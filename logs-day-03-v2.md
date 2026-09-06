I learned about string slicing. String slicing is a way to take a specific part of a string instead of using the entire string.

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


Slicing From the Beginning
If I leave out the starting number, Python starts from the beginning of the string.

word = "Python"

print(word[:3])

Output:

Pyt

Slicing to the End
If I leave out the ending number, Python continues to the end of the string.

word = "Python"

print(word[2:])

Output:

thon

Using a Step
I can also use a third number to tell Python how many characters to skip.

word = "Python"

print(word[0:6:2])

Output:

Pto

The 2 means to take every second character.

What I Learned
The main thing I learned is that string slicing allows me to take out a portion of a string. The basic format is:

string[start:stop]

I also learned that Python starts counting at 0, and the stopping position is not included in the slice.

String slicing can be useful when I only need a certain part of a string instead of the whole thing.
