# cs334-assignment-3-solved
**TO GET THIS SOLUTION VISIT:** [CS334 Assignment 3 Solved](https://www.ankitcodinghub.com/product/cs334-assignment-3-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;116255&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS334  Assignment 3 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (1 vote)    </div>
    </div>
Please complete a report and upload the corresponding codes.

The files should be uploaded directly without compression without compression without compression without compression

The files to be submitted for this assignment are:

1. report.pdf

2. ex1.zip

3. ex2.zip

4. ex3.zip

EX0. CPU Scheduling [25pts]

Consider the following single-threaded processes, and their arrival times, estimated CPU costs and their priorities (a process with a higher priority number has priority over a process with lower priority number):

Process Estimated CPU Cost Arrives Priority

A 4 1 1

B 1 2 2

C 3 5 3

D 2 4 4

Ignore context switching overhead.

If a process arrives at time x, they are ready to run at the beginning of time x.

Highest response ratio next (HRRN) is a non-preemptive scheduling algorithm. In HRRN, the next job is not that with the shorted estimated run time, but that with the highest response ratio defined as: 1 + waiting time / estimated CPU time.

Newly arrived processes are scheduled last for RR. When the RR quanta expires, the currently running thread is added at the end of to the ready list before any newly arriving threads.

The quanta for RR is 1 unit of time.

Average turn-around time is the average time a process takes to complete after it arrives.

SJF is non_preemptive.

Priority scheduler is preemptive.

Given the above information please fill in the following table.

Time HRRN FIFO/FCFS RR SJF Priority

1

2

3

4

5

6

7

8

9

10

Avg. Turn-around Time

EX1. Implement a syscall that can set the priority of current process [15pts]

We already add an integer named labschedule_priority which represents the priority of process in PCB. When the PCB initializes, the labschedule_priority will be set 1.

Please implement a syscall that can set the priority of current process (the priority is given). And you need to print some information like ‘set priority to 5’ after the priority are modified.

To test your code, you need to run user program ex1 . Please release annotations in the main function in ex1.c . Other contents are prohibited to modify in ex1.c . And you should let user_main to run ex1 instead of rr .

Tips:

syscall number is 255.

Some file that you probably need to modify:

ulib.c , syscall.c in /user/libs unistd.h in /libs

some files in /kern/syscall and kern/process

Please show your design idea, modified code(screen-shot) and the running result(screen-shot) in your report.

Sample:

EX2. the RR scheduling Algorithm based on Priority

[20pts]

Please complete the ex2 based on ex1

In this week’s lab, every child process get the same time slice. So, we want to set different time slices for different child process according to the priority. The child process that have high priority will get more time slices for each turn.

Please set the time slice to max_time_slice* priority when the child process enqueue the run queue. And you need to print the information of time slice to show your modification.

To test your code, you need to run user program ex2 . Please release annotations in the main function in ex2.c . Other contents are prohibited to modify in ex2.c . And you should let user_main to run ex2 instead of rr .

Please show your design idea, modified code(screen-shot) and the running result(screen-shot) in your report.

Sample:

EX3. Preemptive process scheduling [40pts]

In ex3, we will implement preemptive scheduling.

Please unable the clock interrupt first.

In PCB, we add another integer name labschedule_good and the initial number is 6. You need to implement a syscall to let user process set labschedule_good .

In this scheduling algorithm, we need to choose the process with the largest good value to run when scheduling.

That is to say, when a process call syscall to set its labschedule_good smaller, it will be preempted by a runnable process with a larger labschedule_good .

If processes have same labschedule_good , they are scheduled by fifo.

You need to realize this scheduling algorithm by modify default_sche.c .

To test your code, you need to run user program ex3 . Please release annotations in the main function in ex3.c . Other contents are prohibited to modify in ex3.c . And you should let user_main to run ex3 instead of rr .

Please show your design idea, the running sequence of processes, modified code(screen-shot) and the running result(screen-shot) in your report.

Sample:
