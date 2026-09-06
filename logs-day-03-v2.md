What Is String Slicing and How Does It Work?
While learning Python through freeCodeCamp, I learned about string slicing. String slicing is a way to take a specific part of a string instead of using the entire string.

Python lets me select certain characters from a string by using square brackets [] and specifying a starting and ending position.

For example:

word = "Python"

print(word[0:3])

The outcome would be: Pyt


The 0 tells Python where to start, and the 3 tells Python where to stop. The character at position 3 is not included.

Python starts counting characters at 0, not 1.

For example:

P  y  t  h  o  n
0  1  2  3  4  5

So:

word[0:3]

gives me:

Pyt

