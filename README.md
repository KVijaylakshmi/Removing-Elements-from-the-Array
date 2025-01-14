# Removing-Elements-from-the-Array
import array
arr = array.array('i', [1, 2, 3, 1, 5])

# using remove() method to remove first occurance of 1
arr.remove(1)
print(arr)

# pop() method - remove item at index 2
arr.pop(2)
print(arr)
