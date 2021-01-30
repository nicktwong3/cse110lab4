#1
At line 11, the console will print the value of prices.length because i is declared with var.
#2
At line 12, the console will print the value of the last discounted price because discountedPrice is declared with var.
#3
At line 13, the console will print the last value of finalPrice because finalPrice is declared as var.
#4
The function will return [50,100,150] because it will calculate half of each of the values of the input array and then round the value to two decimals and push it to the returned array
#5
At line 11, the console will throw an error because the variable i is declared with let in the scope of the for loop. Therefore, it no longer exists after the loop exits when the console.log is called
#6
At line 12, the console will throw an error because the variable discountedPrice is declared with let inside of the for loop. It is not visible outside the loop, where the console.log is called
#7
At line 13, the console should print the last value of finalPrice because it is finalPrice is declared outside of the for loop, within the same scope as the console.log call. However, considering that the two previous lines throw errors, we would not reach line 13 if the function were called.
#8
The function will not return because it cannot find the value of i for the console.log at line 11.
#9
At line 11, the console should still throw an error because the variable i is declared with let in the scope of the for loop. So it is not visible by the console.log call. However, because finalPrice is declared as a const, the computer will throw an error when we try to assign it a value at line 7.
#10
At line 12, the console should throw an error because the variable discountedPrice is declared with const within the for loop. It is not visible outside the for loop by the console.log call. However the same issue with the const finalPrice being assigned a value will stop the code before it reaches the console.log call.
#11
At line 13, the console should print 0 because finalPrice is declared with const and assigned 0 in the function's scope. However, because the code attempts to assign finalPrice a value in the for loop, the code will throw and error and stop before exiting the loop.
#12
The function will not return because the code will stop on an error at line 7.
#13
##A
student.name
##B
student['Grad Year']
##C
student.greeting()
##D
student['Favorite Teacher'].name
##E
student.courseLoad[0]
#14
##A
32 will be printed because '3' will cause the + to act as a concatenation operator
##B
1 will be printed because - is only a mathematical operator, so the computer converts the string to a number
##C
0 will be printed because the null is converted to a number as 0
##D
3null will be printed because the null will be converted to the string 'null'
##E
4 will be printed because true will be converted to the number 1
##F
0 will be printed because + defaults to addition, and false and null both are converted to 0
##G
3undefined will be printed because undefined will be converted to the string "undefined"
##H
NaN will be printed because the numerical conversion of undefined is NaN
#15
##A
true because js converts different values to numbers for comparison
##B
false because strings are compared lexicographically
##C
true because js converts different values to numbers for comparison
##D
false because === also compares data type
##E
false because true becomes the number one for different data type comparison which is not equal to 2
##F
true because Boolean(2) is true
#16
The difference between == and === is that == will perform type conversion to compare, while === will use the data type as a basis of inequality.
#17
'How are you?' will be printed because true==2 is false, but Boolean(2) is true.
#19
The function should return the array [6,8,10] because it creates the output array by adding 2 to the element of the input array and then doubling it before pushing it to the output array.
#21
The program will output 1 and then 4 on individual lines. Then it will print 3 after a short delay, and then 2 after 1 second.
