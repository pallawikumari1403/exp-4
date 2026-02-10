Aim:
Study of sets in python.

Theory:
Sets use {} brackets.
Sets are unordered [ print(thisset[1]) will give an error. ].
Sets do not allow duplicates.
Value of 1 and True are considered same for sets.
You can check if an element is there in set or not using: print("element" in thisset).
You can remove elements using: thisset.remove("element").
You can do set operation like Union, Intersection, Difference, Symmetric Difference. Union adds elements of both sets, intersection displays the common elements, difference displays the difference of the two sets, symmetric difference used to get the elements present in either of the two sets, but not common to both sets.
Frozen sets are like sets but elements cannot be added or removed from a frozenset.
remove() and discard() both delete elements but:
discard does nothing if the element is not there but remove shows an error.

Algorithm:
Set Operations
Operators used: |, &, -, ^
1)Start
2)Create set a and set b
3)Find union using a | b
4)Find intersection using a & b
5)Find difference using a - b
6)Find symmetric difference using a ^ b
7)Print all results
8)End

Unique Event Participants
Operators / functions used: set()
1)Start
2)Create a list with duplicate participant names
3)Convert list into a set using set()
4)Store unique names
5)Print the set
6)End

Common Subjects (Intersection)
Operators used: &
1)Start
2)Create three sets of subjects
3)Find common subjects using std1 & std2 & std3
4)Print the result
5)End

Cricket & Football Club Students
Operators used: &, ^
1)Start
2)Create set cricket
3)Create set football
4)Find students in both clubs using &
5)Find students in only one club using ^
6)Print results
7)End

Find Absent Students
Operators used: -
1)Start
2)Create set of all students
3)Create set of present students
4)Find absent students using all_students - present
5)Print absent students
6)nd

Remove Discontinued Course Code
Methods used: .discard()
1)Start
2)Create set of course codes
3)Remove discontinued course using .discard()
4)Print updated course list
5)End
Conclusion:
Hence sets were implemented in python and set operations were performed in python.
