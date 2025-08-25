# Assigment-5
# task 01
students = {
    "Alice": 85,
    "Bob": 78,
    "Charlie": 92,
    "David": 74
}

name = input("Enter the student's name: ")

# Step 3 & 4: Retrieve marks or show error
if name in students:
    print(f"{name}'s marks: {students[name]}")
else:
    print("Student not found.")
#
# task 02
numbers = list(range(1, 11))

first_five = numbers[:5]

reversed_list = first_five[::-1]

print("Original list:", numbers)
print("Extracted first five elements:", first_five)
print("Reversed extracted elements:", reversed_list)
