# proxychecker
High Performant,MultiThreaded, C Based proxy checker Tool which makes validating and checking millions of proxy in almost no time.

# Compilation for Linux
Linux Executable is already included in Repository named proxychecker-1.0_linux<br>
you can run the tool directly without compiling for linux<br>
<b>Steps to run the Tool<b><br>
(1) open Terminal<br>
(2) Run the code below<br>
  <code style='background-color:black color:white'>./proxychecker-1.0_linux --inputproxyfile million.txt --outputproxyfile wow.txt</code><br>
or<br> 
you can compile simply using gcc<br>
<code style='background-color:black color:white'>
gcc -I /usr/include/python2.7/ proxychecker.c -o proxychecker-1.0_linux -lpython2.7 -lm -lutil -ldl
</code>

