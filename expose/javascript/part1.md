1. values added:  20
2. final result:  20
3. values added:  20
4. The code returns a reference error result is not defined. This is because the console log is called outside of the scope of the let keyword because it is outside of the if statement block.
5. The code returns a type error assignment to const variable. This is because a const cannot be reassigned and line 7 is trying to reassign result.
6. The code will not reach line 13 because of the previous error but if it did it would have the same results as question 4 with the let keyword because they have the same scope.