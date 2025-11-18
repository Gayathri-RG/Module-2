Exp.No:2(a)	ITERATIVE STATEMENTS- PRINTING DIVISIBLE BY 11 NUMBERS
### AIM
To create a  print  numbers  range from M to N (including M and N values) divisible by 11 in reverse order.
### ALGORITHM

Start

Read integer a from the user.

Read integer b from the user.

Loop from i = b down to a (inclusive):

Use a for loop: for i in range(b, a - 1, -1)

Check if the current number i is divisible by 11:

If i % 11 == 0, then:

Print i

End

### PROGRAM
```
Reg no:212223060015
Name:Amrin Shifa S
a=int(input())
b=int(input())
for i in range(b,a-1,-1):
    if i%11==0:
        print(i)
```
### OUTPUT
![image](https://github.com/gokulkrishnan2005/19CS301-Module2/blob/main/LL.png)

 
### RESULT
Thus the python program for print  numbers  range from M to N (including M and N values) divisible by 11 in reverse order has been implemented and executed successfully.
