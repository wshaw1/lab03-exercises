Find All Duplicates
Write a function (or static method in the case of Java) that accepts a list of integers and returns a list of only those integers that appear more than once.

Solutions that find duplicates:
    Nested Loop:
        The nested loop solution uses an outer loop to iterate through every single element of an array. This loop contains another loop that compares the outer loops current element with all of the other elements in an array following the outer loops element.
        This is quite inefficient as needing to iterate multiple times per element brings this solution to O(n^2) time.
    Set:
        A solution based on sets would use the inherent feature of sets where they dont allow duplicates. When adding to a set in java, it will return a boolean depending on the success of the addition. This can be used to track when something is already in the list, allowing you to add it to a further list.
        This is very efficient as it only needs to read through the list once. It could be argued that this needs more memory to run due to needing a second set.
