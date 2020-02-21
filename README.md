# Shannon-Coder
Coder segment of the Shannon coder-decoder.

#### Future Development Fields in Question

1: Evaluate number of independent hashIDs and number of independent symbols per symbol list.\
Use static arrays instead of dynamic arrays. Improve search algorythms due to static array by indexing.\
Is contiguous memory allocation (static array) possible with such extension?

2: Optimize search algorithms by using relative indexing.\
( Eg.: moveHashCursor(actualCursorPos, relativeIndex{...}) )

3: New data storage structure and algorithms based on alphabetical order, hash ID, symbol probability weigh.
	
  Tip#1:
  
            1st layer -> Alphabetic domains according to first character (A-Z,0-9)
		2nd layer -> Hash tables according to hash IDs
		3rd layer -> Symbols in alphabetical order in lists

4: Capability of processing numbers.

5: Randomize pivot and modify algorythm (if necessary) in function 'partition'.

6: Indicate error with negative return value in function 'generateShannonCode'.

7: Outsource program components into source files and headers to improve code maintenance.

8: Implement text converter function ('convertText').

Note that each development field have to be launched and treated in a separate branch.

[Adam] [21-02-2020]
