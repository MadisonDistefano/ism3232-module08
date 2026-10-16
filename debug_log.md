 debug_log.md
# Author: Madison Distefano

## Bug 1
Error type: _typo in the dictionary key 'amout' instead of 'amount'

File + line: week8_buggy.py
What the error means: The dictionary key was spelled wrong therefore Python could not find the 'amount' when the function tried to access it. This caused an error.

What I told the duck: I explained that the program was trying to get the amount from each record, but the first recod had the key spelled differently

What I tried:I retried and compared the key with the one I used _in _the get_total()function 
How I fixed it: _I changed the 'amout' to 'amount' so the dictionary key matched the function__
 
## Bug 2
Error type:  Caused by comparing an interger to a string___
File + line: _week8_buggy.py__
What the error means: The value '1000' had quotation marks, which made it a string instead of a number.___
How I fixed it: I removed the quotation marks around 1000, changing '1000' to 1000___

## After Fixing Both Bugs
Final output: _Total: $5150.00 across 3 records
True__
Did pytest pass? Yes / No
yes
## AI Literacy Reflection
Did I use AI? Yes / No
yes
If yes -- exact prompt I used:_
What AI explained: __I used it to help me transfer the files that I have to make a new one titled Module8 instead of module 5__
What I changed myself: ___
Can I explain every fixed line? Yes / No
yes
## What I learned
[2-3 sentences]
I learned how to pay attention to every small detail because even something as a mispelling could cause an error. In addition I learned how important quotations and how they can change the meaning of something.
