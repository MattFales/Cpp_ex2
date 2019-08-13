Matthew Fales
==========Code environment=======================
Linux version 4.15.0-43-generic (buildd@lgw01-amd64-001) 
(gcc version 7.3.0 (Ubuntu 7.3.0-16ubuntu3)) #46-Ubuntu SMP Thu Dec 6 14:45:28 UTC 2018



===========What the program does==================
This program takes 1 argument which is supposed to be parentheses ()[]{}
with no spaces between.  This program will tell you if these are legal 
and valid ways of order of operations.
Examples:
{}{}({})
{{{{}}}}
(((())))
{(})
=========How is it different=======================
It is the same format as the first version of this but this now split up into easier to 
maintained methods.
==================Output Example========================
Input: ./ts '{}{}({})'
You have put in 2 arguments
valid
Time: 0.07

Input: ./ts '{{{{}}}}' 
You have put in 2 arguments
valid
Time: 0.077

Input: ./ts '(((())))'
You have put in 2 arguments
valid
Time: 0.069

Input: ./ts '{(})'
You have put in 2 arguments
invalid
Time: 0.065

==============Files included=====================
Makefile
ts.cc


=============How to run=========================
1. open terminal  type make  # this is for the make file
2. type: ./ts '{}'  #Please use single quotes
============If problems happen=========================
1. in the terminal use make clean
2. then use make
