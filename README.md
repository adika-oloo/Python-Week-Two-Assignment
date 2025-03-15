# Python-Week-Two-Assignment
#Description
#Create an empty list called my_list.
#Append the following elements to my_list: 10, 20, 30, 40.
#Insert the value 15 at the second position in the list.
#Extend my_list with another list: [50, 60, 70].
#Remove the last element from my_list.
#Sort my_list in ascending order.
#Find and print the index of the value 30 in my_list.

# Create empty list
my_list = []

# Append elements
my_list.append(10)
my_list.append(20)
my_list.append(30)
my_list.append(40)

# Insert 15 at second position (index 1)
my_list.insert(1, 15)

# Extend with another list
my_list.extend([50, 60, 70])

# Remove last element
my_list.pop()

# Sort in ascending order
my_list.sort()

# Find and print index of 30
print("Index of 30:", my_list.index(30))

# Optional: Print final list to verify
print("Final list:", my_list)
#Output
Index of 30: 3
Final list: [10, 15, 20, 30, 40, 50, 60]


