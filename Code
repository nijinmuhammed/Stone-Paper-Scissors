import random

user_score = int()
computer_score = int()

while True:
    print("          =========================\n          "
          " * Stone Paper Scissor * \n          "
          "=========================")
    user = input("select your choice (Stone, Paper, Scissor): ").lower()
    choice = ["Stone", "Paper", "Scissor"]
    bot = random.choice(choice).lower()

    if user == bot:
        print(f"Both are selected {bot}")
        print("It's a Tie!")
    elif user == "stone":
        if bot == "scissor":
            print("Computer selected Scissor\nStone smashes Scissor! You win!")
            user_score += 1
        else:
            print("Computer selected Paper\nPaper covers Stone! You lose.")
            computer_score += 1
    elif user == "paper":
        if bot == "stone":
            print("Computer selected Stone\nPaper covers Stone! You win!")
            user_score += 1
        else:
            print("Computer selected Scissor\nScissor cuts paper! You lose.")
            computer_score += 1
    elif user == "scissor":
        if bot == "paper":
            print("Computer selected Paper\nScissor cuts Paper! You win!")
            user_score += 1
        else:
            print("Computer selected Stone\nStone smashes Scissor! You lose.")
            computer_score += 1
    else:
        print("Your selection is invalid!")

    play_again = input("Play again? (y/n): ")
    if play_again.lower() != "y":
        print("Your selection is invalid!")
    elif play_again.lower() == "n":
        break

print(f"**********SCORE BOARD********** \n \nYour score :{user_score}\nComputer score :{computer_score}")
print("")
if computer_score > user_score:
    print("COMPUTER WON! \nDon't worry try again fail again\n"
          "fail better, the world is yours...")
elif computer_score == user_score:
    print("It's a tie!")
else:
    print("YEAHHH YOU WON! thankalk oru kuthirappavan!")
