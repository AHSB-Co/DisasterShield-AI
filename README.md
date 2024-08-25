# DisasterShield AI

**DisasterShield AI** is an advanced edge AI drone system designed to autonomously monitor environments, detect early signs of natural disasters, and provide real-time alerts for proactive disaster prevention. This project aims to leverage the power of AI, FPGA acceleration, and edge computing to create a robust and reliable system for disaster management and environmental monitoring.

## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [System Architecture](#system-architecture)
- [Installation](#installation)
- [Usage](#usage)
- [Applications](#applications)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Project Overview

DisasterShield AI integrates machine learning, environmental sensors, and autonomous drone technology to detect and respond to natural disasters like flash floods, droughts, and more. The system uses real-time data analysis powered by FPGA acceleration to identify potential threats and provides instant alerts to authorities, enabling timely interventions.

## Features

- **Autonomous Operation**: Pre-programmed flight paths for autonomous monitoring of disaster-prone areas.
- **Real-Time Detection**: Edge AI models for detecting anomalies indicative of natural disasters.
- **Multi-Modal Data Fusion**: Combines image data with environmental sensor readings for enhanced accuracy.
- **FPGA Acceleration**: High-speed processing for real-time analysis and decision-making.
- **Remote Alerts**: Immediate notification to authorities through real-time data transmission.

## System Architecture

The system comprises the following components:

1. **Drone Platform**: Equipped with cameras and environmental sensors for data collection.
2. **Edge AI Processor**: FPGA-based processing unit running AI models for real-time analysis.
3. **Environmental Sensors**: Humidity, temperature, air pressure, and soil moisture sensors for comprehensive environmental monitoring.
4. **Data Transmission Module**: For sending critical alerts and data to ground stations or cloud servers.

[System Architecture Guidelines](SYSTEM_ARCHITECTURE.md)

## Installation

### Prerequisites

- [Python 3.8+](https://www.python.org/downloads/)
- [Xilinx PYNQ-Z2 Board](https://www.xilinx.com/products/boards-and-kits/1-vad8j4.html)
- [Vitis AI](https://www.xilinx.com/products/design-tools/vitis/vitis-ai.html)
- Required Python libraries (listed in `requirements.txt`)

### Setup Instructions

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/4Kapture-Ai-Co/DisasterShield-AI.git
   cd DisasterShield-AI
   ```

2. **Install Dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Setup FPGA Environment:**
   - Follow the instructions in the [PYNQ documentation](https://pynq.readthedocs.io/en/latest/getting_started.html) to set up your FPGA environment.

4. **Deploy AI Models:**
   - Use Vitis AI to deploy pre-trained models onto the FPGA.

## Usage

### Running the System

1. **Power on the Drone and FPGA:**
   - Ensure all sensors are connected and operational.
   
2. **Initiate Flight Mission:**
   - Pre-program the drone with desired flight paths and start the mission.
   
3. **Monitor Real-Time Data:**
   - The system will autonomously collect and analyze data. Alerts will be sent to the designated receivers upon detecting any anomalies.

4. **Post-Flight Data Analysis:**
   - Download and analyze collected data for further insights and model improvements.

## Applications

- **Disaster Prevention and Management**: Early warning for floods, droughts, and other natural disasters.
- **Environmental Monitoring**: Track ecosystem health and contribute to climate change research.
- **Agriculture**: Precision farming with soil moisture monitoring and crop health analysis.
- **Urban Planning**: Flood risk mapping and water resource management.

## Contributing

We welcome contributions to enhance DisasterShield AI. Please check the [Contributing Guidelines](CONTRIBUTING.md) for more details.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For any inquiries or support, please contact [Ryan Morales](mailto:ryanmorales9373@gmail.com).
