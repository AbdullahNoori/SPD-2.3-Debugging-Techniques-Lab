# Debug Log

**Explain how you used the the techniques covered (Trace Forward, Trace Backward, Divide & Conquer) to uncover the bugs in each exercise. Be specific!**

In your explanations, you may want to answer:

- What is the expected vs. actual output?
- If there is a stack trace, what useful information does it contain?
- Which technique did you use, on which line numbers?
- What assumptions did you have about each line of code, and which ones were proven to be wrong?

_Example: I noticed that the program should show pizza orders once a new order is made, and that it wasn't showing any. So, I used the trace forward technique starting on line 13. I discovered the bug on line 27 was caused by a typo of 'pzza' instead of 'pizza'._

_Then I noticed another bug ..._

## Exercise 1

[[The useful information given in the terminal is the TypeError. Whats useful is the line  numbers provided for the error. The technique I used is Traceback technique/approach. Doing so, allowed me to uncover more bugs. I noticed there is no body tag in home.html. I also uncovered that pizza_order_submit wsa retreiving the incorrect names from the input feild form.]] 

## Exercise 2

[[ After running the the program I discovered that the API key was being fetched from a non-existing .env file. In addition data is not being retrieved from the API which was due to the API incorrectly being called. The approach I used is the was trace forward technique and the divide and conquer technique for the API bug/error by  breaking down my code into seperate sections/parts. Lastly, an error for JSON data not finding the temp. For this I used the trace back technique and fixed the temp. I was able to identify that line 54 where temperature defined as temp.]]

## Exercise 3

[[ The error displays index is out of range on line 38 where the index variable is set for the left sub array rather than the right one. The code has inconsistency and is lots of mistakes. I used the divide and conquer technique and notice that both left and right halves of the subarray mixed in the main while loop. Furthermore, I also uncovered that the while loop is incorrect becuase when both pointers are equal to eachother the while loop should continue and not exit out of the loop.  To fix the conditional while loop being from < ; it has to be changed to < =  to continue the loop in the event.  ]]
