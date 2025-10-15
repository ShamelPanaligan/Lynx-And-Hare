This project implements an agent-based simulation modeling the predator-prey dynamics between lynxes (predators) and hares (prey) in a 2D ecosystem.
The simulation demonstrates classic population cycles where predator and prey populations oscillate in response to each other.

Simulation Rules:
Hunting Mechanics
- Lynxes check adjacent cells for hares
- Successful hunts (30% chance) restore lynx energy and remove hares
- Each lynx can hunt only once per time step

Starvation System
- Lynxes lose 2 energy units each time step
- Lynxes die when energy reaches zero
- Successful hunting resets energy levels

Reproduction
- Hares: 30% chance to reproduce into adjacent empty cells
- Lynxes: 20% chance to reproduce into adjacent empty cells
- Reproduction occurs only when suitable empty adjacent cells are available


The simulation demonstrates classic predator-prey oscillations:
- High hare populations enable lynx population growth
- Increasing lynx populations reduce hare populations through predation
- Declining hare populations lead to lynx starvation and population decline
- Reduced lynx populations allow hare populations to recover

Visualization
The simulation includes:
- Grid-based display showing animal positions
- Population tracking over time

Matplotlib visualization of population cycles
