# SORT-using-WHILE-loop
# python program to sort using while loop.
arr = input("Enter a list of numbers or strings: ").split()
arr = list(map(int, arr))

sorted_arr = []

while arr:
    minimum = min(arr)  
    sorted_arr.append(minimum)  
    arr.remove(minimum)
print("Sorted list (ascending):", sorted_arr)

# output:
Enter a list of numbers or strings: 23 1 3334 12 656 343 86546 3245 4543 2 112 56 8
Sorted list (ascending): [1, 2, 8, 12, 23, 56, 112, 343, 656, 3245, 3334, 4543, 86546]
