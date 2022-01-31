# Tanner Tools installation

### This guide will help you install tanner tools on your system.

## Extracting and starting installer

- firstly, download the `zip` file from [here](https://drive.google.com/file/d/1JaSDxjCm3xVu80YDV1Opb9b0hotjLqas/view)
- create a folder and extract the contents.
- Go into `orTaT1630\Mentor Tanner Tools 16.30\TannerToolsV16.30-64Bit` and run `setup.exe` as administrator
- Switch off your wifi connection.

## Installer parameters

- On the first page, choose `Typical workstation`, and hit `next`.
- Now select `Local license`.
- Now hit `install`.
On the left top corner of the screen, there will be a menu that will display the progress of the installation.

## Installing Tanner EDA Tools

- Click on the `next` option and accept the required Terms and Conditions. 
- Select the `Anyone who uses this computer (all users)` option and hit `next`.
- Select `next`.
- Choose the Typical option as it will install all the tanner tools.
- Now click on `Install`. This will take some time depending on the system.

## Installing Tanner EDA Utilities

- This is the next (3rd) installation. Proceed with the same steps given above. 

## Tanner licensing Environment

- When the box appears, click on `cancel`.
- Once that is completed, The installation of Tanner tools has been complete. Now we need to proceed with the patching part.

## Patching the applications

- Go one directory back and go into the `patched` folder. You will find multiple files in here.
- Copy all the files.
- Now go to `C:\Program Files\Tanner EDA\Tanner Tools v16.3`
- Paste and replace all the copied files into this folder.
- In the same folder, create a new folder with the name `leagcy`.
- In the legacy folder, you have to paste two files `wedit64.exe` and `ledit64.exe`. Replace if already existing.

## Final touches

- Go into the `ExampleSetup` folder in the Tanner installation directory and run the `setup.exe` as Administrator.
- The example files are placed in `Documents\Tanner EDA` folder.
- Open The UMC technology file in the dowload folder and copy all the files onto the `Features By Tool` folder present in the Documents folder.

With that, tanner EDA tools has been successfully installed onto your system.











