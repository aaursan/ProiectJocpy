# ProiectJocpy
This was the BCS degree application.

Note: all the photos used here are from my Degree presentation. 

The application aims to make a distributed game on the Windows platform. For this, the Python language(3.7) was used to which the interface modules were added, namely PySide2 and the socket module for the connection between the server and the client interface. 
 The game is designed in such a way that it is easy to access, having specific buttons as well as one providing information about how to play. The player is also put to various attempts to "beat" the computer. He also has the option to choose to play against another player, being a simpler or more difficult task depending on the players.
 One surprise element that the game brings is the hexagonal grid that makes the game not only last longer but more competitive thus giving more room to develop your own in-game strategies. Speaking of strategies, the most classic is to always play in the sides of the hexagon.




Firstly, we introduce into game with an Astah diagram to know better the principles of the game.

![Diagram](https://user-images.githubusercontent.com/52974293/189528187-bde175bb-bb36-4833-b6da-fa859ca79a6f.png)

Down Here we can see the menu in all its glory. I've also added a list of some important Libraries & Algorithm used.

![libraries](https://user-images.githubusercontent.com/52974293/189528485-3b4a8b45-af8a-42c4-9f3a-26ef5d5f490f.png)

![Menu](https://user-images.githubusercontent.com/52974293/189527483-48617964-9106-4e1b-8443-a7e3a39de1fe.png)

As you can see, there are lots of options here. First, by pressing "Meci AI" or "Joc Nou" will start a CPU game.

If you want to host a game, pressing "Hosteaza joc" will host a game until the second person join. The condition to join is the localhost(127.0.0.0) as shown below


Let's dive and see what is all about.


Playing a CPU match looks like this:

![jucatorVSpc](https://user-images.githubusercontent.com/52974293/189528839-aa25f6da-bd22-4aab-8ee0-5328529969b4.png)

As you can see, there are 2 players(Player & CPU) that can have a score & the squares dominated.


Same goes for a Player vs Player match, where the settings change a bit and looks like this:

![jucatorVSjucator](https://user-images.githubusercontent.com/52974293/189528944-6c492e7f-3589-4878-a728-626163f31b9b.png)

As you can see, the 2 players has their board & scores. 

However, the most important thing to notice is that the board, score and squares are updated automatically everytime someone makes a move.

