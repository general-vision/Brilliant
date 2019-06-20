## Brilliant
NeuroMem USB dongle (Brilliant with 4 NM500 chips) features 2304 neurons ready to learn and recognize patterns extracted from your signal, images, measurements and other data source.

## Cypress USB driver
If you have never connected a device on your PC using a Cypress USB chip, the NeuroMem dongle will not be detected unless you run the CypressDriverInstaller.exe

Under the Windows Device Manager,the NeuroMem USB dongle should appear as a Universal Serial Bus Controller with the label "Cypress FX2LP Streamer Example device"

## NeuroMem Console
Windows-based utility to test the good health of the dongle but also to experience with the neurons using simple Register Transfer Level transactions.

Open the console using Start/General Vision/NeuroMem Console.
The default platform shown in the upper left corner of the panel is "Simu" and the network capacity reported in the listbox to the right is 1024 neurons.
Change the platform to Brilliant and verify that the network capacity reported in the listbox to the right is 2304 neurons.

Fr more information on how to use the NeuroMem Console, click the Help button or refer to https://www.general-vision.com/documentation/TM_NeuroMem_Console.pdf.

## GV_NeuroMem API
- C++ library to access the neurons through the NeuroShield USB-serial port
- Academic script to understand how to teach and query the neurons
- For the latest documentation, refer to https://www.general-vision.com/documentation/TM_NeuroMem_API.pdf

Note that this API is delivered for Windows. Adapting its source code to Linux should just involve linking to the Cypress USB driver for Linux.


## For additional tools compatible with NeuroMem USB dongle, visit our web site:

- **NeuroMem Knowledge Builder** (https://www.general-vision.com/product/nmkb/)
- **CogniPat SDK** (https://www.general-vision.com/product/cp-sdk/)
- **CogniPat SDK MatLab** (https://www.general-vision.com/product/cp-sdk-ml/)
- **CogniPat SDK LabVIEW** (https://www.general-vision.com/product/cp-sdk-lv/)

