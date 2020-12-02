# There are 3 sections in this ReadMe.

### Section 1: Installing MingW + Adding to environment PATH
To run this program, you should have MingW installed in your PC, and added to PATH. <br/>
if you already have MingW, and added it to your environment PATH, you can skip this step.

To download MingW, you can go to the link: [here](https://osdn.net/projects/mingw/downloads/68260/mingw-get-setup.exe/)


Once downloaded, please install the MingW.
During installation, please note the directory that the MingW is installed. 
You can copy it first, as it will be used later in adding MingW to path.<br/>
![Alt text](mingw_image/install_dir.png?raw=true "Get installation directory")

During installation, just follow the instructions on the screen such as pressing "next" and "continue".<br/>

Once done, go to File Explorer by pressing Win + e.<br/>

In the file explorer, go to System by right clicking on "This PC", then clicking on "Properties"<br/>
![Alt text](mingw_image/system.png?raw=true "Go to System")

Then, go to "Advanced System Settings"<br/>
![Alt text](mingw_image/advanced_settings.png?raw=true "Go to Advanced System Settings")

Then, go to "Environment Variable"<br/>
![Alt text](mingw_image/environment_variable.png?raw=true "Go to Environment Variable")


In "Environment Variable", Click on "Path" near the bottom of the screen, and click "Edit" <br/>
![Alt text](mingw_image/environment_path.png?raw=true "Edit environment PATH")

In "Edit Environment Variable", click "New" to add new Environment Variable to the PATH <br/>
![Alt text](mingw_image/new_environment_path.png?raw=true "Add new environment PATH")

Then, paste in the path you installed your MingW , add in **"\bin"**, and press "Enter" <br/>
![Alt text](mingw_image/add_mingw.png?raw=true "Add MingW to path")

Then, click "Ok", and close all windows. You have successfully added MingW to the environment PATH.