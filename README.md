first 
print("Welcome to the Quiz Game!")
print("-------------------------")

score = 0

# Question 1
print("Q1: What is the capital of Pakistan?")
print("a) Lahore")
print("b) Karachi")
print("c) Islamabad")

answer = input("Your answer: ")

if answer.lower() == "c":
    print("Correct!\n")
    score += 1
else:
    print("Wrong! The correct answer is Islamabad.\n")

# Question 2
print("Q2: Which language is used for Python files?")
print("a) .java")
print("b) .py")
print("c) .html")

answer = input("Your answer: ")

if answer.lower() == "b":
    print("Correct!\n")
    score += 1
else:
    print("Wrong! The correct answer is .py\n")

# Question 3
print("Q3: What does CPU stand for?")
print("a) Central Processing Unit")
print("b) Computer Power Unit")
print("c) Control Program Unit")

answer = input("Your answer: ")

if answer.lower() == "a":
    print("Correct!\n")
    score += 1
else:
    print("Wrong! The correct answer is Central Processing Unit.\n")

print("Quiz Finished!")
print("Your score:", score, "/ 3")
