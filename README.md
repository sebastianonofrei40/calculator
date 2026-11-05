# Calculator
A Python 3 calculator used from the Terminal, built step by step in SCCM4910.

## What it will do
Add, subtract, modify and divide two numbers; display the result.

## How to run it
Python 3 must be installed first.
Run: ./run.sh from the calculator directory.
Enter the first number, operator (+ - * /), then second number.
The program prints Result: followed by the answer.

## Sample test
Enter 6, *, 7, then expect "Result: 42.0".

## How to stop
Enter Ctrl+C; the application may print KeyboardInterrupt.

## Test script
Run source /opt/python-venv/sccm-4910/bin/activate followed by python3 -m pytest --version to activate the SCCM4910 virtual environment.
Then, run ./check.sh to test the application on addition, multiplication, division, subtraction and division of odd numbers.
If all tests succeeded, the script should print "QUALITY GATE PASSED".
Following the test, run echo $? to check the exit status of the script.
0 indicates all tests succeeded, 1 indicates some tests failed while 5 indicates no tests were collected.

