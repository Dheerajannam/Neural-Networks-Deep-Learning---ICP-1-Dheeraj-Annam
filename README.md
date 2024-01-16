Assignment :1 
Spring 2024: CS5720 Neural Networks & Deep Learning - ICP-1
Dheeraj Annam
Id:700759413

1. Write a python program for the following:
– Input the string “Python” as a list of characters from console, delete at least 2 characters, reverse the resultantstring and print it.

Code:
input_string = list(input("Enter a string: "))


if len(input_string) >= 2:
    
    modified_string = input_string[:-2]
    reversed_string = modified_string[::-1]
    print(''.join(reversed_string))
else:
    print("Please enter a string with at least 2 characters.")
 
Task 1 Summary:
 The program takes the input string "Python," converts it to a list of characters, deletes at least 2 characters, reverses the resulting string, and prints the reversed string.

2. Take two numbers from user and perform at least 4 arithmetic operations on them

num1 = float(input("Enter the first number: "))
num2 = float(input("Enter the second number: "))


addition = num1 + num2
subtraction = num1 - num2
multiplication = num1 * num2
division = num1 / num2

print("\nArithmetic Operations:")
print(f"{num1} + {num2} = {addition}")
print(f"{num1} - {num2} = {subtraction}")
print(f"{num1} * {num2} = {multiplication}")
print(f"{num1} / {num2} = {division}")

 



Task2 Summary:
This program prompts the user for two numbers, performs addition, subtraction, multiplication, and division operations on them, and prints the results.


3. Write a program that accepts a sentence and replace each occurrence of ‘python’ with ‘pythons’
sentence = input("Enter a sentence: ")

word_to_replace = input("Enter the word to replace: ")

replacement_word = input("Enter the replacement word: ")

modified_sentence = sentence.replace(word_to_replace, replacement_word)

print(modified_sentence)
 

Task3 Summary:
The code accepts a sentence from the user, replaces each occurrence of 'python' with 'pythons,' and prints the modified sentence.



4. Use the if statement conditions to write a program to print the letter grade based on an input class score. Use the grading scheme we are using in this class.


class_score = float(input("Enter the class score: "))


if 90 <= class_score <= 100:
    grade = "A"
elif 80 <= class_score < 90:
    grade = "B"
elif 70 <= class_score < 80:
    grade = "C"
else:
    grade = "Below C"

print(f"Letter Grade: {grade}")

 


Task4 Summary:
Taking a class score from the user, the program uses if and elif conditions to determine the letter grade based on a grading scheme, and then prints the calculated letter grade.


