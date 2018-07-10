# check-prime
How would you verify a prime number?

 A prime number is only divisible by itself and 1. Run a while loop and increase by 1.
 
 How can this be made better?
 
The divisor can be increased 1 at a time. After 3 it can increase by 2. If a number is divisible by any even number, it will be divisible by 2.


Step 1: Any number will not be divisible by a number bigger than half of it. For example, 13 will never be divisible by 7, 8, 9 .. it could be as big as half of it for even number. 16 will be divisible by 8 but will never be by 9, 10, 11, 12...

 A number will never be divisible by a number bigger than half of its values. You don't have to loop 50%.
 
Step 2: Now, if a number is not divisible by 3. (if it is divisible by 3, then it wouldn't be a prime number). It would be divisible any number bigger than the 1/3 of its value. 35 is not divisible by 3. It will be never divisible by any number bigger than 35/3 will never be divisible by 12, 13, 14 ... If you take an even number like 36 it will never be divisible by 13, 14, 15

A number could be divisible by numbers 1/3 of its value.

Step 3: Take the number 127. 127 is not divisible by 2 hence you should check up to 63.5. Secondly, 127 is not divisible by 3. So, you will check up to 127/3 approximately 42. It is not divisible by 5, the divisor should be less than 127/5 approximately 25 not by 7. 

 
 The divisor would be less than Math.sqrt (n)

