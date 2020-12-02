# There are 3 sections in this ReadMe.

### Section 1: Installing MingW + Adding to environment PATH
To run this program, you should have MingW installed in your PC, and added to PATH. <br/>
if you already have MingW, and added it to your environment PATH, you can skip this step.

To download MingW, you can go to the link: [here](https://osdn.net/projects/mingw/downloads/68260/mingw-get-setup.exe/)


Once downloaded, please install the MingW.
During installation, please note the directory that the MingW is installed. 
You can copy it first, as it will be used later in adding MingW to path.<br/>
![ScreenShot](https://raw.githubusercontent.com/ChewBoonZhan/OS_Assignment/main/mingw_image/install_dir.PNG "Get installation directory")

During installation, just follow the instructions on the screen such as pressing "next" and "continue".<br/>

Once done, go to File Explorer by pressing Win + e.<br/>

In the file explorer, go to System by right clicking on "This PC", then clicking on "Properties"<br/>
![ScreenShot](https://raw.githubusercontent.com/ChewBoonZhan/OS_Assignment/main/mingw_image/system.PNG "Go to System")

Then, go to "Advanced System Settings"<br/>
![ScreenShot](https://raw.githubusercontent.com/ChewBoonZhan/OS_Assignment/main/mingw_image/advanced_settings.PNG "Go to Advanced System Settings")

Then, go to "Environment Variable"<br/>
![ScreenShot](https://raw.githubusercontent.com/ChewBoonZhan/OS_Assignment/main/mingw_image/environment_variable.PNG "Go to Environment Variable")


In "Environment Variable", Click on "Path" near the bottom of the screen, and click "Edit" <br/>
![ScreenShot](https://raw.githubusercontent.com/ChewBoonZhan/OS_Assignment/main/mingw_image/environment_path.PNG "Edit environment PATH")

In "Edit Environment Variable", click "New" to add new Environment Variable to the PATH <br/>
![ScreenShot](https://raw.githubusercontent.com/ChewBoonZhan/OS_Assignment/main/mingw_image/new_environment_path.PNG "Add new environment PATH")

Then, paste in the path you installed your MingW , add in **"\bin"**, and press "Enter" <br/>
![ScreenShot](https://raw.githubusercontent.com/ChewBoonZhan/OS_Assignment/main/mingw_image/add_mingw.PNG "Add MingW to path")

Then, click "Ok", and close all windows. You have successfully added MingW to the environment PATH.

### Section 2: Running C program from command prompt

The program can be run from any c compiler including online compiler. Assuming you have gcc and gpp already in ur pc, you should also be able to run the program by typing in the following into the command prompt.

```    gcc -o outputFileName code.c && outputFileName
```

### Section 3: Running and using the software for evaluation

1. When the program successfully runs, it will prompt the user to enter the number of processes they wish to schedule. Note that the program allows users to key in two sets of workload. The prompt that the user will see at the start of the program is the prompt for the first set of workload.

2. Users can then key in the arrival time and burst time of each process accordingly.

3. After entering the workload of each process, the program will prompt the user to choose which scheduling algorithm they wish to use. They can choose either the FCFS algorithm, SJF algorithm or Round-Robin algorithm accordingly. There is also an option where users can choose to run all 3 algorithm for comparison.

4. The program will then show a result analysis of the chosen scheduling algorithm. The analysis displays the arrival time, actual start time, the wait time and the turnaround time for each process. It will also total turnaround time and wait time, as well as the average turnaround time and wait time.

..* *Note : There is a slight difference in the prompt if the users choose to run the Round Robin algorithm*
..a After entering the workloads for each process, users will be prompted for a time quantum. The program will then also ask the users if they wish to include overhead. In this program the overhead for the Round-Robin is set as 1.
..b Besides the usual result analysis, the program also displays a timeline of execution of the processes. The programs displays the remaining time of each process as they finish each round of execution until the reamining time is zero.

5. After the first set of workload is done executing, the program will prompt for a second set of workload. The process for running the second set of workload is similar to the first. 


  
