1. 3, because the i variable was initialized with var which does not have block-level scope. Thus it prints the value of i after the loop finishes, which is 3.
2. 150, since the variable is function-level scope so it prints the discounted price of the last item, which is 150.
3. 150, because the variable is function-level scope and it stores the value of discounted price of the last item of the loop, which is 150.
4. [50, 100, 150], because discounted variable is an array variable with function-level scope, and it stores the discounted prices of all items in prices.
5. error, i is not defined since it is block-level scope defined inside the loop.
6. error, discountedprice is not defined since it is block-level scope defined inside the loop.
7. 150, because the block-level scope was defined outside of the loop, and finalPrice stores the rounded discounted price of the last element in the loop.
8. [50, 100, 150], because the discounted variable is block-level scope defined outside the loop, and it stores the final prices after the discounted applies.
9. error, i is not defined since it is block-level scope defined inside the loop.
10. 3, because the const block-level scope variable was defined outside of the loop, and stores the size of the array, which is 3.
11. [50, 100, 150], this variable is block-level scope nad initialized outside of the loop. This variable gets pushed the discounted prices of each item in the loop. 
12. <br>
    A. student.name <br>
    B. student['Grad Year'] <br>
    C. student.greeting() <br>
    D. student['Favorite Teacher'].name <br>
    E. student.courseLoad[0] <br>
13. <br>
    A. 32, the '+' operator converts the 2 into a string, concatenating the '3' + '2' to get '32'. <br>
    B. 1, the '-' operator converts the '3' into a number 3, subtracting the 3 and 2 to get 1. <br>
    C. 3, because 'null' is treated as '0' in numeric context, so 3 + 0 = 3. <br>
    D. 3null, because the '+' operator concatenates strings, so '3' + 'null' concatenates to be '3null'. <br>
    E. 4, because 'true' is treated as '1' in numeric context, so 1 + 3 = 4. <br>
    F. 0, because both 'false' and 'null' are treated as '0' in numeric contexts, so 0 + 0 = 0. <br>
    G. 3undefined, because '+' concatenates strings, so '3' + 'undefined' = '3undefined'. <br>
    H. NaN, because '-' tries to convert the elements into numbers, but 'undefined' cannot be converted into a number. <br>
14. <br>
    A. true, because '2' is turned into a number, and 2 > 1 is true. <br>
    B. false, because string comparison bases off of the Unicode values of individual characters. When comparing the first characters, '2' comes after '1' on Unicode ordering, so this comparison is false. <br>
    C. true, because '==' performs type coercion so '2' converts into a number and 2 == 2 is true. <br>
    D. false, because '===' doesn't perform type coercion and 2 and '2' are different types. <br>
    E. false, because when type coercion is performed, true turns into 1 and 1 == 2 is false. <br>
    F. true, because Boolean(2) means true and is type Boolean, while true is also type Boolean, thus true === Boolean(2) is true. <br>
15. '==' is an equality operator that performs type coercion before comparing two values. '===' is a strict equality operator that does not perform type coercion before comparison.
16. Look at part2-question16.js
17. [2, 4, 6], function modifyArray takes in array [1, 2, 3] and function doSomething(). The for loop iterates through the array and pushes the value returned by doSomething when the array value is inputted as the parameter. doSomething(1) returns 2, doSomething(2) returns 4, and doSomething(3) returns 6. Then the new array [2, 4, 6] is returned.
18. Look at part2-question18.js
19. the output is:<br>
    1 <br>
    4 <br>
    3 <br>
    2 <br>
