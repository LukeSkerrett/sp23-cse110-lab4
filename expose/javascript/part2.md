1. The value of the prices.length variable will be printed.
2. The final discounted, unrounded price will be printed. 
3. The final discounted, rounded price will be printed.
4. Return a list of all discounted prices for each index -> [50, 100, 150]
5. Will return an error, i is not defined for that scope.
6. Will return an error, discountedPrice is not defined for that scope.
7. Will return the final rounded, discounted price.
8. Return a list of all discounted prices for each index -> [50, 100, 150]
9. Will return an error, i is not defined for that scope.
10. Will print the length of the prices list.
11. Return a list of all discounted prices for each index -> [50, 100, 150]
12. A student.name
    B student["Grad Year"]
    C student.greeting()
    D student["Favorite Teacher"].name
    E student.courseLoad[0]
13. A '32'. since integers are mapped to there exact string representation.
    B 1. '3' is evaluated to an integer when a subtraction sign is used.
    C 3. we are essentially adding nothing to the 3
    D '3null'. we are concatenating the string '3' with 'null'.
    E 4. When adding to an integer, true is evaluated to 1, its integer rep.
    F 0. Using the + operator evaluates false to 0, and null to 0.
    G '3undefined'. '3' and 'undefined' are contatenated.
    H 'NaN'. Undefined has no integer representation, therefore js does not know what to do.
14. A True. '2' will be evaluated to its integer rep. also, 2 > 1.
    B False. Both '2' and '12' will be evaluated to their int reps. Also, 2 < 12
    C True. '2' will be evaluated to its integer rep. Also, 2==2.
    D False. The === operator will always consider objects of different types different
    E False. True will be evaluated to 1. Also, 1 != 2.
    F True. Boolean( > 0 ) will always evaluate to true. They are also both of type boolean and both true. So the strictly operator will be sufficient.
15. "==" will evaluate to true while using representation and conversion when        available. "===" will be stricter, and only consider objects of equal value equal if they are also of the same type.
16. Refer to "part2-question16.js" file
17. The function above will result in a modified array of [2,4,6]. First, a new array to be returned is initialized. Then, the current of index of the passed in array is passed into the callback function (doSomething()), which doubles the current member of the array. The new, doubled array is returned.
18. Refer to "part2-question18.js"
19. 1\n4\n3\n2\n. The first integers printed will 1 and 4, which are not used from a setTimeout function. The next two integers, 3 and 2, are used in a setTimeut function in which 2 is delayed longer than 3.