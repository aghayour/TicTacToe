# TicTacToe

I developed this game during the Spring semester of 2018 as part of my _Artificial Intelligence and Expert Systems_ course. The project took me roughly half a day to complete. 

I programmed the game using Java, implemented the MiniMax algorithm, and built its graphical user interface with JavaFX and Adobe Photoshop. 

Players can choose to compete against another human or challenge the computer; however, the computer is unbeatable because it relies on a fully explored MiniMax decision tree.

To run the game, compile it into the bin directory and run it from there, with the JavaFX SDK on the module path:
```bash
javac --module-path /path-to-your-javafx-directory/openjfx/lib --add-modules=javafx.controls -d bin src/*.java
cd bin
java --module-path /path-to-your-javafx-directory/openjfx/lib --add-modules=javafx.controls Main
```

![Game Screenshot](TicTacToe-Screenshot.png)
