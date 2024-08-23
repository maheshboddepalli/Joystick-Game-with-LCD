# Joystick-Game-with-LCD
Project Abstract : This project involves designing and implementing a simplified version of the Super Mario game using a 16x2 LCD display. The game features basic functionalities, such as character movement and simple obstacles, controlled via input buttons. The objective is to provide a minimalistic yet functional version of the classic game on a small-scale display.
Introduction :
In this project, we are making a jumping jack game using Arduino Uno with a 16*2 LCD Display. In the sketch, a basic mini-program of a retro video game replicating the Super Mario Bros arcade game is a good code to explore and study if you are into programming.
Components Required : 
1. Arduino UNO 
2. Jumper Wires 
3. Standard LCD - 16x2 with I2C Connector
4. Analog joystick 

Description of the Project : The project involves creating a simple Super Mario game where the character can move horizontally across the 16x2 LCD screen, avoiding obstacles represented by specific characters. The game is controlled using push buttons that allow the player to move Mario left or right. The LCD screen is used to display the game state, including the position of Mario and obstacles.
Procedure: 
1.	Setup the Hardware:
•	Connect the 16x2 LCD display to the microcontroller using the appropriate pins (usually using 4-bit or 8-bit mode).
•	Connect the push buttons to the microcontroller for user inputs.
•	Use a breadboard to organize connections and ensure a stable setup.
•	Adjust the LCD contrast using a potentiometer.
2.	Initialize the LCD:
•	Write the code to initialize the LCD and configure it for displaying characters.
•	Test the LCD by displaying simple text messages to ensure proper connections and functionality.
3.	Design the Game Logic:
•	Create variables and functions to handle the game state, player position, obstacles, and score.
•	Implement the main game loop that updates the game state and refreshes the LCD display accordingly.
•	Handle user inputs through push buttons to control Mario's movements.
4.	Implement the Display Update:
•	Write functions to update the LCD display based on the game state.
•	Use custom characters if needed to represent Mario and obstacles within the limited resolution of the LCD.
5.	Test and Debug:
•	Test the game thoroughly to ensure it runs smoothly.
•	Debug any issues related to display updates, input handling, and game logic.
Result : When running the project, the 16x2 LCD display shows Mario as he moves based on user input. Obstacles move from right to left across the screen. If Mario collides with an obstacle, the game displays "Game Over" and resets.
Conclusion : This project successfully demonstrates how a simple version of the Super Mario game can be implemented on a 16x2 LCD display. It highlights the challenges and creative solutions required to adapt complex games for small-scale, low-resolution displays. This project serves as a foundation for more advanced game development on embedded systems.
