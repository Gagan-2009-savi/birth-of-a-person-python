# birth-of-a-person-python
senior citizen checker using python-python basic  project 

# Birth of a Person - Senior Citizen Checker
# Author: Gagan | AIML - MSCE

name = input("Enter the person's name: ")
year = int(input("Enter the year of birth: "))
current_year = 2026
age = current_year - year

print("\nName:", name)
print("Age:", age)

if age >= 60:
    print(name, "is a senior citizen.")
else:
    print(name, "is not a senior citizen.")