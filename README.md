# Traffic Management System

A **Python-based simulation project** designed to intelligently manage vehicle traffic on multiple roads using logic-based control. The system mimics real-world traffic scenarios by dynamically assigning green signals to the busiest roads and controlling vehicle flow in a round-by-round manner.

---

## Features

- **Simulates Four Roads:** North, East, South, and West lanes are actively monitored.
- **Random Vehicle Arrival:** Vehicles arrive randomly on each road to simulate real-world traffic patterns.
- **Dynamic Signal Control:** Detects the road with the highest traffic and assigns a green signal accordingly.
- **Adjustable Vehicle Clearance:** Clears a fixed number of vehicles per round; the number of vehicles cleared can be configured.
- **Real-Time Console Updates:** Prints detailed updates for each round including vehicle count, signal changes, and cleared vehicles.
- **Traffic Flow Optimization:** Ensures fair and efficient distribution of green signals to reduce congestion.
- **Round-Based Simulation:** Traffic flow is controlled in rounds to mimic time-based traffic light cycles.
- **Scalable Design:** Can be extended to more roads or complex intersections in the future.

---

## Technologies Used

- **Python 3** – Main programming language for logic and simulation.
- **Random module** – To simulate random arrival of vehicles.
- **Time module** – To add delays between rounds, simulating real-time traffic updates.
- **Logic-Based Control** – To dynamically prioritize roads with maximum traffic.

---

## How It Works

1. Each road maintains a queue of vehicles waiting at the signal.
2. Vehicles arrive randomly on each road during each simulation round.
3. The system detects the road with the **most vehicles** waiting.
4. The green signal is assigned to that road for the round.
5. A fixed number of vehicles are cleared from the green signal road.
6. The round ends, and the system prints the status of all roads.
7. The next round begins with updated vehicle queues, repeating the process.

---

## Benefits

- Helps visualize **traffic flow management** in a simplified environment.
- Demonstrates **algorithmic decision-making** for resource allocation (green signal).
- Useful as a **learning tool** for Python programming, simulations, and logic-based control systems.
- Can be extended to include **real-time sensor input** or **GUI visualization**.
