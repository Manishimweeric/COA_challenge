responsive photo gallery, ArrayMap

the first challenge Gallery -used html and css -simple design of html and for a good design i used css displayed images in Grid and for responsiveness i used media query 2nd challenge
**ArrayMap ** How it Works
Initialization: I Create a Map to track cumulative sums.

Iteration: Loop through the array, updating the cumulative sum.
Check Conditions: If the sum equals the target or sum - target exists in the map, return true.
Update Map: Add the current sum to the map.
Completion: If no subarray is found, return false.

How to Run

Copy the ArrayMap function into your JavaScript file.
Define your array and target value.
Call ArrayMap(arr, target) and log the result.

3RD challenge String Transformation
How It Works
Initialization: -The function transformString takes an inputString as its parameter.
-The length of the inputString is stored in the length variable.
-A result variable is initialized with the inputString.

Divisibility Check: If the length of the string is divisible by both 3 and 5 , the function first reverses the string using split('').reverse().join(''), then replaces each character with its ASCII If the length is divisible by 3 but not 15, the function simply reverses the string using split('').reverse().join(''). If the length is divisible by 5 but not 15, the function replaces each character with its ASCII Return Result: The transformed string, stored in the result variable, is returned.