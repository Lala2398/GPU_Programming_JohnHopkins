The goal of this assignment is for the student to create a C++-based implementation of the ticketing parallel programming algorithm. Students will be furnished with a base assignment.cpp and assignment.h, which will hold the scaffolding for implementing a ticketing algorithm with the C++ standard library's thread library.  Students will have the freedom to implement this algorithm using any concurrent capabilities that exist in the C++ 14 STL. They will need to click the two buttons (indicated with Step 1 and Step 2).  There is code within the base .cpp file that outputs logging of thread activity to a text file, do not modify this code, it must be executed before and after each thread has executed, ensuring that all threads complete their participation in the ticketing system, in a parallel manner.

You can modify the code to see what the effect will be.

Write/update the .user file with a username that you will put into your code. This is used as part of execution verification.

Execute make clean build, which will clean and build all of the various examples (atomic, future, mutex, thread).

To execute the code, especially for debugging purposes, you will use the following command line arguments as part of the code execution:    ./assignment.exe numThreads user partId.

Once you are satsified with your work, you can do one of the following to run your code to output graded text files:

Click the Execute Assignment Runs (Part 1) button; or

From the terminal execute a single command make clean build && sh run.sh 1 $(cat .user) 1 uSrKD && sh run.sh 1 $(cat .user) 3 T9bcV && sh run.sh 1 $(cat .user) 20 OISFH; or

Run the individual commands:

make clean build

sh run.sh 1 $(cat .user) 1 uSrKD

sh run.sh 1 $(cat .user) 3 T9bcV

sh run.sh 1 $(cat .user) 20 OISFH

Check that there are 3 output text files and that the content makes sense.

To submit your assignment, click the Submit (Part 2) button.

Note: Make sure that the output for the thread starting log output should start with "C++11: Thread retrieved ticket number: " and the output for the thread completing log output should start with "C++11: Thread with ticket number: ". If this is not reflected in the output files the grader will not parse them correctly.


