# Treasure--Island-
#This repo consists of code to run a python based game called Treasure Island. 
#Topics used - Logical Operators 



print(r'''
*******************************************************************************
          |                   |                  |                     |
 _________|________________.=""_;=.______________|_____________________|_______
|                   |  ,-"_,=""     `"=.|                  |
|___________________|__"=._o`"-._        `"=.______________|___________________
          |                `"=._o`"=._      _`"=._                     |
 _________|_____________________:=._o "=._."_.-="'"=.__________________|_______
|                   |    __.--" , ; `"=._o." ,-"""-._ ".   |
|___________________|_._"  ,. .` ` `` ,  `"-._"-._   ". '__|___________________
          |           |o`"=._` , "` `; .". ,  "-._"-._; ;              |
 _________|___________| ;`-.o`"=._; ." ` '`."\ ` . "-._ /_______________|_______
|                   | |o ;    `"-.o`"=._``  '` " ,__.--o;   |
|___________________|_| ;     (#) `-.o `"=.`_.--"_o.-; ;___|___________________
____/______/______/___|o;._    "      `".o|o_.--"    ;o;____/______/______/____
/______/______/______/_"=._o--._        ; | ;        ; ;/______/______/______/_
____/______/______/______/__"=._o--._   ;o|o;     _._;o;____/______/______/____
/______/______/______/______/____"=._o._; | ;_.--"o.--"_/______/______/______/_
____/______/______/______/______/_____"=.o|o_.--""___/______/______/______/____
/______/______/______/______/______/______/______/______/______/______/_____ /
*******************************************************************************
''')
print("Welcome to Treasure Island.")
print("Your mission is to find the treasure.")
choice1 = input('You\'re at a cross road, choose a direction?", "left" or "right".').lower()
if choice1 == "right":
    print(" You fell in a ditch\n !!!Game over!!!!!")
else:
    choice2 = input("You are at a lake now. Would like to wait for a boat? or swim?").lower()
    if choice2 == "swim":
        print("The lake is infested with fresh water crocodiles!!\n !!!They ate you alive!!!\n !!!Game over!!!")
    else:
     choice3=input("The boat took you to other side of the lake and dropped you at a palace entrance. It has three doors\nYellow\nGreen\nRed\nchoose your door").lower()
     if choice3 == "red":
         print("The door lead you to the treasure. You won the treasure")
     elif choice3 == "yellow":
         print("The door has hungry lions behind it, which killed you\n!!!!Game over!!!!")
     elif choice3 == "green":
         print("There are Beasts behind the door, who killed you\n!!!Game over!!!")
     else:
         print("The door selection is invalid\n !!!Game over!!!")






