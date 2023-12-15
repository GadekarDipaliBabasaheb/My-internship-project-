# Input handling
def get_user_choice(choices):
    while True:
        user_input = input("Enter your choice: ").lower()
        if user_input in choices:
            return user_input
        else:
            print("Invalid choice. Try again.")

# Display
def display_text(text):
    print(text)

# Game logic
def explore_forest():
    display_text("You find yourself in a dense forest. What do you want to do?")
    choices = ["explore", "rest", "return"]
    user_choice = get_user_choice(choices)

    if user_choice == "explore":
        display_text("You discover a hidden cave.")
        # Continue the story...
    elif user_choice == "rest":
        display_text("You take a nap under a tree.")
        # Continue the story...
    elif user_choice == "return":
        display_text("You decide to go back.")
        # Continue the story...

# Main game loop
def main():
    display_text("Welcome to the Text-Based Adventure Game!")
    explore_forest()

if __name__ == "__main__":
    main()
