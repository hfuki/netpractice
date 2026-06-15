*This project has been created as part of the 42 curriculum by hfuki.*

# Net-Practice

## Project Overview
**Net-Practice** is a networking project at **42**. The goal is to master the mechanics of TCP/IP addressing, subnetting, and routing by solving 10 networking puzzles through a web-based simulator.

## Instructions
To run the networking simulator locally:

1. Run the provided shell script:
   ```bash
   bash run.sh
   ```
2. Open your web browser and navigate to the URL shown in the terminal (usually `http://localhost:49242`).

### Solving and Submission
1. Follow the instructions on each level to configure the network interfaces and routing tables.
2. Once a level is solved, click the **"Get my config"** button to download the configuration as a `.json` file.
3. To fulfill the project requirements, you must place all 10 solved configuration files (e.g., `level_1.json`, `level_2.json`, etc.) directly at the **root** of your repository for submission.

## Resources
### Networking Concepts
The project covers the following fundamental concepts:
- **IPv4 Addressing:** Understanding octets and address structures.
- **Subnet Masks & CIDR:** Calculating network ranges and using CIDR notation.
- **Default Gateway:** Configuring the exit point for packets leaving a subnet.
- **Routing & Switching:** Differentiating between device communication within the same network (Switch) and across different networks (Router).
- **OSI Layers:** Understanding the context of networking protocols within the OSI model.

### AI Usage
AI was utilized during this project for the following tasks:
- **Documentation Structure:** Assisted in organizing and formatting the README to meet specific project guidelines.
- **Logic Review:** Used to verify networking logic and double-check CIDR calculations for complex scenarios.
- **Troubleshooting:** Provided guidance on setting up the local environment and resolving script execution issues.
