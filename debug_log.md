# debug_log.md
# Author: Cam Lopez

## Bug 1
Error type: KeyError: 'amount'
File + line: week8_buggy.py, line 12
What the error means: Python could not find the key name "amount".
What I told the duck: The program tries to add the amounts together, but one of the records is mispelled.
What I tried: I checked the records list to find which key was incorrect.
How I fixed it: I corrected the mispelled key to "amount".

## Bug 2
Error type: TypeError
File + line: week8_buggy.py, line 16
What the error means: Python could not compare an integer to a string using ">".
How I fixed it: I removed the quotations around 1000 so python could recognize it as an integer.

## After Fixing Both Bugs
Final output: Total: $5170.00 across 3 records
True
Did pytest pass? Yes

## AI Literacy Reflection
Did I use AI? Yes 
If yes -- exact prompt I used: I asked "Why can't Python compare an integer vs a string?".
What AI explained: "Python cannot directly compare an integer to a string using > or < because they are two different data types, integer: a whole number used for mathmatical operations, string: text enclosed in quotation marks.
What I changed myself: From this explanation I dediced to change the "1000" which was a string, to 1000 an integer, so the python could compare the two.
Can I explain every fixed line? Yes

## What I learned  
I learned that you have to keep a close eye on spelling because one small mistake could cause a lot of trouble. Another thing is to make sure every aspect of the code makes sense, as said before, integers cannot be compared to strings, so being able to know the difference is very important. 