# Truck Platooning System Design and Implementation
This repository contains the code and documentation for the **Truck Platooning System**, developed for the **Distributed and Parallel Systems** course at Fachhochschule Dortmund. The project simulates a four-truck platooning system to study real-time autonomous driving, communication, and synchronization using various technologies.

## Project Overview
The system involves:

- C++ implementation for truck control and communication using **multithreading (OpenMP, pthread)**.
- **V2V communication** with UDP for data transmission between trucks.
- **GPU programming** (CUDA) for sensor data processing.
## Key Features:
- Real-time platoon formation with leader/follower roles.
- Synchronized driving, obstacle avoidance, and speed adjustments.
- Parallel and concurrent task execution for efficient resource use.
## Repository Structure
- /src: Source code for truck communication and platoon behavior.
- /docs: Project report and additional documentation.
- /gpu: GPU implementation code.
## How to Run
Clone this repository.
Compile and run the **main.cpp**, **server.cpp**, **client.cpp**, and **gpu.cpp** files.
Ensure OpenMP and CUDA libraries are installed for parallel processing and GPU acceleration.
## Contact
For more details, refer to the full project report or contact the contributors listed in the documentation.