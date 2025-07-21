# cpp_wordsearch

## I made a word search that makes the puzzle and gives you the solution for it. 

### Task: 
#### Randomize the starting location of placing the word horizontally from left to right. Ensure that the spot chosen does not cause the word to go out of bounds.
#### Modify and add the algorithm to place the word horizontally from right to left.
#### Modify and add the algorithm to place  the word randomly vertically down and up.
#### Modify and add the algorithm to place the word in the 4 diagonal directions. (Hint: start at the corners to determine the proper range.)
#### Randomize the 8 directions to place the word.
#### Collect all of the placement algorithms of this board into a void function called placeWord(string s);
#### Use placeWord()  to place multiple words onto the board.
#### Note that words may run into each other. Write a function isSafe(row,col,word, dir) that determines if the [row][col] spot chosen "isSafe" for the word being placed in dir direction.
#### Use the isSafe() function to help generate valid [row][col] spot values that will safely place the word without inappropriately running into other words.
#### Note that the words are not crossing into one another through a common character. Modify the isSafe() function to allow the word to intersect with a placed word just as long as the point of intersection is a common character.
#### Test and ensure that all the words placed are satisfactory. Ensure no improper run-ins and out of bound errors.
#### Gather up a collection of 25+ words from a file and place them on the grid.
#### Note that there are spaces that are not populated with an alphabetic character. Replace all '-' characters with a random alphabetic character to complete the puzzle generator.
#### Output BOTH the puzzle (with AND without random characters) and the list of words you placed inside.



