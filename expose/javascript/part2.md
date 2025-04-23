1. Console print "3" because "var i" is visible within the function and after i++, i = 3 >= prices.length and exist the for-loop.
2. Console print "150", discountedPrice is visible outside the for-loop, and it preserve the value in the last iteration.   
3. Console print "150", finalPrice is the value of the last iteration. 
4. The funcction return [50, 100, 150]: The function iterate through all value in the "prices" array and apply a discount on it, and save it into a list. 
5. Error, because "i" is  visible only in the for-loop block.
6. Error, because "discoutedPrice" is visible only in the for-loop block
7. Console print "150", because finalPrice is delcared outside the for-loop block and is the same scope of line 14. 
8. [50, 100, 150], there is no error because every variables is delcared in let and therefore value can reassign. 
9. Error, "i" is not visible. 
10. Console print "3", variable "length" is the same scope of line 12.
11. [50, 100, 150], because array is mutable, and  variable "discounted" is update through push() function instead of reassignment. Hence it does not violate the rule of const variable. 
12. 
    - A) student.name
    - B) student["Grad Year]
    - C) student.greeting()
    - D) student["Favorite Teacher"].name
    - E) student.courseLoad[0]
13. - A)'3' + 2 = "32",  '+' operation can be aplied to string. 
    - B) '3' - 2 = 1, '-' cannot apply to string, so convert '3' to int.
    - C) 3 + null = 3, null is treat as 0 in int.
    - D) '3' + null = 3null, "+" with string will turn "null" as it is string. 
    - E) true + 3 = 4, true is treated as 1
    - F) false + null = 0, false and null is treated as int which is 0.
    - G) '3' + undefined = "3undefined", undefined is treated as string and concat with "3".
    - H) '3' - undefined = Nan, because '-' only apply to numerals and undefined is Nan. 
14. - '2' > 1, True '2' convert to 2
    - '2' < '12', False string comparison '2' > '1' in ascii
    -  2 == '2' True, convert value to 2
    -  2 === '2' False, type not equal
    -  true == 2, False, true becomes 1.  
    -  true == Boolean(2), True, Boolean(2) is true.
15. Strict equality === needs both side have the same type, and equality == allows different type to be compared through value convertion.
16. in part2-question16.js
17. Result : [2,4,6]
    
    First, modifyArray would iterate through the array, and push the return value of the callback function.

    Second, passing doSomething into callback parameter, now the callback function return the double of the original array value and push it to the newArr. 
18. in .js
19. Result: 1

    3

    4
    
    2