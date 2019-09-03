# Shannon-Coder
Coder segment of the Shannon coder-decoder.

#### Future Development Fields in Question

1: Evaluate number of independent hashIDs and number of independent symbols per symbol list/hash element.\
Use static arrays instead of dynamic arrays. Improve search algorythms due to static array by indexing.\
Is contiguous memory allocation (static array!) possible with 'such' extension?

2: Optimize search algorithms by using relative indexing.\
( Eg.: moveHashCursor(lastCursorPos, relativeIndex{...}) )

3: New data storage structure and algorithms based on alphabetical order, hash ID, symbol probability weigh.
	
  Tip#1:
  
            1st lvl -> Alphabetic groups according to 1st letter(and number)
		2nd lvl -> Hash tables according to hash IDs
		3rd lvl -> Symbols in alphabetic order in lists

4: Use const where possible (eg.: function parameter list)

5: Outsource the initialisation funtions from the insertNew[...]Between() functions to the calling function.
 
  Tip#1:
    
		-> allocate locally
		-> check for allocation exceptions locally
		-> initialise with function call
		-> insert with function call

6: Capability of processing numbers.

Note that each development field have to be launched and treated in a separate branch from the master branch.

[Adam] [03-09-2019]
