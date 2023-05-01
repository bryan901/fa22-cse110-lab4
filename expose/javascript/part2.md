1. The number 3 is printed. This happens because we are looping through 3 items in the prices list, and we print the value of i after we are finished looping
2. The number 150 is printed. The var discountedPrice contains the discounted price of the last item in the prices list, which in this case is 300 * 0.5 = 150
3. The number 150 is printed. The var finalPrice contains the rounded discountedPrice value, which in this case is 150. After rounding 150, we still get the value of 150, which is the number that is printed
4. The list [50, 100, 150] is returned. Each item in the prices list was multiplied by 0.5 and returned in a new list
5. The code causes an error, because the i variable is being printed outside of the scope it was declared in
6. The code causes an error, because the discountedPrice variable is being printed outside of the scope it was declared in
7. The number 150 is printed. There is no error because we are accessing the finalPrice variable, which was declared in the same scope
8. The list [50, 100, 150] is returned. Each item in the prices list was multiplied by 0.5 and returned in a new list. There is no error because we are accessing the discounted variable, which was declared in the same scope
9. The code causes an error, because the i variable is being printed outside of the scope it was declared in
10. The number 3 is printed. The const variable contains the lenght of the price list, which in this case is 3 as there are 3 elements inside the list. There is no error because the lenght variable was declared in the same scope
11. The list [50, 100, 150] is returned. Each item in the prices list was multiplied by 0.5 and returned in a new list
12. A. student['name']
    B. student['Grad Year']
    C. student['greeting']()
    D. student['Favorite Teacher']['name']
    E. student['courseLoad'][0]
13. Arithmetic
    A. ‘3’ + 2 = '32', because the integer is mapped to its string representation '2' 
    B. ‘3’ - 2 = 1, because the integer 2 is subtracted from the integer representation of the string '3', which equals 1
    C. 3 + null = 3, because null represents the absence of any object value
    D. ‘3’ + null = '3null', because the null value is mapped to its string representation 'null', and then concatenated with '3' 
    E. true + 3 = 4, because the boolean true is mapped to its integer representation 1
    F. false + null = 0, because the boolean value false is mapped to its integer representation 0, and then the value of null which is nothing, is added to 0. This gives us 0
    G. '3' + undefined = '3undefined', because undefined is mapped to its string representation 'undefined' and concatenated with the string '3'
    H. '3' - undefined = NaN, because an undefined value cannot be subtracted from the integer representation of the string '3', which is 3. 
14. Comparison
    A. ‘2’ > 1 = true, because the string '2' is mapped to its integer representation 2, and 2>1
    B. ‘2’ < ‘12’ = false, because the alphabetical value of '12' is smaller than that of the string '2' 
    C. 2 == ‘2’ = true, because both of the values are the same even though they are of different variable types
    D. 2 === ‘2’ = false, because the type of 2 is an integer but the type of '2' is a string, so they are not equal 
    E. true == 2 = false, because the integer representation of true is 1, and 1 does not equal 2
    F. true === Boolean(2) = true, because the boolean of any non-zero value is true 
15. The == operator only compares the values of the two elements, while the === operator compares both the values and the types of the elements
16. js file
17. The result is the list [2, 4, 6]. The function doSomething acts as the callback function. doSomething multiples an element by 2, and we call doSomething on every element of the input array. We append this multiplied value to the new array that is returned. 
18. js file
19. 1 4 3 2 is printed. This happens because we call the setTimeout function on lines 3 and 4. Since we pass in a 1000 as the second parameter on line 3, the execution of line 3 is delayed the longest, which is why we get 1 4 3 2
