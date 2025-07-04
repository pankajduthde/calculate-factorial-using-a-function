#  Create a Dictionary of Student Marks
student_marks = {
    "Alice": 85,
    "Bob": 78,
    "Charlie": 92,
    "Diana": 88,
    "Ethan": 76
}


name = input("Enter the student's name: ")

print(f"student mark")

if name in student_marks:
    print(f"{name}'s marks: {student_marks[name]}")
else:
    
    print(f"Student named '{name}' student not found.")


#  Demonstrate List Slicing 

numbers = list(range(1, 11))


first_five = numbers[:5]


reversed_first_five = first_five[::-1]


print("Original list:", numbers)
print("First five elements:", first_five)
print("Reversed first five elements:", reversed_first_five)


