Here’s your formatted README.md file for your GitHub repository:
# 🏝 Island Adventure Game 🏝 A simple text-based adventure game written in Python where you choose between two doors and face exciting surprises.
🎮 How to Play
1. Run the Python script.
2. Choose between the *red door* and the *blue door.
3.  3. If you choose the **red door, pick a box and see what’s inside.
4. If you choose the **blue door*, beware of the crocodiles! 🐊
   📝 Code Snippet ```python print("Welcome to my Island 👋")
   doors = input("There are two doors in front of you. 🚪 A red door & 🚪 a blue door \nWhich door do you want to open?:\n")
   if doors.lower() == "red": print("Great! Now you entered a room.\nYou found three boxes: 🎁 White box, 🎁 Black box, 🎁 Green box")
   box = input("Which box do you open?\n")
   if box.lower() == "white": print("Oops! You opened a box filled with snakes 🐍🐍🐍")
   elif box.lower() == "black": print("Oops! You opened a box filled with spiders 🕷🕷🕷")
   elif box.lower() == "green": print("Congratulations! You found the Treasure 💰💰💰")
   else: print("Invalid Choice 🤷‍♂")
   elif doors.lower() == "blue": print("Oops! You chose the Crocodile Door 🐊🐊🐊\nGame Over!")
   else: print("Invalid Choice 🤷‍♂") 
🚀 How to Run
Make sure you have Python installed (preferably Python 3).
Copy the code into a file named island_game.py.
Run the script using:
python island_game.py 
📌 Features
Simple text-based adventure
Fun surprises with different outcomes
Beginner-friendly Python practice
Enjoy the game and feel free to improve it! 🚀
