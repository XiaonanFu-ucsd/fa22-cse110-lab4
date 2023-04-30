1. Line 12 will print the variable `i` which equals `prices.length`, because `i` is declared with `var`; it is not block scoped in the for loop.
2. Line 13 will print the variable `discountedPrice` which equals the value in the last iteration, because `discountedPrice` is declared with `var`; it is not block scoped in the for loop.
3. Line 14 will print the variable `finalPrice` which is the rounded value of the `discountedPrice` in the last iteration. It is defined at the same scope as the print statement, but modified in the for loop. It is accessible in the print statement no matter if it is declared with `var`, `let`, or `const`.
4. This function will return a list of prices after the discount, and rounded to 2 decimal places. The variable `discounted` is definded with `var` under the scope of the function, so it is accessible in the for loop and the return statement.
5. Line 12 will cause an error because `i` is not defined outside of the for loop. It is declared with `let` and is block scoped in the for loop.
6. Line 13 will cause an error because `discountedPrice` is not defined outside of the for loop. It is declared with `let` and is block scoped in the for loop.
7. Line 14 will print the variable `finalPrice` which is the rounded value of the `discountedPrice` in the last iteration. It is defined at the same scope as the print statement, but modified in the for loop. It is accessible in the print statement no matter if it is declared with `var`, `let`, or `const`.
8. The preivous error will stop the function. If ignore the error, ideally the function will return a list of prices after the discount, and rounded to 2 decimal places. The variable `discounted` is definded with `let` under the scope of the function, so it is accessible in the for loop and the return statement.
9. Line 11 will cause an error because `i` is not defined outside of the for loop. It is declared with `let` and is block scoped in the for loop, hence is not accessible in the print statement.
10. Line 12 will print the length of the array `prices`, because it is defined with `const` and is at the same scope as the print statement. 
11. This function will return a list of price after the discount. The array `discounted` is defined with `const` and is at the same scope as the return statement. Although it is a constant variable, its content can be modified.


12a. `student.name`  
12b. `student["Grad Year"]`  
12c. `student.greeting()`   
12d. `student["Favorite Teacher"].name`  
12e. `student.courseLoad[0]`


13a. `'32'`, since `'3'` is a string, `2` is converted to a string and concatenated to `'3'`.  
13b. `1`, since `'3'` is a string, `'3'` is converted to a number and subtracted by `2`.  
13c. `3`, since `null` is converted to `0` and added to `3`.
13d. `'3null'`, since `null` is converted to a string and concatenated to `'3'`.
13e. `4`, since `true` is converted to `1` and added to `3`.  
13f. `0`, since `false` is converted to `0` and `null` is converted to `0` and added to `0`.  
13g. `'3undefined'`, since `undefined` is converted to a string and concatenated to `'3'`.  
13h. `NaN`, because subtraction converts the string `'3'` to a number, and `undefined` is converted to `NaN`.  


14a. true, since `'2'` is converted to a number and is greater than `1`.  
14b. false, since both of them are strings, and `'12'` is not greater than `'2'` in lexicographical order.  
14c. True, since `'2'` is converted to a number and is equal to `2`.  
14d. false, since `===` is a strict equality operator, and `'2'` is not equal to `2` in terms of type.  
14e. False, because `true` is converted to `1` and is not equal to `1`.  
14f. True, because `Boolean(2)` is `true`, they are strictly equal.  

15. `==` is a loose equality operator, and it will convert the operands to the same type before comparing them. `===` is a strict equality operator, hence it will not convert the operands to the same type before comparing them. 
17. This function will return the array `[2, 4, 6]`. The function copy the parameter array, and apply the function `doSomething` to each element in the copied array. The function `doSomething` will multiply the element by 2 and return the result. The function `modifyArray` will return the modified array. 
19. The above code will print `1 4 3 2` in the console. First the print statement in the function scope will run. The function also pushes two macro tasks to the task queue, and they will run at the specific time. 