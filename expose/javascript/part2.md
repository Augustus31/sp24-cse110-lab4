1. 3. The variable i has function scope, so it still accessible after the for loop. The loop terminates when i is 3, and thus 3 is printed.
2. 150. The variable discountedPrice has function scope, so it still accessible after the for loop. The loop's last pass is when i is 2, and discountedPrice is therefore 300/2 = 150.
3. 150, for the same reasons described above. 
4. [50,100,150]. The array contains all of the values in the original array, multiplied by 0.5.
5. Error, since i was not declared within the scope of the print statement.
6. Error, same reason as above.
7. 150. The variable finalPrice has block scope, but the block includes this print statements. Thus, its value (which was last changed at the final loop-through of the for loop, in which it was set to 150) will be printed.
8. [50,100,150]. The scope of the variable (its block) includes the return statement, so the variable does exist when it is returned.
9. Error, since i was not declared within the scope of the print statement.
10. 3. The variable length is const, but isn't modified, so there is no error. The length of the list passed into the function is 3.
11. [50,100,150]. The array is declared as const, and thus cannot be reasigned; however, it can be mutated. Pushing new elements will not cause an error. So the function will return the same result as in Q4.
12. 1) student.name 2) student["Grad Year"] 3) student.greeting() 4) student["Favorite Teacher"].name 5) student.courseLoad[0]
13. 
a. '32'.    The number 2 is converted to a string and concatenated with the string '3'.
b. 1    Since - is not a concatenation operator, in this case '3' is converted to the number 3 and 2 is subtracted from it to get 1.
c. 3    3 is a nunmber, so null is converted to a number, becoming 0. 3 + 0 = 3.
d. '3null'    '3' is a string, so null is converted to a string, becoming 'null'. '3' is then concatenated to 'null', yielding '3null'.
e. 4    true is a boolean, which is equivalent to the number 1. Thus, the operation becomes 1 + 3 = 4.
f. 0    false is a boolean, which is equivalent to the number 0. null can also be converted to a number, also 0. 0 + 0 = 0.
g. '3undefined'    undefined is converted into a string because '3' is being concatenated to it, therefore yielding '3undefined'.
h. NaN    The - operator indicates a numeric operation. However, numeric operations with undefined values (NaN) yield NaN.

14. 
a. true    The values are of different types, and thus both are converted to numbers. 2 > 1, so true.
b. false    The values are both strings, which results in a lexicographical comparison, in which '2' > '12'.
c. true    The values are of different types, and thus both are converted to numbers. 2 == 2 is true.
d. false    The values are of different types, so the === operator automatically returns false. 
e. false    The values are of different types, and thus both are converted to numbers. 1 == 2 is false.
f. true    The value on the right evaluates to true prior to comparison. Thus, the comparison is true === true, which is true because both operands are equal and of the same type.

15. == checks for equality after type conversion, while === checks for equality before type conversion.

16. see part2-question16.js
17. [2,4,6]    The function modifyArray takes in the array [1,2,3], creates a new empty array, and runs a loop which iterates over every element of the passed-in array, applies the function doSomething() to it, and then adds it to the new array. doSomething, in this case, multiplies by 2, so modifyArray will return an array with all elements from the original array multiplied by 2. This means passing in [1,2,3] will yield [2,4,6].
18. see part2-question18.js
19. 1,4,3,2 (on separate lines, in that order)
