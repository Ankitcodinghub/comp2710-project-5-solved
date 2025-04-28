# comp2710-project-5-solved
**TO GET THIS SOLUTION VISIT:** [COMP2710 Project 5 Solved](https://www.ankitcodinghub.com/product/comp-2710-project-5-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;117692&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;COMP2710 Project 5 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (2 votes)    </div>
    </div>
&nbsp;

Objectives:

1. Complete the source code to simulate producer/consumer problem.

2. Understand the basics of the POSIX thread library.

3. Build a binary program on a Linux machine.

4. Run the program and record the result of the simulation.

Requirements:

• You are highly recommended to use a Linux operating system, because “pthread.h” is a header for the Unix/Linux (POSIX) API for threads.

1. Introduction to producer and consumer model

1. Producer: One or multiple processes/threads that produce data or release hardware resource.

2. Consumer: The one process/thread that takes in data or uses hardware resource to do computations.

A producer could also be relatively a consumer to the output of another producer and vice versa.

3. Buffer: The destination to store the output from producers or resources and later accessed by another consumer.

Other concepts involved in our project:

4. POSIX thread: Threads mechanism that satisfy POSIX standard (most operating system).

5. Mutex: A “lock” that guarantee that only one person has the access.

In this project we use POSIX threads. The “pthread” is a POSIX thread library written in C++ and provides the basic functions.

To simplify our simulation, we assume there are only 2 POSIX threads. One is the consumer, the other is the producer. The producer generates 1 unit data each time to the buffer, and the consumer takes 1 unit data from the buffer each time. The size of the buffer is 1. One unit data is just one integer. The producer generates integers 7, 14, 21 …. into the buffer and consumer read them out from the buffer.

2. Follow the Format Specification (10 Points)

In the source file “project5_LastName_UserID.cpp”, you will find first four comment lines:

// #0#BEGIN# DO NOT MODIFY THIS COMMENT LINE!

// Firstname

// Lastname

// #0#END# DO NOT MODIFY THIS COMMENT LINE!

Your first task is modifying the two lines between the beginning line and end line. Change them into your first name and last name. Remember the strings are case-sensitive, so capitalize the first letter of the word and follow exactly the syntax of the example.

You can see lots of similar code blocks in the file. You are supposed to fill your answer between those special beginning and ending comment lines. You can insert and edit multiple lines between special comment lines in anyways, however (Important!), as the comment indicated, do not modify the special begin and comment lines themselves!

Let’s do the second task. Scroll down to the bottom of the file and find those lines (press “shift + g” if you are using vi/vim):

// #8#BEGIN# DO NOT MODIFY THIS COMMENT LINE! int banner_id = 0;

// #8#END# DO NOT MODIFY THIS COMMENT LINE!

Look at your student ID card, check your banner ID. Again, change ZERO to your own ID. Your unique student id will be compiled into the program, and the input of the experiment also uniquely depends on your ID.

3. Complete Source Code (70 Points)

Read the source code and the rest comments, try to understand the function of each line of code, the basic usage of “pthread” library function and semaphore from the example code of producer and from the main function.

Follow the instructions in the comments and insert proper code into the rest 7 blocks to implement a producer/consumer model.

4. Run and Record Simulation Result (10 Points)

Your correct file name should be: project5_LastName_UserID.cpp

For example, project5_Liu_tzl0031.cpp. Please remember to change the lastname and userID to your own ones before you continue the following steps.

Compile your source code into a binary program. For example, use following command to include the pthread library:

$ g++ project5_Lastname_UserID.cpp -o project5_LastName_UserID -lpthread

After you compile the C++ source code successfully, please use the script command to record the running result of the program Firstname_Lastname:

$ script project5_LastName_UserID.script

Script started, file is project5_LastName_UserID.script

./project5_LastName_UserID

After you run the program, you will have the following results:

Banner id: 90…….

producer produce item 7 consumer consume item 7 producer produce item 14 consumer consume item 14 producer produce item 21 consumer consume item 21 producer produce item 28 consumer consume item 28 producer produce item 35 consumer consume item 35 producer produce item 42

consumer consume item 42

…

You should have the same result except the different in the banner ID. Then exit recording and save it into typescript file “project5_LastName_UserID.script” by the following command:

$ exit

exit Script done, file is project5_LastName_UserID.script

5. Deliverables (10 Points)

Since you have generated multiple script files, please save all the script files in one directory. Make sure all the three files are into this folder. You should have those following files inside the folder:

1. Commands recording file: project5_LastName_UserID.script

2. Executable binary file: project5_LastName_UserID

3. Source code file: project5_LastName_UserID.cpp

Change the folder name to “project5_LastName_UserID”. Note: It is better to change the name of the folder after the above three files moved into the folder, because of the name conflict. Please make sure the folder name is in a correct form. You can use the command mv to rename the folder:

$ mv your-current-folder-name project5_LastName_UserID

Achieve all the folder into a single tarred and compressed file with a tar command.

tar -zcvf project5_LastName_UserID.tar.gz project5_LastName_UserID

You need to submit one tarred file with a format project5_LastName_UserID.tar.gz through Canvas.

Grading Criteria:

1. Follow the format specification: 10%

a. Do not break the special comments.

b. Input your name properly (mark #0).

c. Input your banner id properly (mark #8).

2. Complete the source code: 70%

a. Each blank is worth 10%, in total 70% (mark #1 ~ #7).

b. See detailed specification for each blank in the source code file.

3. Compiling and running result: 10%

a. Compile the code successfully.

b. Record the running results.

4. Deliverables: 10%

a. Contains all the files.

b. Naming all the files properly.

Rebuttal Period:
