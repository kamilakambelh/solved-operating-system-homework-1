Download Link: https://assignmentchef.com/product/solved-operating-system-homework-1
<br>
<h1>Part I</h1>

As a preparation step for the second part of this and later homework assignments, for the first part of this homework assignment, you are required to do the following.

<ol>

 <li>Install Linux on your computer. It is up to you to choose a distribution that you prefer.<sup>1 </sup>Make sure that it can connect to the Internet.</li>

 <li>Recompile the kernel that comes with the Linux distribution you chose. Make sure that the version numberof the newly compiled kernel is the original version number suffixed with your student ID. For instance, the student ID of one of your TA’s is m983040031, and the version number of the kernel is 2.6.37.4, then the version number of the newly compiled kernel will be 2.6.37.4-m983040031.</li>

</ol>

<sup>1</sup>Here are some Linux distributions that you might be interested.

<ul>

 <li>Debian: <a href="https://www.debian.org/">http://www.debian.org/</a></li>

 <li>Fedora: <a href="https://fedoraproject.org/">http://fedoraproject.org/</a></li>

 <li>Gentoo: <a href="https://www.gentoo.org/">http://www.gentoo.org/</a></li>

 <li>Ubuntu: <a href="http://www.ubuntu.org.tw/">http://www.ubuntu.org.tw/</a></li>

</ul>

Hand in a report to show that the newly compiled kernel works by showing the output of the following commands:

<ul>

 <li>uname -a</li>

 <li>ifconfig -a</li>

 <li>ping 140.117.11.1</li>

</ul>

Make sure that your TA’s can log in to your system to verify the results you show on the report.

If you never use Linux before, start earlier. It may take you quite a while to get it up and running.

<h1>Part II</h1>

For the second part of this homework assignment, you are required to write a shell that is similar to Fig. 1–10 of the text but contains enough code so that it actually works and you can use it as a shell on Linux.

For full credits, here are the minimum requirements of the shell you are required to write.

<ol>

 <li>It should be able to run all the single-process commands.</li>

 <li>It should be able to run all the two-process pipelines, the skeleton of which is as given in Fig. 1–13 of thetext.</li>

 <li>It should be able to handle input and output redirection.</li>

 <li>It should be able to execute commands in the background.</li>

</ol>

You are, of course, free to add more features to the shell you write.

In addition, all the programs you write must be well organized and come with a Makefile that can be used to correctly compile your program. <em>Without a Makefile, your homework assignment will not be graded—meaning that you will receive zero points.</em>