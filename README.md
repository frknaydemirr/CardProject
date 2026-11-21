# Card Game
[ENG]

The purpose of this project is to demonstrate object-oriented programming principles and develop problem-solving skills by designing a simple card game consisting of 16 cards. The game, in which the player competes against the computer, will be played in two different categories: football and basketball. Each player has 8 cards (4 football players and 4 basketball players), and each category has 3 different match types (for football: free kick, penalty, one-on-one with the goalkeeper; for basketball: free throw, three-pointer, two-pointer). In each turn, a random match type from the active category will be selected, and the chosen players' attribute points will be compared. The score table will be updated accordingly, and the game will end when all cards have been used.

In our program, which is written in Java using the NetBeans IDE and the Java Swing UI library, past scores are recorded and displayed in a simple database structure. Each athlete has an image, with their attribute points displayed on it. The game flow and score table can be tracked through this interface, and the player selects cards via the UI. The computer's randomly selected card and match type are compared with the player's chosen card. Used cards cannot be reused, and the player cannot see the computer’s cards.

## Method
The Athlete (Sporcu) parent class is inherited by the Footballer (Futbolcu) and Basketball Player (Basketbolcu) classes. Similarly, the Player (Oyuncu) parent class is inherited by the User (Kullanıcı) and Computer (Bilgisayar) classes. Common attributes are defined in the parent classes, keeping the code clean and structured.The Text class is responsible for defining the athletes' attributes and names and contains the main method where the game flow is executed. The game logic is controlled and managed within the Text class.Player scores are defined as private variables and are accessed through getter and setter methods, ensuring encapsulation.



![Karşılaştırma(1-github)](https://github.com/user-attachments/assets/4020a6f2-7cc1-4950-9a72-db156008277c)


![karşılaştırma(2-github)](https://github.com/user-attachments/assets/4e582170-e314-4875-95ac-93d3e511d950)


![output(github)](https://github.com/user-attachments/assets/e2e3f6a6-dacd-4a46-98e3-af82417ff25c)


![output(github-2)](https://github.com/user-attachments/assets/3c0a4b07-f33a-4806-b2b0-e5cce8089272)


![veriTabanı(github)](https://github.com/user-attachments/assets/275612f5-c3a9-4ea1-bbdc-83f2815c3f15)


![karşılaştırma(3-github)](https://github.com/user-attachments/assets/f63fcf6a-3c43-4a67-a507-25ec966d0a15)



![Oyunbitir(github)](https://github.com/user-attachments/assets/a3426237-9d13-48ca-a3fd-f07569f567ba)

## Class Diagram -19.02.2025

![KartGame (Class Diyagram)](https://github.com/user-attachments/assets/8abd8813-ec1b-4087-bb97-c0c849036d27)




## Correct Class Diagram:  21.11.2026

<img width="1687" height="888" alt="image" src="https://github.com/user-attachments/assets/51edaa43-3580-4944-818e-ba7dc9113458" />

## Result
The program has successfully terminated. Each time the screen is opened, the deck is shuffled differently, and the cards are distributed randomly. The computer makes random selections from the shuffled cards, while the user must choose either a football player or a basketball player. As specified, consecutive actions are not allowed. If the randomly chosen "matchup" between the user and the computer results in equal card points, the cards are returned, and the game can be played again. After all the cards are used up, a new window will display the result on the screen, showing the winner or indicating a draw. Additionally, if the user clicks the "End Game" button, the program will terminate 1 second after the button is pressed.



