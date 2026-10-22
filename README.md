# Student-marks-Management-System
Student marks profile

student_names = ["John", "Lungile", "Elvis", "Lerato", "kelvin"]
student_marks = [78, 55, 34, 29, 85]

#This is the class average
class_average = sum(student_marks) / len(student_marks)

#These are the iteration for student marks
print("\nSTUDENT MARKS")
print("---------------------------")
for i in range(len(student_names)):
    name = student_names[i]
    mark = student_marks[i]
    print(name, "-", mark)

highest_mark = max(student_marks)
lowest_mark = min(student_marks)

print("\nCLASS RESULTS")
print("------------------------")

print("Class Average:", class_average)
print("Highest Mark:", highest_mark)
print("Lowest Mark:", lowest_mark)

# These are the updated marks
print("\nUPDATED MARKS")
print("------------------------")
for i in range(len(student_names)):
    name = student_names[i]
    mark = student_marks[i]
    student_marks[2] = 75
    print(name, "-", mark)
