#Rock-Paper-Scissor (GAME) by https://github.com/m-s-13

import random
print("Welcome to the GAME: Stone-Paper-Scissor \n Author: m-s-13 \n")
print("Rules of the GAME : "
                        "\n Rock vs Paper --> Paper wins"
                        "\n Paper vs Scissor --> Scissor wins"
                        "\n Scissor vs Rock --> Rock wins \n")
#Rock-Paper-Scissor (GAME) by https://github.com/m-s-13
while True:
	print("Enter (using keyboard): \n 1 for *Rock \n 2 for *Paper \n 3 for *Scissor \n")
	
	choice = int(input("YOUR turn (enter 1/2/3): "))
	
	while choice > 3 or choice < 1:
		choice = int(input("enter valid input: "))
		
	if choice == 1:
		choice_name = 'Rock'
	elif choice == 2:
		choice_name = 'Paper'
	else:
		choice_name = 'Scissor'
	print("YOUR choice is: " + choice_name)

	print("\nNow its COMPUTER's turn.......")
	comp_choice = random.randint(1, 3)
#Rock-Paper-Scissor (GAME) by https://github.com/m-s-13
	while comp_choice == choice:
		comp_choice = random.randint(1, 3)
	if comp_choice == 1:
		comp_choice_name = 'Rock'
	elif comp_choice == 2:
		comp_choice_name = 'Paper'
	else:
		comp_choice_name = 'Scissor'

	print("COMPUTER'S choice is: " + comp_choice_name)

	print(choice_name + " V/s " + comp_choice_name)


	if((choice == 1 and comp_choice == 2) or
	(choice == 2 and comp_choice ==1 )):
		print("Paper wins => ", end = "")
		result = "Paper"
	elif((choice == 1 and comp_choice == 3) or
		(choice == 3 and comp_choice == 1)):
		print("Rock wins =>", end = "")
		result = "Rock"
	else:
		print("Scissor wins =>", end = "")
		result = "Scissor"

#Rock-Paper-Scissor (GAME) by https://github.com/m-s-13
	if result == choice_name:
		print("<== Congratulations, you beat the COMPUTER ==>")
	else:
		print("<== COMPUTER wins ==>")


	print("Do you want to Play again? (Y/N)")
	ans = input()
	if ans == 'n' or ans == 'N':
		break
	

print("\n Thanks for Playing... \n Author: m-s-13 \n https://github.com/m-s-13")
