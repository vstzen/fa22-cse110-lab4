## 1
The code will print out 3, because this ends up as the length of prices. There is no error because i was declared with "var", so it has function scope.

## 2
The code will print 150, because discountedPrice ends up storing the discounted price of the last item in the prices array when the loop terminates. There is no error because discountedPrice was declared with "var", so it has function scope.

## 3
The code will print out 150, because finalPrice ends up storing the rounded discount price of the last item in the prices array when the loop terminates. There is no error because finalPrice was declared with "var", so it has function scope.

## 4
This function will return a list containing [50, 100, 150], the discounted prices of all the prices in the input prices variable. This is because the function loops through each value in the provided array, applies the discount, and appends it to the output array.

## 5
Line 12 will throw an error because the i variable was declared with "let" inside the loop block, so it can only be accessed inside the loop block.

## 6
Line 13 will throw an error because the discountedPrice variable was declared with "let" inside the loop block, so it can only be accessed inside the loop block.

## 7
Line 14 will print out 150 because finalPrice ends up storing the rounded discount price of the last item in the prices array when the loop terminates. There is no error because finalPrice was declared with "let" in the function block, so it has function scope.

## 8
This function will return a list containing [50, 100, 150], the discounted prices of all the prices in the input prices variable. This is because the function loops through each value in the provided array, applies the discount, and appends it to the output array.

## 9
Line 11 will throw an error because the i variable was declared with "let" inside the loop block, so it can only be accessed inside the loop block.

## 10
Line 12 will print 3 because the length constant is set to the length of the prices input array.

## 11
This function will return a list [50, 100, 150], containing the discounted prices of all the prices in the input prices variable. This is because the function loops through each value in the provided array, applies the discount, and appends it to the output array.

## 12
### A
student.name;
### B
student["Grad Year"];
### C
student.greeting();
### D
student["Favorite Teacher"].name;
### E
student.courseLoad[0];

## 13
### A
32, because integer 2 is being mapped to exact string
### B
1, because using normal integer operation
### C
3, because using normal integer operation and using 0 for null
### D
3null, because null is being mapped to exact string
### E
4, because true is being converted to integer value "1" for regular integer addition
### F
0, because false is being converted to integer value "0" for regular integer addition (where 0 is used for null).
### G
3undefined, because undefined is being mapped to exact string
### H
NaN, because attemped to do integer subtraction, but undefined value caused Nan output.

## 14
### A
True, the 2 string is being converted to an integer for comparision
### B
True, using string comparision, so comparing '2' to '1' char to determine inequality.
### C
True, string 2 is being casted to integer for comparision with double equals
### D
False, triple equals does not convert data types.
### E
False, true is being converted to integer value 1
### F
True, the Boolean() constructor creates a True boolean object if the input parameter does not equal 0.

## 15
Triple equals does not perform type conversions, while double equals does.

## 19
1
4
3
2
