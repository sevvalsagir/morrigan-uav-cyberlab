# MORRIGAN: UAV Simulation & Cybersecurity Testbed

**Morrigan** is an open-source simulation and cybersecurity testing environment designed to emulate UAV (Unmanned Aerial Vehicle) communication systems. Developed with a focus on security research in autonomous systems, this project enables real-time analysis, protocol inspection, and adversarial testing against virtual drone communication.

The system is built around PX4 Autopilot and Gazebo simulator, integrating MAVLink-based telemetry with various security test modules, including replay attacks, spoofing, and denial-of-service scenarios.

Named after the Celtic goddess of war and prophecy, *Morrigan* reflects the duality of modern drone technology—powerful yet vulnerable—highlighting the necessity of robust defense mechanisms in autonomous aerial systems.

## Features

- Full UAV flight simulation with Gazebo and PX4
- Real-time MAVLink telemetry monitoring and interception
- Custom security testing modules for:
  - Packet sniffing and protocol inspection
  - Replay and spoofing attacks
  - DoS simulation on control channels
- Modular architecture for future integration of AI-based anomaly detection
- Designed for research, demonstration, and educational purposes

## Tech Stack

- Ubuntu 22.04 LTS
- PX4 Autopilot (SITL)
- Gazebo 11 Simulator
- MAVLink Protocol
- Python 3.x (Tooling and Attack Modules)
- Wireshark / Scapy for packet inspection
- QGroundControl for manual GCS interaction

## System Requirements

- VirtualBox or native Linux environment (recommended: Ubuntu 22.04)
- At least 8 GB RAM (16 GB preferred)
- 40 GB free disk space
- 2–4 CPU cores allocated for the virtual environment

## Getting Started

Follow these steps to set up the Morrigan simulation environment:

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/morrigan-drone-defender.git
cd morrigan-drone-defender
