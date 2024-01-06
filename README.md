# ant_man - Ant Pheromone Trail Simulation

## Introduction


https://github.com/Eeman1113/ant_man/assets/54275491/4f82842e-cdcd-4974-9ba3-0a8a8a4d46e9


NAnts is a simulation of ant behavior using pygame in Python. The simulation includes features such as ant movement, pheromone trails, food seeking, and nest navigation. This readme provides an overview of the code structure, key components, and logic.

## Getting Started

### Prerequisites

- Python 3
- pygame library

```bash
pip install pygame
```

### Running the Simulation

1. Clone the repository:

```bash
git clone https://github.com/Eeman1113/Esoteric_Languages_Adventures.git
```

2. Navigate to the project directory:

```bash
cd Esoteric_Languages_Adventures
```

3. Run the simulation:

```bash
python nants.py
```

## Code Explanation

### Key Components

1. **Ant Class (`Ant`):**
   - Represents an ant in the simulation.
   - Ants have various behaviors such as random wandering, food seeking, and nest navigation.
   - Uses pygame for drawing and updating ant positions.

2. **PheroGrid Class (`PheroGrid`):**
   - Represents the pheromone grid that ants leave behind.
   - Pheromones decay over time and affect ant behavior.
   - The class uses pygame to update and display the pheromone grid.

3. **Food Class (`Food`):**
   - Represents food items in the simulation.
   - Ants seek out and pick up food.

### Simulation Logic

1. **Ant Behavior:**
   - Ants exhibit random wandering until they encounter food or the nest.
   - Pheromone trails are left behind by ants as they move.
   - Ants follow pheromone trails when seeking food and returning to the nest.

2. **Pheromone Trails:**
   - Pheromone levels decay over time.
   - Ants reinforce pheromone trails when seeking food and returning to the nest.

3. **Food Seeking:**
   - Ants detect the presence of food based on color.
   - When finding food, ants either follow their own trail back to the nest or head towards the nest.

4. **Nest Navigation:**
   - Ants navigate towards the nest using pheromone trails.

5. **Wall Avoidance:**
   - Ants avoid walls by adjusting their direction when wall colors are detected.

### User Interaction

- Left-clicking on the simulation window spawns food items.
- Right-clicking on a food item picks it up.

### Fullscreen vs. Window Mode

- The simulation can run in fullscreen or windowed mode based on the `FLLSCRN` variable.

## Acknowledgments


- Icons and images used in the simulation may be missing or are optional (nants.png, background.png).

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Conclusion

ant_man provides a simple yet interesting simulation of ant behavior. Users can observe how ants interact with their environment, leaving pheromone trails and seeking food. The code is well-documented and can be easily extended or modified for experimentation and learning purposes.
