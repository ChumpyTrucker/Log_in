# Log_in
def login():
    username = input("Enter your username: ")
    password = input("Enter your password: ")

    # Check if the username and password match
    if username == "ChumpyTrucker" and password == "123456789":
        print("Login successful!")
        # Call your app's main function or perform additional actions
    else:
        print("Invalid username or password. Please try again.")

# Call the login function
login()
