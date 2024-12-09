# Mobile-Robot-Navigation-Using-Fuzzy-Logic

A project to design and simulate a robot control system using fuzzy logic in CoppeliaSim. The robot navigates to a goal while avoiding obstacles, leveraging sensor data to make decisions. Includes fuzzification, a rule base, and defuzzification for adaptive navigation in dynamic environments. Ideal for robotics research.

Key Features
Fuzzy Logic Control: Implements linguistic terms and rules for decision-making based on sensor inputs.
Simulation in CoppeliaSim: The environment includes static/dynamic obstacles and a goal location.
Obstacle Avoidance: Ensures the robot navigates safely in complex environments.
Dynamic Adaptation: Robot adapts to varying obstacle positions and goal orientations.
How It Works
Input Parameters:

Sensor data (distances to obstacles): Left, Front, Right.
Angle/orientation to the goal.
Output Parameters:

Linear speed of the robot.
Turning angle for directional control.
Fuzzy Logic Concepts:

Fuzzification: Converts sensor data into linguistic terms like Close, Medium, Far.
Rule Base: Maps input parameters to outputs using human-like reasoning.
Defuzzification: Transforms fuzzy outputs into precise control commands.
Getting Started
Prerequisites:
Install CoppeliaSim.
Ensure Python is installed (for external control, if needed).
Steps:
Clone this repository:
bash
Копировать код
git clone https://github.com/your-username/fuzzy-logic-robot-navigation.git
cd fuzzy-logic-robot-navigation
Open the provided CoppeliaSim scene file.
Run the simulation and observe the robot's behavior.
Modify fuzzy logic rules and parameters in the script to explore different behaviors.
Applications
Autonomous mobile robots in warehouses or unknown environments.
Research and education in intelligent control systems.
Pathfinding and real-time obstacle avoidance in robotics.
License
This project is licensed under the MIT License.

Feel free to copy this into your repository and customize it further!
