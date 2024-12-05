# IM HERE Framework

## Description

**IM HERE** stands for **Interaction Model for Human Effort-based Robot Engagement**. 

It is a novel approach to modeling engagement in social interactions by analyzing and interpreting the **effort** entities exert toward each other. The framework simplifies complex relational states into four key engagement states: *Passive*, *Buildup*, *Requested*, and *Engaged*, using **focus** as single summary of entites point of interest, enabling a structured and intuitive way to simulate and study engagement dynamics. This system supports interaction modeling across diverse contexts, including human-human, human-robot, and robot-robot scenarios, fostering better understanding and integration of social behaviors in autonomous systems.

<p align="center">
  <img src="/Pictures/bob.png" />
</p>



## DISCLAIMER: the code will be uploaded once the paper is publically available

## About the Paper

This simulation framework is based on the research paper outlining the IM HERE Framework, which provides a structured approach to modeling engagement dynamics using effort-based principles. The paper is currently under review and will be available soon. 

**Citation Placeholder**: [Citation details will be added here once the paper is published.]

## Features

- **Effort-Based Engagement Modeling**:
  - Simulates interaction dynamics between entities (e.g., humans, robots, objects).
  - Implements effort modulation across channels like gaze, gesture, body alignment, and speech.
  - Tracks focus and state changes for all entities.

- **Real-Time Visualization**:
  - Displays focus, engagement states, and effort contributions in a 2D environment.
  - Visualizes fields of view (FOV), dynamic focus shifts, and interaction signals using emojis and intuitive graphics.
  - Includes debugging tools for analyzing engagement parameters.

- **Flexible and Extensible**:
  - Modular design for easy adaptation to diverse research and application needs.
  - Supports integration of custom entities and effort channels.

## Getting Started

1. **Clone the Repository**:
   ```bash
   git clone https://github.com:RoSA-Study/IM-HERE.git
   cd IM-HERE
   ```

2. **Install Dependencies**:
   Install the required Python libraries:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Simulation**:
   Execute the main script to run the simulation:
   ```bash
   python main.py
   ```

4. **Customize Entities**:
   Modify the `entities` list in `main.py` to include your desired agents (e.g., robots, humans, objects) and adjust parameters like size, position, and preferences.

## Requirements

- Python 3.8+
- Libraries:
  - `pygame`
  - `numpy`
  - `Pillow`
  - `rich`



## How to Contribute

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Submit a pull request describing your changes.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

## Contact

For any questions or feedback, feel free to open an issue or contact the authors of the accompanying paper.
