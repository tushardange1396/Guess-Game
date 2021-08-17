# Guess-Game

n=18
no_of_gussess=1
print("number of gussess is limited till 9")
while no_of_gussess<=9:
    guess_number = int(input("Guess the number: "))
    if guess_number<18:
        print("You Inputed Less Number Please Input Higher Number ")

    elif guess_number>18:
        print("You Inputed Higher Number Please Input Lesser Number")
    else:
        print("You Won !!")
        break
    print("no of guesses left")
    no_of_gussess=no_of_gussess+1

if no_of_gussess>9:
    print("Game Over !!!")
