# CodingQuiz5
Answers to questions from 3/22:

Plus Minus:
    Time complexity: O(n). This functions time is linear as the time it takes to complete depends wholly on the size of the given array arr, since the main chunk of the code happens in a for loop that iterates through the array. All other commands in this code run in constant time, so they have no bearing on the larger linear time complexity.

    Space Complexity: The space complexity for this code is O(1). This is because the variables poscount, negcount and zerocount are the only variables that will be initialized during the runtime, there are no compounding factors such as nested structures, recursive calls or higher level data structures that are initialized that would increase the space complexity

Fibonacci Modified:
    Time Complexity: O(n(n^2)). This functions time complexity is exponential due to the inclusion of the BigInt method .multiply. This method has a time complexity of O(n^2), this combined with the fact that the multiply method is called recursively n times, where n is the size of the array, makes the time complexity O(n(n^2) or n^3.

    Space Complexity: O(1), as only three values are initialized, and then these values are recursively rewritten, the amount of space needed to run the program remains unchanged.
