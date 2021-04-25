# Waynar Bocangel Calderon Lab04 PID: A15881859
## Part 1A
### Question 1
Line 9 prints the sum of num 1 and num 2 "20".
### Question 2
Line 13 prints the sum of num 1 and num 2 "20".
### Question 3
Line 9 prints the sum of num 1 and num 2 "20".
### Question 4
Line 13 causes an error because result is defined only inside the if block while line 13 calls the variable outside of the scope where it was created.
### Question 5
Line 9 is never excecuted because line 8 causes a crash before it since it's trying to change the value of a const variable which is not allowed.
### Question 6
Line 13 is never excecuted because line 8 causes a crash before it since it's trying to change the value of a const variable which is not allowed. If it was executed it would cause a crash because of useing a variable outside of the scope where it was declared.

## Part 1B
### Question 1
Line 12 prints the last value of i in the for loop "3".
### Question 2
Line 13 prints the last value of discountedPrice in the loop which would be "150".
### Question 3
Line 14 prints the last value of finalPrice after the loop which would be "150".
### Question 4
The function will return an array with all the discouted prices which would be "[50, 100, 150]".
### Question 5
Line 12 causes an error since it calls the variable i outside it's scope which is the for-loop.
### Question 6
Line 13 causes an error since it calls the variable discountedPrice outside it's scope which is the for-loop.
### Question 7
Line 14 prints the last value of finalPrice after the loop which would be "150".
### Question 8
The function will return an array with all the discouted prices which would be "[50, 100, 150]".
### Question 9
Line 11 causes an error since it calls the variable i outside it's scope which is the for-loop.
### Question 10
Line 12 prints the size of the prices array that is being passed to it which is "3".
### Question 11
The function will return an array with all the discouted prices which would be "[50, 100, 150]".
### Question 12
**A.** student.name
**B.** student["Grad Year"];
**C.** student.greeting();
**D.** student["Favorite Teacher"].name;
**E.** student.courseLoad[0];
### Question 13
**A.** The output would be the string "32" since 2 maps to the string 2 and then JS performs concatenation
**B.** The output would be the number "1" since the string 3 maps to the number 3 and the JS performs number arithmetic.
**C.** The output would be the number "3" since null maps to the number 0 and JS performs number arithmetic.
**D.** The output would be the string "3null" since null maps to the string "null" and JS performs concatenation.
**E.** The output would be the number "4" since true maps to the number 1 and JS performs number arithmetic.
**F.** The output would be the number "0" since false maps to 0 and null maps to 0 and JS performs number arithmetic.
**G.** The output would be the string "3undefined" since undefined maps to the string "undefined" and JS performes concatenation.
**H.** The output would be the expression NaN which is used to represent arithmetic operations that have no clear answer since JS can't map string into number because there are no numbers in the expression and there is no negative concatenation meaning that JS can't reach a result with the given expression.
### Question 14
**A.** The output is true since the string "2" maps to the number 2 and 2 is greater than 1.
**B.** The output is false since the string "2" is greater than the first letter of the string "12".
**C.** The output is true since the string "2" maps to the number 2 which is equal to number 2.
**D.** The output is false since the string "2" is not the same type as the number 2.
**E.** The output is false since true maps to the number 1 which is not the same as the number 2.
**F.** The output is true since true and Booleand(2) have the same value true and are both of the same type.
### Question 15
The == operator compares two values and uses JS logic to see if the two values are equivalent. The === operator compares two expressions and checks that both their values and types are equivalent.
### Question 17
The result would be the array "[2, 4, 6]". Each time that the for loop is called the value returned by callback(array[ i ]) where i is the counter of the loop is added to newArr. This means that each time the loop goes through doSomething(num) executed where num = array[ i ] and the returned value is added to newArr.
### Question 18
The output will be the numbers "1432"