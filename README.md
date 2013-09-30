                                      
   
<html>
<head>

<title>Read Me</title>

</head>

<body bgcolor="#999999">
<blockquote>
  <h1 align="center" class="style1">SANTA CLAUS PROBLEM</h1>
  <p><font face="Times New Roman, Times, serif"><span class="style2">The problem</span></font><font face="Times New Roman, Times, serif" size="+6">:</font> Santa Claus sleeps at the North pole until awakened by either all
    of the nine reindeer, or by a group of three out of ten elves. He
    performs one of two indivisible actions:</p>
  <p>*If awakened by the group of reindeer, Santa harnesses them to
    a sleigh, delivers toys, and finally unharnesses the reindeer who
    then go on vacation. </p>
  <p>*If awakened by a group of elves, Santa shows them into his
    office, consults with them on toy R&amp;D, and finally shows them
    out so they can return to work constructing toys. </p>
  <p>A waiting group of reindeer must be served by Santa before a waiting
    group of elves. Since Santa&rsquo;s time is extremely valuable, marshalling
    the reindeer or elves into a group must not be done by Santa. </p>
  <p><span class="style3"><span class="style2">The Solution</span>:</span>We now give an outline of the solution using semaphores, omitting the details
    of the calculations of the global variables and the semaphores protecting them.
    There is a single Santa process which waits on the semaphore Santa; it will
    be awakened by the ninth reindeer or the third elf. If awakened by the last
    reindeer, Santa executes as follows: awaken the eight other reindeer, harness all
    nine reindeer to the sleigh, deliver the toys and unharness the reindeer.</p>
  <p align="center" class="style1">&nbsp;</p>
  <p align="center" class="style1">&nbsp;</p>
  <p align="right">&nbsp;</p>
  <blockquote>
    <p align="right"><img src="santa.jpg" alt="Santa" width="175" height="175" vspace="0" align="left" /><img src="elf.jpg" alt="elf" width="133" height="168" />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="rend.jpg" alt="reindeer" width="100" height="100" /></p>
  </blockquote>
  <blockquote>
    <p>&nbsp;</p>
    <p>&nbsp;</p>
    <p><strong>THE SOLUTION TO THIS PROBLEM IS DISCRIBED UNDER FOLLOWING LINKS::::::::::::::: </strong></p>
    <form>
      
 	<input name="BUTTON" type="BUTTON" onclick="window.location.href='Semaphores_and_critical section.html'" value="Semaphores/critical section" /><br>
 	<input name="BUTTON" type="BUTTON" onclick="window.location.href='busy.html'" value="busywaiting" /><br>
 	<input name="BUTTON" type="BUTTON" onclick="spinlock.html'" value="Monitors" /><br>
	<input name="BUTTON" type="BUTTON" onclick="window.location.href='http://localhost/git%20hub/Monitors.html'" value="Monitors" /><br>
  </form>
</blockquote>
</body>

</html>
                                  

  
   
   
