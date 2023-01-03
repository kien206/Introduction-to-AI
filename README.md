# Introduction-to-AI
How to run our program?


Our program is written in Python3.
To run our program, first you need to download the 4 files we attached and install Python compiler to your computer.
We used some libraries such as random, math, copy,..... However these libraries can be used without downloading.


First, you need to open the file game_better.py in the_real_project folder and run this python file on the terminal. 


![image](https://user-images.githubusercontent.com/112222605/210299547-d9c63119-acf6-485a-a59c-fa9ee02bbb20.png)
Choose yes if you want to enable forced capture, meaning if there exist a capturing move, we must make that move. You should type 'yes' to play like international Checkers rule.

By default you will be 'x'.


At the next stage, you should enter the coordinate of the piece you would want to move. If your input is invalid there will be an error message and you can choose again. 
![image](https://user-images.githubusercontent.com/112222605/210331304-d362a05c-0dbc-43c3-9d15-36bfcea27894.png)
For example, if I choose my first piece is piece at coordinate 50, then it will display valid move at 41 like this. Enter one of the coordinate that appear on the screen to make the move to that coordinate: 
![image](https://user-images.githubusercontent.com/112222605/210331459-026caa1f-197c-4c72-9424-60ea85bf7218.png)
After your turn will be AI turn. By default we set the depth to our Minimax to 5 (when both players have less than 7 pieces combined then the depth will be 10). Its move will be displayed right after with colouring to show where it moved.
![image](https://user-images.githubusercontent.com/112222605/210332880-05b6683e-b8d2-4d30-8b3d-b69e8eb1fe30.png)
If you accidentally enter invalid position, it will prompt you to enter again.
The AI will make his own choice and the board will automatically update. Sometimes the board can be updated very fast, however you always can check the activity of the game by scrolling up the terminal window.


Now it's your game with COM player. The game will end if it satisfies our ending conditions. The ending conditions are either one player does not have any pieces or valid moves left; or when you and the AI exceed 50 moves without any capture then whoever has more pieces win; the game is a tie if number of pieces are equal.
Otherwise, if you want to exit the game, enter 'x' to exit: 
![image](https://user-images.githubusercontent.com/112222605/210334540-0ec15327-97c3-4b3c-ab65-018707144ef4.png)


That's how to run our game. Enjoy!
