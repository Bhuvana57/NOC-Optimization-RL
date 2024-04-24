# Network-on-Chip (NOC) Optimization using Reinforcement Learning

## Overview
This project focuses on optimizing the design of a Network-on-Chip (NOC) using Reinforcement Learning (RL). The goal is to minimize latency, maximize bandwidth, and efficiently manage buffer space, all while considering power constraints.

## Installation
1. Clone the repository:
git clone https://github.com/Bhuvana57/NOC-Optimization-RL.git

2. Install the required dependencies:
pip install numpy

## Usage
1. Run the main script to start the RL optimization process:
python main.py

2. Monitor the training progress and view the learned Q-values.

## NOC Simulation
- The NOC environment is simulated with different configurations and measures latency and bandwidth.
- Latency and bandwidth thresholds are used to calculate rewards in the RL algorithm.

## Repository Structure
- `main.py`: Main script to run the RL optimization.
- `utils.py`: Utility functions for NOC simulation and reward calculation.
- `README.md`: This file, providing an overview of the project.

## Contributing
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes and commit them (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Create a new Pull Request.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
Feel free to customize this README file with more detailed information about your project structure, how to run it, and any other relevant details
