# TD-Backgammon
## Project explanation
 This project aims to develop a Backgammon Android application with an integrated AI opponent. The app allows users to play against the AI, which is
 built using reinforcement learning principles inspired by Gerald Tesauro's TD-Gammon. The AI evaluates possible moves and selects the optimal one
 for its turn. The purpose is to provide a challenging and engaging gameplay experience while demonstrating advanced AI techniques.
 The AI was trained using approximately 18,000 epochs in a simulated environment to develop a reasonable understanding of the game. While it is not
 perfect, it can effectively evaluate moves and provide a competitive experience. The Python's Gym backend handles state representation and move
 generation, while the Android front-end ensures smooth interaction for users. TensorFlow Lite enables real-time evaluation of moves on mobile
 devices

 ## TD-Gammon
 TD-Gammon is one of the earliest examples of successful reinforcement learning applied to a complex board game. Gerald Tesauro’s approach
 leverages temporal-difference learning, where the AI evaluates states and predicts their value based on future rewards. The model's strength lies in its
 ability to:
 1. Learn from Self-Play: TD-Gammon improves its strategy by repeatedly playing against itself, refining its decision-making over time.
 2. Handle Non-Deterministic Games: Backgammon’s use of dice introduces randomness, and TD-Gammon effectively adapts to probabilistic
 scenarios.
 3. Use Neural Networks: The model applies a neural network to generalize from previous game states, making it versatile in predicting outcomes
 for unseen scenarios.
 This made TD-Gammon an ideal foundation for our project, as its structure aligns well with the goals of creating a competitive and adaptive AI for
 backgammon.

## Android
Android app was made by my good friend [Davit Chinchaladze]([url](https://github.com/datotoda)). Project was made for course Intelligent Systems Programming in The University of Vigo.
I integrated both model and environment into android app using tensorflow and Chaquopy libraries. It was my first time using python code into android kotlin environment and also first time deploying model
to the app. Task was interesting and I had no problem with this process.

You can download APK file on your android device and test it!
