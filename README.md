Anagram-Solver
==============

Definition of an Anagram:
A word, phrase, or name formed by rearranging the letters of another

Created a that finds all the anagrams in a 5 million word dictionary in 7.242 seconds

- 	Implemented a hash table to achieve θ(1 + L) inserting/deletion
-  	Implemented counting sort to attain θ(n) sorting complexity

# How the algorithm works


1).	Read in the word.
2).	Sort the word in alphabetical to produce the key.
3).	Store the word in a Hash Table using a hash function.
4).	If collision occurs verify if current word is an anagram of the word in that array location.
5). If step 4 fails move up +1 to a new index until an anagram or a empty slot is found

Note: An empty slot indicates that sequence of letters has not been discovered 




