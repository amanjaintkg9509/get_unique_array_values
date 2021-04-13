# Requirement:- Get unique values from an array where some values duplicate with and without builtin function.
* Pseudo code for get unique values array with builtin function:-
* 1. get all value in a variable.
* 2. create a empty array variable.
* 3. check all values using map function and check one by one.
* 4. check value in exist or not in new array using indexof function, if value already exist in this array so function return index otherwise -1.
* 5. if getting -1 response from function then push checked value in new array.
*
* * Pseudo code for get unique values array without builtin function:-
* 1. get original array in a variable and create a empty array variable for sotre purpose.
* 2. run for loop.
* 3. set a flag status in a variable with true boolean value.
* 4. check new array, if any value is exist already so check all stored value one by one with original array value one by one.
* 5. if value is matched then flag set false then after for loop completion check flag and if flag is true then insert a picked value
* in max length of new array.
* 6. if new array length is 0 then store picked value in max length of new array.
