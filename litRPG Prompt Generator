# Import the random module for random selection of elements
import random

# Define lists for random generation of settings, protagonists, conflicts, and game mechanics
settings = [
    "a dungeon-filled world where every floor holds new challenges",
    "a floating sky fortress ruled by warring factions",
    "a post-apocalyptic wasteland where survivors must level up to survive",
    "a magical academy where students compete in virtual reality battles",
    "a kingdom where everyone is bound by a system that assigns them classes and skills"
]

protagonists = [
    "a former soldier turned blacksmith who discovers a hidden class",
    "a rogue AI trapped in a medieval fantasy world",
    "a bard with no musical talent who must level up by composing epic ballads",
    "a farmer who gains a rare crafting skill and becomes a legendary enchanter",
    "a noble who loses everything and must start over as a low-level adventurer"
]

conflicts = [
    "a war between guilds for control of a rare resource",
    "a quest to retrieve a stolen artifact that can alter the game world",
    "a demonic invasion that threatens to destroy the world",
    "a glitch in the system that causes monsters to grow stronger every day",
    "a rival player who will stop at nothing to defeat the protagonist"
]

game_mechanics = [
    "leveling up by defeating monsters and completing quests",
    "crafting magical items to gain an edge in battles",
    "a class system that evolves based on player choices",
    "a permadeath mechanic where players have only one life",
    "a reputation system that affects how NPCs interact with the protagonist"
]

# Function to generate a premise by combining the provided elements
def generate_premise(setting, protagonist, conflict, mechanic):
    """
    Combines the setting, protagonist, conflict, and game mechanics into a cohesive premise.
    """
    premise = f"In a world of {setting}, {protagonist} must {conflict} by {mechanic}."
    return premise

# Function to validate user input to ensure it is not empty
def validate_input(prompt):
    """
    Prompts the user for input and ensures the input is not empty.
    If the input is empty, the user is asked to try again.
    """
    while True:
        user_input = input(prompt).strip()  # Remove leading/trailing whitespace
        if user_input:  # Check if input is not empty
            return user_input
        print("Error: This field cannot be empty. Please try again.\n")

# Function to save the generated premise to a text file
def save_premise(premise):
    """
    Saves the generated premise to a file named 'litrpg_premises.txt'.
    If the file does not exist, it will be created. New premises are appended to the file.
    """
    filename = "litrpg_premises.txt"
    with open(filename, "a") as file:  # Open the file in append mode
        file.write(premise + "\n")  # Write the premise to the file
    print(f"Premise saved to {filename}!")

# Main program
if __name__ == "__main__":
    # Display welcome message and options
    print("Welcome to the Lit-RPG Novel Premise Generator!")
    print("Choose an option:")
    print("1. Enter details manually")
    print("2. Generate a random premise")
    choice = input("Enter your choice (1 or 2): ").strip()  # Get user's choice

    if choice == "1":
        # Manual input mode
        print("\nPlease enter the following details to create your premise:\n")
        setting = validate_input("Enter a setting (e.g., 'a dungeon-filled world', 'a magical academy'): ")
        protagonist = validate_input("Enter a protagonist (e.g., 'a rogue AI', 'a farmer turned enchanter'): ")
        conflict = validate_input("Enter a conflict (e.g., 'a war between guilds', 'a demonic invasion'): ")
        mechanic = validate_input("Enter a game mechanic (e.g., 'leveling up by defeating monsters', 'crafting magical items'): ")
        premise = generate_premise(setting, protagonist, conflict, mechanic)  # Generate premise

    elif choice == "2":
        # Random generation mode
        setting = random.choice(settings)  # Randomly select a setting
        protagonist = random.choice(protagonists)  # Randomly select a protagonist
        conflict = random.choice(conflicts)  # Randomly select a conflict
        mechanic = random.choice(game_mechanics)  # Randomly select a game mechanic
        premise = generate_premise(setting, protagonist, conflict, mechanic)  # Generate premise

    else:
        # Handle invalid choices
        print("Invalid choice. Exiting program.")
        exit()

    # Display the generated premise
    print("\nGenerated Lit-RPG Novel Premise:")
    print(premise)

    # Ask the user if they want to save the premise
    save_choice = input("\nWould you like to save this premise? (y/n): ").strip().lower()
    if save_choice == "y":
        save_premise(premise)  # Save the premise to a file
    else:
        print("Premise not saved. Exiting program.")
