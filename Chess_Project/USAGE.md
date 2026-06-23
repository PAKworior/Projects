you enter the commands to play the game.  
these are the given regexes patterns to all the commands:  
<img width="1203" height="261" alt="image" src="https://github.com/user-attachments/assets/1b8aef6a-4027-4594-aac8-2a853d5648e7" />  
  
i will add a feature, where you can type "help" in game  to see the game manual  
## commands to play the game:  
  6: moving a piece:  
    entering: "e4 f5" will move the piece from e4 spot to f5 if it's a valid chess move  
  1: command to castle:  
    entering: "c a1" will allow you to castle with the rook you want if it fulfils all the conditions for castling  
  11: to change game theme:  
    type: "theme" to open a menu of theme change  
  7:  typing "a1" will show all valid moves that the piece on that coordinates can do  
  
## developer commands for testing(basically maximum priviliges)  
 2: enter "c" or "clear" to clear the chessboard  
 3: enter "t" or "test" to run the tests that you can custom write to do testing  
 4: enter "r" or "restart" to restart, ofc  
 5: placing special pieces to board:  
         inorder to place any other chess piece, you need to enter command like this "bki e4"  
         where, b means black and ki = king and "e4" is the coordinate where you want to place it  
         " <b = black, w = white><ki = king| r = rook| p = pawn| q = queen| k = knight| b = bishop>  
         in "wq e4"  
        w = white  
        q = queen  
        e4 = chess coordinates you want to place it in(they are different from normal coordinates)  
  
8: you can use this command to display a notification on the notification bar:  
    format: " -m \"enter contents of the notification\"  {time in a few miliseconds}"  
    example " -m \"hello, my name is Umar\" 3000 "  
    this will display the message "hello, my name is Umar" for 3000 milliseconds  
    this is also usefull for debugging since you can't use normal std::cout or printf in this code since terminal is already been used and else, undefined befaveour happens.  
9: this command is for removing a notification. every notification on the board is been assined an id automatically when you run the command #8, and the scheduler runs this command to remove that pirticular notification. you don't have to worry about it.  
10: when you are in theme menu, or pawn promotion menu this command handles the interaction with the menues.  
11: it opens theme menu to change the game menu.  














You enter the commands to play the game.
These are the given regex patterns for all the commands:

(Image: Regex patterns reference)

You can type "help" in-game to see the game manual.

## Commands to Play the Game

1: Moving a piece:
   Entering: "e4 f5" will move the piece from e4 spot to f5 if it's a valid chess move

2: Command to castle:
   Entering: "c a1" will allow you to castle with the rook you want if it fulfills all the conditions for castling

3: To change game theme:
   Type: "theme" to open a menu of theme change

4: Typing "a1":
   Will show all valid moves that the piece on that coordinate can do

## Developer Commands for Testing (Maximum Privileges)

5: Enter "c" or "clear":
   Clear the chessboard

6: Enter "t" or "test":
   Run the tests that you can custom write for testing

7: Enter "r" or "restart":
   Restart the game

8: Placing special pieces to board:
   To place any chess piece, enter a command like: "bki e4"
   where: b = black, ki = king, e4 = coordinate
   
   Format: "<color><piece><coordinate>"
   - Colors: b = black, w = white
   - Pieces: ki = king, r = rook, p = pawn, q = queen, k = knight, b = bishop
   
   Example: "wq e4" places a white queen at e4

9: Display a notification on the notification bar:
   Format: "-m \"notification message\" {time in milliseconds}"
   Example: "-m \"hello, my name is Umar\" 3000"
   
   This will display "hello, my name is Umar" for 3000 milliseconds.
   Useful for debugging since you can't use normal std::cout or printf in this code, as the terminal is already in use and could cause undefined behavior.

10: Remove a notification:
    Every notification on the board is assigned an ID automatically when you run command #9.
    The scheduler runs this command to remove that particular notification.
    You don't have to worry about it.

11: Menu interaction:
    When you are in the theme menu or pawn promotion menu, this command handles the interaction with the menus.

12: Open theme menu:
    Opens the theme menu to change the game theme.

---

**Changes made:**
- Fixed capitalization at the start
- Corrected spelling: "regexes" → properly formatted, "fulfils" → "fulfills", "inorder" → "in-game/to", "befaveour" → "behavior", "pirticular" → "particular"
- Consistent indentation throughout
- Removed extra spacing and blank lines
- Clarified command descriptions for clarity
- Standardized formatting for the piece placement command
















