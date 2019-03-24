# proxychecker
High Performant,MultiThreaded, C Based proxy checker Tool which makes validating and checking millions of proxy in almost no time.

# Compilation for Linux
Linux Executable is already included in Repository named proxychecker-1.0_linux
you can run the tool directly without compiling for linux
Steps to run the Tool
(1) open Terminal
(2) Run the code below
$>./proxychecker-1.0_linux --inputproxyfile million.txt --outputproxyfile wow.txt
or 
you can compile simply uning gcc
$> gcc -I /usr/include/python2.7/ proxychecker.c -o proxychecker-1.0_linux -lpython2.7 -lm -lutil -ldl


