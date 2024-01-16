input_string = list(input("Enter a string: "))
if len(input_string) >= 2:
    modified_string = input_string[:-2]
    reversed_string = modified_string[::-1]
    print(''.join(reversed_string))
else:
    print("Please enter a string with at least 2 characters.")






 




