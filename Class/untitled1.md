# Import the `string` library.


# Use the `string` library to initialize string variables representing all valid letters and digits, respectively.


# Define a function called `check_strength` that takes in a string parameter called `password`.

    # Create two boolean variables called `contains_number` and `contains_letter`. Set them to False.


    # Initialize a `count` variable and set it to 0.


    # Loop through each character in the `password` and increment the `count` variable by 1 for each character.


        # Create an if-else statement that loops through each character in `password` and updates `contains_number` or `contains_letter` to True.


    # If `password` contains equal to or fewer than 6 characters and consists only of numbers, print "Your password is too weak."
    # Else if `password` contains more than 6 characters and consists of at least one number and at least one letter, print "Your password is a strong password".
    # Else, print "Your password is of average strength."


# Declare a variable as `user_input_password` with an input stating "Input your password: ".


# Call the check_strength function with the `user_input_password`.

# Initial variable to track game play
user_play = "y"

# While we are still playing...
while user_play == "y":

    # Ask the user how many numbers to loop through
    user_number = int(input("How many numbers? "))

    # Loop through the numbers. (Be sure to cast the string into an integer.)
    for x in range(user_number):

        # Print each number in the range
        print(x)

    # Once complete...
    user_play = input("Continue: (y)es or (n)o? ")
