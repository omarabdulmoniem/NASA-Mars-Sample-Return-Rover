# NASA Mars Sample Return Rover
This repository contains the code for the NASA Sample Return Rover Image Processing project. The project focuses on developing image processing algorithms to analyze and identify samples on the Martian surface using a simulated rover environment.

## Files

The project consists of the following Python files:

- `decision.py`: This file contains the implementation of the decision-making algorithm for the rover. It determines the appropriate actions based on the processed images and other rover data.

- `drive_rover.py`: This file contains the main script to drive the simulated rover. It establishes a connection with the simulator, receives data from various sensors, and executes the decision-making algorithm.

- `perception.py`: This file contains the image processing pipeline implementation. It applies various techniques to process the images captured by the rover's camera.

- `supporting_functions.py`: This file contains supporting functions and helper methods used in other Python files. It provides common functionalities and utilities for image processing and data manipulation.

## Setup and Dependencies
To run this project, you need to have Python installed on your system. The code has been developed and tested using Python 3.7, but it should be compatible with other Python 3 versions.

## Usage
To run the project, follow these steps:

1. Launch the simulator on your Linux environment.

2. In a terminal or command prompt, navigate to the project directory.

3. Execute the following command to start the rover script:
```
>python drive_rover.py
```
4. The rover will start processing the images and making decisions based on the implemented algorithm. You can observe the rover's actions and the output in the simulator window.
5. The rover will collect all samples and return to the starting position


