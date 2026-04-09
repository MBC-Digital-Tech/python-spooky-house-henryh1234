<h1>Spooky House Escape </h1>
<h2>Simple Python Game</h2>
How the Game Works<br>

<ol>
<li>The player chooses a red or blue door.</li>
<li>Each door leads to two new choices.</li>
<li>Some choices help the player escape, and some lead to GAME OVER!</li>
</ol>

Step 1: Import random
At the top of your Python file, add this line to use random choices later.
import random
print(“The aim of this game is to escape the spooky house.”)

Step 2: Create a List of Scary Sounds
We will use this list to make the game spooky!
scary_sounds = ["a creaky door", "a whisper", "a loud bang", "footsteps behind you"]

Step 3: Start the Game and Get Player Input
Print a message and ask the player to choose a path.
print("You enter a spooky house. It's dark and silent... except for", random.choice(scary_sounds))
print("You see two doors: one RED and one BLUE.")
choice1 = input("Which door do you choose? (red/blue) ").lower()

Step 4: Use Conditionals for Different Paths
Now, we create different results based on the player's choices. Here is HALF your possible code. 
if choice1 == "red":
    print("The red door creaks open... You see a dusty staircase and a dark hallway.")
    choice2 = input("Do you go UP the stairs or into the HALLWAY? (up/hallway) ").lower()
    if choice2 == "up":
        print("You reach the attic and find a window. You escape! Yay!")
    else:
        print("The hallway leads to a locked door... Suddenly, you hear footsteps behind you. BOO! GAME OVER!")

Now you must write the rest of the code!! (i.e. What happens if the choice 1 is blue?

Add your own twists by:
•	Changing the story
•	Adding more choices
•	Using more random events

Don’t forget to commit your code using today’s date.
