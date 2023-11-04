# reverse_string

def reverse_string(input_str):
    return input_str[::-1]

if __name__ == "__main__":
    user_input = input("Enter a string: ")
    reversed_string = reverse_string(user_input)
    print("Reversed string:", reversed_string)
    input("Press Enter to exit")


pyinstaller --onefile reverse_string.py


