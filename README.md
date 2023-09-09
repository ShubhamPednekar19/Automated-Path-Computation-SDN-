# Automated-Path-Computation-SDN-

## Overview
Designed and implemented a custom network topology consisting of 10 nodes with diverse link delays (1ms - 5ms) and 50Mb bandwidth using Mininet and RYU controller.

Developed a RYU controller program to automatically discover the network topology, calculate link costs based on traversed time, and compute optimal paths for all host pairs.

Implemented user interaction for dynamic connection requests, considering source, destination, service type (IPv4 or MAC), and bandwidth (1-5Mb). Generated and applied configuration updates on intermediate switches along the path.

## Demo
Output after network discovery

![image](https://github.com/ShubhamPednekar19/Automated-Path-Computation-SDN-/assets/83055678/0341c003-328e-4cbf-8a89-0f72710eb797)

Command to run on Mininet
![image](https://github.com/ShubhamPednekar19/Automated-Path-Computation-SDN-/assets/83055678/e9ddb48e-01fa-433e-a400-a232d43c0dda)

For all pairs shortest paths I created ShortestPath.py which when run using ryu-manager alongside mininet gives all pairs of mac-addresses and the shortest path between them. A sample output is-
![image](https://github.com/ShubhamPednekar19/Automated-Path-Computation-SDN-/assets/83055678/51ce5fa0-0003-41ad-9eba-e351760eda33)


