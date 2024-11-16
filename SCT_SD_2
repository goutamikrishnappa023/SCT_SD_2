import random

def guess_the_number():
    print("Welcome to the Number Guessing Game!")
    print("I have selected a random number between 1 and 100.")
    
    # Generate a random number
    random_number = random.randint(1, 100)
    attempts = 0
    
    while True:
        try:
            # Prompt the user for their guess
            user_guess = int(input("Enter your guess: "))
            attempts += 1
            
            # Compare the guess to the random number
            if user_guess < random_number:
                print("Too low! Try again.")
            elif user_guess > random_number:
                print("Too high! Try again.")
            else:
                print(f"Congratulations! You guessed the number {random_number} correctly in {attempts} attempts.")
                break
        except ValueError:
            print("Please enter a valid number.")
            
# Run the game
guess_the_number()