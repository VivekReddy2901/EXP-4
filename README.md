EXP 4 : Study of Sets in python

Theory :

In Python, a set is an unordered collection of unique elements. Sets are written using curly braces {} and do not allow duplicate values. Sets are mutable, meaning elements can be added or removed after creation, but they do not support indexing because they are unordered.

Creation and Printing of a Set
A set can be created by placing elements inside curly braces. When a set is printed, the elements may appear in any order because sets are unordered.

Indexing in Sets
Sets do not support indexing or slicing. Attempting to access an element using an index results in a TypeError, because sets do not maintain any fixed order.

Duplicate Elements in a Set
A set automatically removes duplicate elements. If the same value is added multiple times, it will appear only once in the set.

Mixed Data Types in a Set
A set can contain elements of different data types such as strings, integers, and boolean values. However, values like True and 1 are treated as the same because they have the same value internally.

Membership Test in a Set
The in keyword is used to check whether an element exists in a set. It returns True if the element is present, otherwise False.

Adding Elements to a Set
The add() method is used to insert a new element into a set. Since sets do not allow duplicates, adding an existing element has no effect.

Removing Elements from a Set
Elements can be removed from a set using methods like remove() or discard().

remove() raises an error if the element does not exist.

discard() does not raise an error if the element is absent.

Set Operations
Python supports various mathematical set operations:

Union (|): Combines all elements from both sets.

Intersection (&): Returns common elements.

Difference (-): Returns elements present in one set but not in another.

Symmetric Difference (^): Returns elements present in either set but not in both.

These operations are useful for comparing groups of data.

Frozenset
A frozenset is an immutable version of a set. Once created, elements cannot be added or removed. Frozensets are useful when a fixed collection of unique elements is required.

Removing Duplicate Values Using Set
Converting a list or collection into a set automatically removes duplicate values, leaving only unique elements.

Finding Common Subjects Using Sets
Intersection operation can be applied on multiple sets to find elements common to all sets. This is useful in scenarios like finding common subjects or interests.

Students in Cricket and Football Clubs
Create a set cricket containing names of cricket players.

Create a set football containing names of football players.

Use intersection (cricket & football) to find common students.

Use symmetric difference (cricket ^ football) to find students in only one club.

Display the results.

Finding Absent Students
Create a set all_students containing names of all students.

Create a set present_students containing names of present students.

Subtract present_students from all_students using (-) operator.

Store the result in absent_students.

Print the absent students.

Program: Removing an Element Using discard()
Create a set course containing course codes.

Use discard() method to remove a specific course.

Display the updated set.

Conclusion :

In this experiment, the concept of sets in Python was studied in detail. We learned how to create sets and understood that sets store unique elements and do not allow duplicate values. It was observed that sets are unordered, hence they do not support indexing.

Various set operations such as union, intersection, difference, and symmetric difference were performed and their applications were understood in solving real-world problems like finding common students, absent students, and shared subjects. The use of methods like add(), remove(), and discard() was also studied.

The experiment also introduced frozenset, which is an immutable version of a set. Overall, this experiment helped in understanding how sets can be efficiently used for data comparison, elimination of duplicates, and logical operations in Python programming.
