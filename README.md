# Railtrack-management-system

The provided code sets up a comprehensive railway system simulation, which includes several critical functionalities for managing and operating a railway network. The core components of this system are:

## Description

* Graph Construction: Manages the network of tracks between stations, where each track has a start and end station and a weight (distance).

* Train Scheduling: Uses Dijkstra's algorithm to calculate the shortest paths between stations and determine optimal train routes, considering track conditions.

* Track Maintenance Scheduling: Allows scheduling and executing maintenance tasks based on priority, ensuring tracks are kept in good condition.

* Train Performance Monitoring: Tracks and updates performance metrics (speed and delay) for multiple trains and calculates average speed and delay.

* Real-Time Tracking: Maintains and retrieves the current positions of trains within the network.

* Track Condition Monitoring: Updates and checks the condition of tracks, ensuring that trains avoid tracks under maintenance.

* Platform Management: Calculates the minimum number of platforms required at a station based on train arrival and departure times.

Overall, this system integrates route optimization, maintenance management, performance tracking, and real-time monitoring to provide a robust framework for efficient railway operation and planning.

## Features:

* Train routing with Dijkstra
* Track condition monitoring
* Real-time tracking
* Performance monitoring
* Maintenance scheduling
* Platform requirement calculator

### How to Run

```bash
python3 code.py
```
