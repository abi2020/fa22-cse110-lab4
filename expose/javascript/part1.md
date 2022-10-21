## Part 1
1. values added:  20
2. final result:  20
3. values added:  20
4. Error - The *result* variable is declared within the 'if' statement, which means its scope is only within that block since it is a var type variable. The print statement on line 13 is outside that 'if' statement so it does not have access to the *result* variable. 
5. Error - The *result* variable is declared with const, which means its value can not be changed. Since we are trying to give *result* a new value in line 9, an error is thrown.
6. Error - The *result* variable is declared within the 'if' statement, which means its scope is only within that block since it is a const type variable. The print statement on line 13 is outside that 'if' statement so it does not have access to the *result* variable. 
