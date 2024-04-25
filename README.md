# key-cod
key cod
# Define a list of valid key codes
valid_key_codes = ["ABC123", "DEF456", "GHI789"]

# Function to check if the entered key code is valid
def check_key_code(entered_code):
    if entered_code in valid_key_codes:
        return True
    else:
        return False

# Main function
def main():
    # Prompt the user to enter the key code
    entered_code = input("Please enter the key code: ")
    
    # Check if the entered key code is valid
    if check_key_code(entered_code):
        print("Access granted! The key code is valid.")
    else:
        print("Access denied! Invalid key code.")

# Call the main function
if __name__ == "__main__":
    main()
