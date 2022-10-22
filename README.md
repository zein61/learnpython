# learnpython
Learning python is fun


print('''
          |                   |                  |                     |
 _________|________________.=""_;=.______________|_____________________|_______
|                   |  ,-"_,=""     `"=.|                  |
|___________________|__"=._o`"-._        `"=.______________|___________________
          |                `"=._o`"=._      _`"=._                     |
 _________|_____________________:=._o "=._."_.-="'"=.__________________|_______
|                   |    __.--" , ; `"=._o." ,-"""-._ ".   |
|___________________|_._"  ,. .` ` `` ,  `"-._"-._   ". '__|___________________
          |           |o`"=._` , "` `; .". ,  "-._"-._; ;              |
 _________|___________| ;`-.o`"=._; ." ` '`."\` . "-._ /_______________|_______
|                   | |o;    `"-.o`"=._``  '` " ,__.--o;   |
|___________________|_| ;     (#) `-.o `"=.`_.--"_o.-; ;___|___________________
____/______/______/___|o;._    "      `".o|o_.--"    ;o;____/______/______/____
/______/______/______/_"=._o--._        ; | ;        ; ;/______/______/______/_
____/______/______/______/__"=._o--._   ;o|o;     _._;o;____/______/______/____
/______/______/______/______/____"=._o._; | ;_.--"o.--"_/______/______/______/_
____/______/______/______/______/_____"=.o|o_.--""___/______/______/______/____
/______/______/______/______/______/______/______/______/______/______/
''')

print("Welcome to Treasure Island.")
print("Your mission is to find the TREASURE.") 

answer1 = input('You\'re at a crossroad. Where do you want to go? Type "left" or "right"\n').lower()
if answer1 == "left":
  print('You\'ve come to a lake. There is an island in the middle of the lake.')
  answer2 = input('Type "wait" to wait for a boat. Type "swim" to swim across.\n').lower()
  if answer2 == "wait":
    answer3 = (input("You arrive at the island unharmed. There is a house with 3 doors. One 'RED', one 'YELLOW' and one 'BLUE'. Which colour do you choose?\n")).lower()
    if answer3 == "yellow":
      print("You found the treasure! CONGRATULATIONS! YOU WIN!!!")
                    
    elif answer3 == "red":
      print("It's a room full of fire. GAME OVER.")
    elif answer3 == "blue":
      print("You enter a room of beasts. GAME OVER.")
    else:
      print("You chose a door that doesn't exist. GAME OVER.")
  else:
    print("You get attacked by an angry trout. GAME OVER.")
  
else:
  print("You fell into a hole. GAME OVER.")


