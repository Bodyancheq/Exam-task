# Exam-task
This is last and the hardest task from russian exam UNE (ЕГЭ on russian) for 11th grade graduates.
You have unknown amount of natural numbers, but more than two and the end of the line is number 0. After the line comes expected
number. Program should find highest possible multiplication of 2 numbers that is divisible by 7, but aren't divisible by 49. If there is 
no such multiplication then the result should be 1.
Examle of input data:
6
7
8
9
0
64

Example of output data:
Total numbers: 4
Expected number: 64
Calculated number: 63
Numbers dont match

The program uses BREAK keyword. The point of my program is to find the highest number that is divisible by  7 and not by 49 and to find
the highest nubmer that is not divisible by 7. The number is divisible by 49 when the are at least two numbers that are divisible by 7
or 1 that is divisible by 49. On each iteration I will match my current number with max number from previous iterations and compare it 
to my multiplication that is stored in variable M.
