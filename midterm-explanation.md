# Explain the Midterms

### capitalizeSentences

1. Make a new empty string that will hold our result.
2. Loop through each index in our paragraph.
3. If the paragraph's character at the current index - 2 is equal to a period OR the index is 0...
   1. Append the uppercase version of the character at the current index from step 3 to our result string.
4. Otherwise... 
   1. Append the lowercase version of the character at the current index from step 3 to our result string.
5. After looping through all indices in our paragraph, return our result string.

### isValidPassword

1. If the password's length is < 12...
   1. Return false.
2. If the password includes a space...
   1. Return false.
3. Otherwise...
   1. Return true.

### makeHalfSquares

1. Make a new empty array to hold our result array
2. Loop through each index of our numbers.
3. Square the number at the current index, and then divide this number by 2.
4. Add this result to the result array
5. After looping through each index, return the result array.

### countAs

1. Make a new empty number to hold our A-count.
2. Loop through each index of our grades.
3. If the grade at the current index is greater than or equal to 90...
   1. Add 1 to our A-count.
4. After looping through each index, return our A-count.

### deleteMiddleLetter

1. Make a new empty string to hold our result.
2. Make a new number equal to the length our string parameter divided by 2, rounded down. This is our middle index.
3. Loop through each index in our string.
4. If the length of the string is odd AND the current index is not equal to our middle index from step 2...
   1. Append the string at our current index to our result.
5. Otherwise if the length of the string is even, AND the current index is not equal to our middle index OR middle index - 1...
   1. Append the string at our current index to our result.
6. After looping through all indices, return our result.

### lastIndexOfSpace
1. Loop through each index of our string, starting from the last index. 
2. If the string at our current index is a space...
   1. Return the current index
3. After looping through all indices, return -1.

### hyphenateName
1. Make a new empty string to hold our result.
2. Loop through each index of our name parameter.
3. If the current index is equal the last index of space in our name...
   1. Append a dash to our result string.
4. Otherwise...
   1. Append the character at the current index to our result string.
5. After looping through all indices, return our result string.