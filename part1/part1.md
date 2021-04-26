## Part 1a
1) values added: 20
2) final result: 20

3) values added: 20
4) This line 13 will return an error as result is not declared in the scope of the console log statement. let declares in block level scope and the console log statement is outside of the scope of result.

5) This line 9 will return an error as we are trying to assign a value to a const variable which is not allowed.
6) This line 13 will return an error as result is not declared in the scope of the console log statement. const declares in block level scope and the console log statement is outside of the scope of result.

## Part 1b

1) Line 12 will print to the console: 3. Since i is declared as a var, it has usable scope for the console statement. Moreover, the for loop declaration implies that i will increment as long as i is strictly less than the length of prices, which in this case is 3. So on the final iteration of the loop, i updates to value of 2 and at the end of the loop we have to increment to 3 and then the loop condition is false and we move on to line 12.
2) Line 13 will print: 150. this will happen because discounted price will reassign itself to 300 * 1- 0.5 in the last iteration of the loop, which yields 150.
3) Line 14 will print: 150. This happens becuase the final iteration of the loop stores 150 into discountedPrice. As 150 is a whole number, the rounding at the hundredth's place will have no effect on the whole number.
4) This function will return an array with the contents: [50,100,150]. This is because the for loop will push each price in the input array multiplied by the discounted rate and rounded to the nearest cent.
5) Line 12 will cause an error as it now referencing a variable (i) that is now out of scope.
6) Line 13 will cause an erroras it now referencing a variable (discountedPrice) that is now out of scope.
7) Line 14 will print: 150 . This works as finalPrice is the declared in the same block as the console statement. Moreover it is 150 as on the final iteration of the loop it stores a 50% discount of 300.
8) This function will return an array with the contents: [50,100,150]. This is because the for loop will push each price in the input array multiplied by the discounted rate and rounded to the nearest cent. The let keyword use will not cause any change to the contents of the output array
9) Line 11 will throw an error as we are trying to access variable (i) which is out of scope at line 11.
10) Line 12 will print: 3. This is because the length of the input array is 3 and this remains constant and untampered through the running of the program.
11) This function will return an array with the contents: [50,100,150]. This is because the for loop will push each price in the input array multiplied by the discounted rate. The const keyword is used on variables are remain constant during their scope and are not attempted to be reassigned.
12) 
    a)student.name;
    b)student["Grad Year"];
    c)student.greeting();
    d)student["Favorite Teacher"].name;
    e)student.courseLoad[0];
13) 
    a)'32', We are adding a number and a string, JS will automatically concatentate the number to the string.
    b)2, the subtraction operator converts the string into numerical values automatically
    c)3, null is treated as zero valued
    d)'3null', here null is not converted to its numerical representation as we simpy contantenating strings
    e)4, true is converted to its numerical representation of 1
    f)0, false and null are converted to their numerical representations due to the addtion operator, returns 0 + 0 => 0
    g)'3undefined', 3 is a string and is concatentated to the value undefined
    h)NaN, the subtraction operator converts '3' to its numerical representation and undefined to NaN, the subtraction will yield NaN (not a number)
14) 
    a)true, the string 2 is converted to its numerical value and 2 > 1 is true
    b)false, there is unicode comparision between the string 2 and 12, 1 comes before 2 so '2' > '12'
    c)true, the == operator converts all the comparsion pieces into numerical representations
    d)false, the === operator checks equality withyout
    e)false, numerical value of true is 1, 1 is not equal to 2
    f)true, Boolean type cast of nonzero number is true, true === true, no type change involved.
    
15)The main difference between == & === is that === is a strict equality operator. This means that there is not type conversion occurring with ===. The == is type convert the arguments to their numericanl representations.  

17)The result will be an array with the contents [2,4,6]. What happens is that we have inputted an array, and a function as our function arguments. we declare a const array that cannot be reassigned. Then we are simpy iterating through the contents of our input array and passing them to our input argument function which simply multiplies the contents of the input array by 2. This is being pushed onto our constant array, which is allowed as we are not redeclaring the array.
19)Output:
1
4
3
2