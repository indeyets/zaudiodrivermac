EMU USB Audio Driver for Mac

Several build targets exist.   All but the release target requires that FireLog be 
running on the test machine.  

The file kextInstall should be placed in your home directory.  

If you copy the kext file to your home directory and run kextInstall, the driver should
then be loaded on your machine.  

You could add a build step to your project to automate this process. 

The driver should work w/ existing EMU USB audio products. 


