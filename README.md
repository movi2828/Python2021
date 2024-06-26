# Python2021
Exercice Python analyse fichier

## Introduction

An access log file of a web server in common log format (CLF) should be evaluated with the aim to determine potential source IP addresses of DDoS attacks.
Goals and Tasks

Develop a Python program which meets the following requirements:

- The program should read the given log file access.log as an argument. If no argument is specified on the command line, a corresponding message must be printed and execution must be aborted.
- The program reads and counts the occurrence of every source IP address (origin IP) in the log file. We recommend the use of the class collections.Counter.
- The program creates an ordered list with pairs of keys (IP addresses) and values (counter), ordered by max count of occurrence descending.
- The program must write the ordered key value pairs into a JSON file named results.json, representing every pair on a new line.
- Errors in file handling: The program must print a specific error message to the console, distinguishing errors while reading or writing files.
- In terms of code quality, the program must be commented sensibly.

## Submission

Submit a ZIP archive containing your Python program (regardless of whether it is finished or not) and the generated output file (if available). Ensure that used external modules are properly declared with import statements.
