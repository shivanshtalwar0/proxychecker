# proxychecker
High Performant,MultiThreaded, C Based proxy checker Tool which makes validating and checking millions of proxy in almost no time.
![alt text](https://github.com/shivanshtalwar0/proxychecker/blob/master/example.png)


# Dependencies Installation
This tool depends on two of python 2.7 packages to run make sure to install them via pip inorder to have this tool running without any issues.
execute the following command to satisfy all dependencies.
  <code style='background-color:black color:white'>pip install tqdm requests</code><br>

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

