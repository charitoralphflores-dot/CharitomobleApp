Guess the Emoji - Flutter Game

Project Description

Guess the Emoji is a simple interactive Flutter mobile game where the player is shown an emoji and must identify what it represents. The game provides three possible answers, keeps track of the player's score, and gives immediate feedback after each answer.

This project was created as a Flutter/Dart application to demonstrate basic mobile application development concepts such as widgets, screen navigation, state management, user interaction, random question selection, and dialog boxes.

Features

🏠 Home Screen

Displays the game title.

Provides a play button to start the game.

🎮 Emoji Guessing Game

Displays a randomly selected emoji.

Provides three possible answers.

Randomizes the position of the answer choices.

⭐ Score System

Increases the score when the player selects the correct answer.

Displays the current score while playing.

✅ Answer Feedback

Shows a "Correct!" message for the right answer.

Shows a "Try Again!" message for an incorrect answer.

Displays the correct answer after each attempt.

🔄 Next Question

Allows the player to continue to another randomly selected emoji.

Technologies Used

Flutter - Framework used to build the application.

Dart - Programming language used for the application logic.

Material Design - Used for the user interface components and styling.

Project Structure

my_game/
├── lib/
│   ├── main.dart
│   ├── Homepage.dart
│   └── WordGame.dart
├── android/
├── ios/
├── web/
├── windows/
├── linux/
├── macos/
├── pubspec.yaml
└── README.md

Main Files

lib/main.dart

This is the starting point of the Flutter application. It runs the GuesstheEmoji widget and opens the HomePage.

lib/Homepage.dart

This file contains the home screen. It displays the Guess the Emoji title and a play button. When the player taps the play button, Flutter navigates to the WordGame screen.

lib/WordGame.dart

This file contains the main game logic. It:

Stores the available emojis and their correct answers.

Selects an emoji randomly.

Creates two incorrect choices and one correct choice.

Randomizes the three choices.

Checks the player's answer.

Updates the score.

Displays feedback using an AlertDialog.

Loads the next question.

pubspec.yaml

This file contains the Flutter project configuration, SDK requirements, and dependencies used by the application.

How the Game Works

The application starts on the Home Screen.

The player taps the Play button.

The game randomly selects an emoji.

Three answer choices are displayed.

The player selects an answer.

If the answer is correct, the score increases by one.

A dialog displays whether the answer was correct or incorrect.

The player taps Next to continue.

A new random emoji and new answer choices are displayed.

Example Questions

The game currently includes emojis such as:

Emoji

Correct Answer

🍎

Apple

🐶

Dog

🐱

Cat

☀️

Sun

🌙

Moon

🐟

Fish

🚗

Car

🌸

Flower

🍈

Melon

🍊

Orange

🥭

Mango

🏠

House

🐎

Horse

Installation and Setup

Requirements

Before running the project, make sure the following are installed:

Flutter SDK

Dart SDK

Android Studio or Visual Studio Code

An Android emulator, physical Android device, or another supported Flutter platform

Steps

Extract the project folder.

Open the project in Android Studio or Visual Studio Code.

Open a terminal inside the project folder.

Run:

flutter pub get

Check that Flutter is correctly installed:

flutter doctor

Start an emulator or connect a physical device.

Run the application:

flutter run

Game Interface

The application uses a simple and colorful interface:

Blue background for the main screens.

Large emoji display for easy recognition.

Large answer buttons for user interaction.

Score display at the top of the game screen.

Dialog feedback after every answer.

Learning Objectives

This project demonstrates the following Flutter and Dart concepts:

Creating Flutter applications.

Using StatelessWidget and StatefulWidget.

Building interfaces with Scaffold, Column, Center, Text, and Container.

Handling button and gesture events.

Navigating between screens using Navigator.push().

Managing changing data using setState().

Using Dart lists and maps.

Generating random values with Random.

Using conditional statements.

Displaying dialogs with showDialog() and AlertDialog.

Creating a simple scoring system.

Future Improvements

Possible improvements for future versions include:

Adding more emojis and questions.

Adding sound effects and background music.

Adding different difficulty levels.

Adding a timer for each question.

Adding a lives or mistake system.

Adding a final score screen.

Adding high-score storage.

Adding animations and improved visual effects.

Adding a restart game button.

Author

Student Flutter Project

Conclusion

The Guess the Emoji project is a simple educational Flutter game designed to demonstrate fundamental Flutter and Dart programming concepts. It combines a user-friendly interface with interactive game logic, random question generation, answer validation, and score tracking.
