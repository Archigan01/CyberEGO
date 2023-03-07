# Challenge 2: Binary

Using the binary guide provided, translate the string of binary bits in the file into our base-10 counting system. Then, once you have the numbers, use the ASCII table provided to change the numbers into a phrase. That phrase is the flag for this challenge.

To turn binary into decimal, you have to think of each bit as a number. Starting from the right, the first 1 or 0 has a value of 1. If the bit is a 1, ass 1 to the total. If it is 0, add nothing. Do the same for the next bit. The next bit has a value of 2. The third from the right has a value of 4. Then 8, then 16, then 32, 64, 128, 256, etc. If the bit is a 1, add the value of that bit to the overall total. If it is 0, add nothing. So, if you have the binary byte 01101001, you start at the right and add together, like so: 1 + 0 + 0 + 8 + 0 + 32 + 64 + 0 to get a value of 105. This translates to the letter i.
