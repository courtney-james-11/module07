# debug_log.md
# Author: Courtney James

## Bug 1
Error type: Key Error
File + line:  File "/home/courtneyjames/ism3232/module05_functions/week8_buggy.py", line 12, in get_total
What the error means: One of the dictionary keys is spelled wrong
What I told the duck: records is a dictonary that stores the id, name, and amount. The get total function the returns the total amount by adding each record in a loop.The is over limit function then returns true f the amount if greater than 1000. The formart summery functon returns the format based on total and count inputs. In line 21, total is defined to the get total function. In line 22, the format summer functon is called and printed based on total and the length of the records dictionary. In line 23, the is over limit function is called and printed.
What I tried: I entered a debug print statement in line 12 to find a spelling error.
How I fixed it: I changed 'amout' to 'amount' and saved the file.

## Bug 2
Error type: Type Error
File + line: File "/home/courtneyjames/ism3232/module05_functions/week8_buggy.py", line 17, in is_over_limit
What the error means: >' not supported between instances of 'int' and 'str'
How I fixed it: I changed '1000', which is a string to 1000, which is an interger. 

## After Fixing Both Bugs
Final output: 
Total: $5150.00 across 3 records
True
Did pytest pass? Yes

## AI Literacy Reflection
Did I use AI? No. I was able to identify each bug with the error outputs in the terminal.
If yes -- exact prompt I used: ___
What AI explained: ___
What I changed myself: ___
Can I explain every fixed line? Yes

## What I learned
I learned that it is important to go through every line of your code and list what it is doing if you are stuck trying to find a bug. I learned that you can use print statements to help debug as well. I also learned that the terminal gives helpful insight for where an error is and what type of error it is.