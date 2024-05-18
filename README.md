# Tic-Tac-Toe-WindowsXP
A Windows XP Era Inspired Tic-Tac-Toe Game. Implemented in Python using Tkinter, Transport Back to 2004!

***INSERT PICTURE HERE****

## 📎 It looks like you're being nostalgic! Would you like help?

🖥️ Windows XP was the exposure to a computer I ever got to experience.
* At the young age of ***3***, I spent untold hours playing games on the computer at my grandma's house.
* It was in these simple inbuilt games and internet explorer that I became interested in technology.

🔍 This Project's goal was to create a game I **could** have played as a child, while also helping devolp my skills as a coder.
* It refined my knowledge of implementing GUI's using Tkinter.
* It also was just a fun coding project in Python.

## 👀 Look & Feel

🪟 My first major priority was to copy the aesthetic and feel of the built-in applications that ran on Windows XP.
* This meant gray buttons, recessed text, and pop-up windows for completions.
* I also implemented a color picker for the player, using a 16-color limit with an open pallette on the screen.
  * This was inspired by early paint programs I would play with.

## ⌨️ Coding & Algorithm

🐍 This code was written in **Python.**
* This did lead to some problems getting it to run on my Windows XP Virtual Machine.
* This was simply due to the age of Windows XP, which stopped getting official support on April 8, 2014.
* I ended up having to install a user generated Python interpreter to get it to run in Windows XP, found on this old reddit thread.
  * https://www.reddit.com/r/Python/comments/3tgi0t/python_35_x86_on_windows_xp/
  * You will need to download and install additional .dll files for full compatibility, so please be patient if you want to run it on XP.
* **Of course, you can simply run this on your mordern OS without issue!** [🙂]

🤖 The AI for the game uses the **Minimax Algorithm.**
* This means the the AI attemps to minimize the loss via a **worst case scenario.**
* Since Tic-Tac-Toe is a fairly simple game with only 9 possible moves, I have given the AI the data set of all 8 possible winning combinations.
* It tries to choose moves based on boxes that it can link to win the game.
  * If the AI is chosen to go first in a single-player game, it will choose a box randomly and try to build a win based on this box. 
