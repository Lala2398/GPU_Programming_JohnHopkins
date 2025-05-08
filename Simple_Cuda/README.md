# Lab and Project

## Lab
This lab has the same code as the coding assignment in the same lesson. Feel free to explore the existing code or write your own. 

If you would like to build the code, you will need to fix the existing Makefile, simple.cu, and simple.h. Once the code is fixed, you will need to execute the make command with the option build (compile) and run (run the executable).  You can explore the Makefile to see how the build system would clean, compile, and run the project. 

The code in this lab, like the assignment, is written to have you replace keywords and variables in the .cu and .h files to have functions execute on the appropriate hardware.  The multiplication functions should run on the GPU and the rest should run on the CPU.  Note that one multiplication kernel executes another, so keep that in mind when choosing keywords. Lastly the Makefile will need to have you update the COMPILER variable to the appropriate compiler, which should be nvcc.

## Project 

This assignment will challenge you to identify which keywords are to be used to determine where code will be run, use the Nvidia cross compiler, and show a simple understanding of the syntax for determining how CUDA kernels are configured for execution on GPUs.

The code in /home/project will need work in a number of ways to compile and run appropriately.  Note there will be differences with the code in the project folder from what is shown in the video, but the goal is the same, get the simple code in the project folder to build, run, and submit. Keywords for execution, variables, Makefile variables, etc. have been modified to not work.  Once you fix the code, you will need to compile and run the code via the following steps:

Run make clean build from the terminal, to compile the code or identify any existing issues in the CUDA code.

Execute ./simple.exe > output.txt

Click the Submit button on the bottom of the IDE.

Note: There is an erroneous README.md file which has incorrect instructions showing up for some students.  While this gets fixed (and really always) the instructions for the assignment, stated here are the appropriate steps to take.



