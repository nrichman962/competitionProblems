A book cipher uses numbers to reference words in a book. You will write a program to read in a "book" and using character values as keys, write out a message.

# Input

The program will read the "book" as a space separated list of words. The same book will be used for each case.

The next input will be the number of cases.

Each subsequent line will be a string of characters. Each character's CP1026 value will then be used as an index. The index will be used to look up the coresponding word in the "book". The "book" is 0 based indexed and values above the length of the book wrap around (i.e. 255 in a "book" of length 120 would refer to the item at index 15).

# Output

The output for each case will be the decoded message with each word separated by a space.
