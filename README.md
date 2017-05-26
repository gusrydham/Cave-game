# Cave-game
Finished version of Cave-game 2.0

This project is part of course the TIG059 at Gothenburgs University. 

This folder contains the finished code for the Cave-game along with necessary applications needed to run the application.

-----------------------------------------------------------------------------------------------------------------------------------

Information about how to complie and run the game:

För att kunna köra programmet behöver datorn ha Java installerat. Java kan du ladda ner på följande länk:
https://www.java.com/sv/download/windows-64bit.jsp
Följ instruktionerna på skärmen för att slutföra installationen. 

För att använda alla färdigskrivna script behövs också Git installeras. 
Gå in på följande länk och välj nedladdning utefter vilket operativsystem din dator har: 
https://git-scm.com/downloads

För att kompilera:
Stå i mappen Cave-game
För att köra scriptet skriver du "./build.sh".
Om du vill kompilera utan scriptet skriver du “javac se/itu/game/main/MainGui.java”

För att köra programmet:
Stå i mappen Cave-game
För att köra programmet skriver du
 " java $FLAGS -cp "sqlite-jdbc-3.16.1.jar:." se.itu.game.main.MainGui "
Om du använder en Windows-dator använder du istället: “ java $FLAGS -cp "sqlite-jdbc-3.16.1.jar;." se.itu.game.main.MainGui “

------------------------------------------------------------------------------------------------------------------------------------

How to play the game:

To move around, use the buttons on the left named north, south, east and west. If you are unable to press a button, there is no room in that direction. 

To pick up items from a room, double click the item in the list to your right calles "Things in room". 
To drop items, double click the item in the list to the left called "Inventory".



