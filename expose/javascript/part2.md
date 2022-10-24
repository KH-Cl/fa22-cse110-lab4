1. Line 12 will print the value of the var i which is 3 (the length of prices).
2. Line 13 will print the value of the var discountedPrice which is 150 (the last value of prices at the discount rate). This is because discountedPrice is declared as a var in the for loop so it is still in scope outside of the for loop.
3. Line 14 will print the value of the var finalPrice which is 150 (the last value of prices at the discount rate rounded to a proper number). This is because finalPrice is decalared as a var outside of the for loop so it is still in scope.
4. The function will return an array of the prices with the discount applied. In this case, [50,100,150]. This is because the finalPrice is calculated for each and then pushed to the var array discounted which is the returned value.
5. Line 12 will error because i was declared with a let keyword so the scope is contained within the block and the log statement is outside the for statement.
6. Line 13 will error because discountedPrice was declared with a let keyword so the scope is contained within the block and the log statement is outside the for statement.
7. Line 14 will print the value of finalPrice (in this case 150) because it was declared with the keyword let within the scope(outside the for loop).
8. The function will return an array of the prices with the discount applied. In this case, [50,100,150]. This is because the finalPrice is calculated for each and then pushed to the array discounted which is the returned value.
9. Line 11 will error because i was declared with a let keyword so the scope is contained within the block and the log statement is outside the for statement.
10. Line 12 will pring the value of the const length which is 3 (the length of prices).
11. The function will return an array of the prices with the discount applied. In this case, [50,100,150]. This is because the discountedPrice is calculated for each and then pushed to the array discounted which is the returned value. Even though the array is a const, we can still push items to it because it doesn't act as reassignment.
12. A. student.name
    B. student['Grad Year']
    C. student.greeting()
    D. student['Favorite Teacher'].name
    E. student.courseLoad[0]
13. A. 32 because ints map to string rep with plus sign
    B. 1 because strings map to ints with minus sign
    C. 3 because null maps to zero with int
    D. 3null because null maps to string with string
    E. 4 because bool true maps to 1 with int
    F. 0 because bool false and null both map to 0
    G. 3undefined because undefined maps to string with plus sign
    H. NaN because undefined numeric conversion (caused by minus sign) is NaN
14. A. true because '2' maps to int and 2 > 1
    B. false because when comparing strings it will compare letter by letter and '2' < '1' is false
    C. true because '2' maps to int rep and 2 == 2
    D. false because === is the strict equality operator and checks without type conversion
    E. false because true maps to numerically to 1 which is not equal to 2
    F. true because Boolean(2) returns a bool true which is strictly equivalent to another bool true
15. == is the equality operator and allows for type conversion while checking equality allowing 2 == '2' to return true because '2' will numerically convert to 2. === is the strict equality operator and does not allow for type conversions while checking equality meaning 2 == '2' will return false because there are two different types being compared.
16. See part2-question16.js
17. The result will be [2,4,6]. Each element of the array ([1,2,3]) of modifyArray is used as a parameter for callback (which in this case is doSomething) and pushed to newArr which is the return value.
18. See part2-question18.js.
19. 1
    4
    3
    2