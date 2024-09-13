# Hand-Tracking Food Catcher Game

This project is a Unity-based game with an integrated hand recognition system developed in Python using the MediaPipe framework. The main focus of the game is to control the gameplay with real-time hand movements, creating an interactive experience for children.

## About the Game

In the game, players need to catch falling food items and feed the character by using their hands. After showing their hand to the camera, players can control the hand in the game by physically moving and grasping food items, then dragging them to the character.

The hand-tracking system processes the hand data in Python and communicates with Unity via TCP to ensure seamless real-time interaction. The game was developed as part of an internship project aimed at creating a fun, educational tool for children.

![image](https://github.com/user-attachments/assets/e8e6afc2-96f1-4b81-ae8d-70d75cdb01c4)


## Features


- **Real-time Hand Tracking**: Uses Python’s MediaPipe framework for hand detection and gesture recognition.
- **Seamless Python-Unity Integration**: Hand data is transferred to Unity using TCP, allowing for smooth interaction between the hand movements and the game world.
- **Child-Friendly Design**: Simple gameplay mechanics designed for children to enjoy and learn.
- **Interactive Gameplay**: Players physically interact with the game, using their hands to catch food and feed the character.

## Technology Stack

- **Unity**: For game development and rendering.
- **Python**: To implement the hand-tracking system using MediaPipe.
- **TCP Communication**: To transfer hand data from Python to Unity in real time.
- **MediaPipe**: A framework for building perception pipelines, used here for hand detection.

## How to Play

1. Show your hand to the camera to initialize hand tracking.
2. Use hand movements to catch falling food items on the screen.
3. Drag and drop the food to feed the character.
4. Score points by successfully feeding the character with the correct items.

## Future Improvements

- Adding more levels and increasing difficulty as the game progresses.
- Implementing more advanced hand gestures for additional game actions.
- Enhancing character reactions and animations for a more engaging experience. 
