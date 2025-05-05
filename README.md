# ee451-assignment-2-solved
**TO GET THIS SOLUTION VISIT:** [EE451 Assignment 2 Solved](https://www.ankitcodinghub.com/product/ee451-assignment-2-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;100468&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;EE451 Assignment 2 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 0px;">
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
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
1. Examples

<ul>
<li>A Pthreads example code, “print msg with join.c”, which prints a hello message
in each thread. To compile and run it,

1 2

Here ‘-c’ specifies the number of CPUs (threads) you will be using. In this case, the code is run with 4 CPUs.
</li>
<li>A Pthreads example code that uses a mutex, “increase shared var.c”, which lets 2 threads increase a shared variable. To compile and run it,
1 2
</li>
<li>A Pthreads example code that uses a mutex and a condition variable, “increase shar ed var cond.c”, which lets 2 threads take turns to increase a shared variable. To compile and run it,
1 2

2. Parallel Matrix Multiplication

Use Pthreads to implement a parallel version of your naive matrix multiplication code from PA1. Set the number of threads p = 1,2,4,8. For each value of p, print out the value of C[100][100] and the execution time. Plot the execution time w.r.t. p, and briefly discuss your observation (you don’t need to plot in the program). Name your program ‘problem2a.c’.

3. Producer-Consumer Problem

The producer-consumer problem (also known as the bounded-buffer problem) is a classic example of a multi-thread synchronization problem. In this assignment, you will simu- late the producer-consumer problem using a mutex and a condition variable. Producer makes cookies and puts cookies on the shelf. Consumer buys cookies and takes cookies away from the shelf. The simulation works as follows.
</li>
</ul>
<ul>
<li>There are two consumers and one producer. Each producer or consumer is imple- mented as a thread.</li>
<li>The capacity of the shelf is 10. Initially, the shelf is empty.
&nbsp;
</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
gcc -O3 -o run print_msg_with_join.c -lpthread srun -n1 -c4 ./run

</div>
</div>
<div class="layoutArea">
<div class="column">
gcc -O3 -o run increase_shared_var.c -lpthread srun -n1 -c2 ./run

</div>
</div>
<div class="layoutArea">
<div class="column">
gcc -O3 -o run increase_shared_var_cond.c -lpthread srun -n1 -c2 ./run

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
<ul>
<li>When the producer checks the number of cookies on the shelf, (1) if the number is less than 9, the producer puts 2 cookies on the shelf; (2) if the number is 9, the producer puts 1 cookie on the shelf.</li>
<li>When the shelf is not empty, a consumer thread can only take 1 cookie at a time.</li>
<li>If the producer thread has put ≥ 30 cookies on the shelf, it can be terminated.</li>
<li>If a consumer thread has taken 15 cookies away from the shelf, the consumer thread can be terminated.</li>
<li>Whenever the number of cookies on the shelf changes, you need to print a message in the following format.
<ul>
<li>– &nbsp;Producer has put 2 cookies; # of cookies on the shelf changes from 0 to 2.</li>
<li>– &nbsp;Consumer 2 has taken 1 cookies; # of cookies on the shelf changes from 2 to
1.
</li>
<li>– &nbsp;Producer has put 4 cookies1; # of cookies on the shelf changes from 1 to 3.</li>
<li>– &nbsp;Consumer 1 has taken 1 cookies; # of cookies on the shelf changes from 3 to 2.</li>
<li>– &nbsp;Consumer 1 has taken 2 cookies2; # of cookies on the shelf changes from 2 to 1.</li>
<li>– &nbsp;Consumer 1 has taken 3 cookies; # of cookies on the shelf changes from 1 to 0.</li>
<li>– &nbsp;…

Please implement 2 versions of the simulation:</li>
</ul>
<ol>
<li>Using mutex only

In this version, when each thread intends to check/update the number of cookies on the shelf, the thread needs to acquire the mutex first in order to avoid any race condition. Here, only mutex is used. Name this program ‘problem2b1.c’.</li>
<li>Using mutex and condition variable

In this version, when the producer checks the number of cookies on the shelf, if the number is 10, the producer goes to sleep; if the number is 0, the producer puts 2 cookies on the shelf and sends a broadcast signal to wake up the consumers. When a consumer checks the number of cookies on the shelf, if the number is 0, the consumer goes to sleep; if the number is 1, the consumer takes 1 cookie and wakes up the producer. Initially, all threads are awake. Name this program ‘problem2b2.c’.</li>
</ol>
1This is an accumulative number. The producer has put 2+2 = 4 cookies so far. 2This is an accumulative number. Consumer 1 has taken 1+1=2 cookies so far.
</li>
</ul>
</div>
</div>
<div class="layoutArea"></div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
4. Submission

</div>
</div>
<div class="layoutArea">
<div class="column">
<ul>
<li>Three .c files: ‘problem2a.c’ for parallel matrix multiplication; ‘problem2b1.c’ and ‘problem2b2.c’ for the producer-consumer problem. Make sure your programs are runnable. (10+10+10 pts)</li>
<li>Screenshotsoftheprogramoutputsforparallelmatrixmultiplication(p=1,2,4,8). (10 pts)</li>
<li>Plot of execution time and your observation for parallel matrix multiplication. (5 pts)</li>
<li>Screenshots of the program outputs for the producer-consumer problem (version 1&amp;2). (5 pts)</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column"></div>
</div>
<div class="layoutArea"></div>
</div>
