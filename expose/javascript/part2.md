## Part 2
1. The number '3' will be printed. This is because the variable *i* is of the type var, which means its scope is within the entire function discountPrices. Additionally, the variable *i* is incremented until its value is greater than or equal to the length of the array prices. Since the length of prices is 3, the for loop will finish once the value of *i* is 3.
2. The number '150' will be printed.  This is because the variable *discountedPrice* is of the type var, which means its scope is within the entire function discountPrices. Additionally, the variable *discountedPrice* is currently set to the discounted price of the last element in the *prices* array; that price is 300, and with a discount of 50%, the value will be 150.
3. The number '150' will be printed.  This is because the variable *finalPrice* is of the type var, which means its scope is within the entire function discountPrices. Its value will be the same as *discountedPrice* since we are multiplying and dividing by 100; the rounding function will not have an effect since we are dealing with whole numbers.
4. This function will return an array with the values of [50, 100, 150]. There are no logic errors in the function, so the *discounted* array will contain the correct discounted prices. 
5. Error - The variable *i* is declared with let, which means it has block scope. Line 12 is outside the for loop so it is not properly defined.
6. Error - Same explanation as Question 5.
7. 150 - Although this variable is declared with let, it's scope is the entire function. Thus, it's value will be the discounted price of the final element in the array.
8. This function will return an array with the values of [50, 100, 150]. Same reasoning as Question 4, and since the variable has scope for the entire function, there will be not be an error.
9. Error - Same explanation as Question 5.
10. 3 - There are three elements in the array so the length is 3. The const variable's value is not changed so there is no error.
11. This function will return an array with the values of [50, 100, 150]. There are no logic errors in the function, so the *discounted* array will contain the correct discounted prices. There is no rounding.
12. Data Types
    1.  student.name
    2.  student['Grad Year']
    3.  student.greeting()
    4.  student['Favorite Teacher'].name
    5.  student.courseLoad[0]
13. Arithmetic
    1.  '32' - the 2 will be converted into a string representation and concatenated to '3'
    2.  1 - The '3' is converted to a number, and 3 - 2 = 1
    3.  3 - null is converted to a 0
    4.  '3null' - null gets converted into the string 'null'
    5.  4 - true is converted to the number 1, and 1 + 3 = 4
    6.  0 - both false and null are considered the number 0, and 0 + 0 = 0
    7.  '3undefined' - the undefined is converted to a string and concatenated to '3'
    8.  NaN - 
14. Comparison
    1.  true - '2' is converted to a number, and 2 is greater than 1
    2.  false - the ASCII value of '2' is greater than the ASCII value of '1'
    3.  true - '2' is converted to a number
    4.  false - they are different data types
    5.  false - true is converted to the number 1
    6.  true - Boolean(2) evaluates to true, and true === true
15. '==' checks for equality regardless of data type, while '===' checks for data type and value equality.
