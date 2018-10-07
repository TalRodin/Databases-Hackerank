# Databases-Hackerank

Basics of Sets and Relations #1

You are given two sets. 
Set A = {1,2,3,4,5,6} 
Set B = {2,3,4,5,6,7,8}

How many elements are present in A U B? 
Only enter the correct integer in the answering box. Do not include any extra spaces, tabs or newlines.

Answer: 8

A U B ( U - or) = A + B - A and B 
A U B = {1,2,3,4,5,6} + {2,3,4,5,6,7,8} - {2,3,4,5,6} = {1,2,3,4,5,6,2,3,4,5,6,7,8}-{2,3,4,5,6}={1,2,3,4,5,6,7,8}

Basics of Sets and Relations #2

You are given two sets. 
Set A = {1,2,3,4,5,6} 
Set B = {2,3,4,5,6,7,8}

How many elements are present in A and B? 
Only enter the correct integer in the answering box. Do not include any extra spaces, tabs or newlines.

Answer: 5
A U B ( U - or) = A + B - A and B 
A and B = A + B  - A U B ( U - or)You are given two sets. 
A U B = {1,2,3,4,5,6} + {2,3,4,5,6,7,8} - {1,2,3,4,5,6,7,8} = {1,2,3,4,5,6,2,3,4,5,6,7,8} - {1,2,3,4,5,6,7,8} = {2,3,4,5,6}

Basics of Sets and Relations #3

Set A = {1,2,3,4,5,6} 
Set B = {2,3,4,5,6,7,8}

How many elements are present in A - B? 
Only enter the correct integer in the answering box. Do not include any extra spaces, tabs or newlines.

Answer: 1

A - B = {1,2,3,4,5,6} - {2,3,4,5,6,7,8} = {1}
We substract from set A the values which are in set B if value in set A = value in set B and the result is what left in set A.

Basics of Sets and Relations #4

You are given two sets. 
Set A = {1,2,3,4,5,6} 
Set B = {2,3,4,5,6,7,8}

What is the total number of ordered PAIRS present in the Cartesian Product  AxB? 
Only enter the correct integer in the answering box. Do not include any extra spaces, tabs or newlines.

Answer: 42

set A = 6 values
set B = 7 values
number pairs = 6*7 =42
(1,2) (1,3) (1,4) (1,5) (1,6) (1,7) (1,8) (2,2) (2,3) (2,4) (2,5) (2,6) (2,7) (2,8) (3,2) (3,3) (3,4) (3,5) (3,6) (3,7) (3,8)
(4,2) (4,3) (4,4) (4,5) (4,6) (4,7) (4,8) (5,2) (5,3) (5,4) (5,5) (5,6) (5,7) (5,8) (6,2) (6,3) (6,4) (6,5) (6,6) (6,7) (6,8)
(7,2) (7,3) (7,4) (7,5) (7,6) (7,7) (7,8) (8,2) (8,3) (8,4) (8,5) (8,6) (8,7) (8,8)

Basics of Sets and Relations #5

Consider the following data table named Student.

Student Name    Number  Sex  
Ben             3412    M  
Dan             1234    M  
Nel             2341    F  
What is the count of rows returned in the following relational selection? 
σ(Number<3000)(Student)

Only enter a single integer. Do not include any extra spaces or newlines.

Answer: 2

Number 3412 < 3000 and Number 2341 < 3000

Basics of Sets and Relations #6

Consider the following data table named Student.

Name                Number  Sex  
Nina                3412    F 
Mike                1234    M  
Nelson              2341    F  
What is the count of attributes (columns) returned in the following projection? 
π(Name, Number)(Student)

Only enter a single integer. Do not include any extra spaces or newlines.

Answer: 2 

Name, Number

Basics of Sets and Relations #7

Consider the following data table named Student.

Student Name        Number  Sex  
Nina                3412    F 
Mike                1234    M  
Nelson              2341    F  
Here is another data table named Teaching Assistants

Subject     ID
Physics     3412
Chemistry   1111
Mathematics 2341

What is the count of rows returned in the following join operation? 
Student ⊳⊲(Number=ID) Teaching Assistants

Only enter a single integer. Do not include any extra spaces or newlines.

Answer: 2 

Number=ID=3412
Number=ID=2341








