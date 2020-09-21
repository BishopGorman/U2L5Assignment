# U2L5: Assignment - Calling Methods That Return Values
Homework Problems for CSAwesome Unit 2

## Construction Costs
### Statement
The `Construction` class is completed for you and you will use it as a client, but you may want to look at it to make sure you understand how to use it.

Then write a program in the `main` method that asks the user to enter the sales tax rate as a decimal, the number of boards needed, and the number of windows needed.

Create a `Construction` object to compute the cost of the lumber and windows. Use $8 for the cost of lumber. Use $11 for the cost of windows.
Print the total cost. Then use the method to compute the tax and print out the grand total including tax.
 
### Example input
`7500`
 
### Example output
```
Enter the sales tax rate: 
.08
How many boards do you need? 
10
How many windows do you need? 
5
Total: 135.0
Grand Total: 145.8
```


## TimeStamps.java
### Statement
Given two timestamps of the same day: a number of hours, minutes and seconds for both of the timestamps. The moment of the first timestamp happened before the moment of the second one. Calculate how many seconds passed between them.
 
### Example input #1
```
1
1
1
2
2
2
```
 
### Example output #1
`3661`
 
### Example input #2
```
1
2
30
1
3
20
```
 
### Example output #2
`50`

## StudentDesks.java
### Statement
A school decided to replace the desks in three classrooms. Each desk sits two students. Given the number of students in each class, print the smallest possible number of desks that can be purchased.
 
The program should read three integers: the number of students in each of the three classes, a, b and c respectively.
 
In the first test there are three groups. The first group has 20 students and thus needs 10 desks. The second group has 21 students, so they can get by with no fewer than 11 desks. 11 desks is also enough for the third group of 22 students. So we need 32 desks in total.

 
### Example input
```
20
21
22
```
 
### Example output
`32`

## AnalogClock.java
### Statement
The hour hand of an analog clock turned α degrees since midnight. Determine the angle by which the minute hand turned since the start of the current hour. Input and output in this problem are integers.

 
### Example input
`190`
(6:20)
 
### Example output
`120`
(20 minutes)
