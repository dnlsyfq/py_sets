```
//can't be indexed.
// Duplicate elements will automatically get removed
num_set = {1, 2, 3, 4, 5}

print(3 in num_set)

// use the add() function to add new items to the set, and remove()
nums = {1, 2, 1, 3, 1, 4, 5, 6}
print(nums)
nums.add(-7)
nums.remove(3)

//The union operator | combines two sets to form a new one containing items in either. 
//The intersection operator & gets items only in both. 
//The difference operator - gets items in the first set but not in the second. 
//The symmetric difference operator ^ gets items in either set, but not both. 

first = {1, 2, 3, 4, 5, 6}
second = {4, 5, 6, 7, 8, 9}

print(first | second) // {1, 2, 3, 4, 5, 6, 7, 8, 9}
print(first & second) // {4, 5, 6}
print(first - second) // {1, 2, 3}
print(second - first) // {8, 9, 7}
print(first ^ second) // {1, 2, 3, 7, 8, 9}








```
