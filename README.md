# Particle Collision Simulation in a 2D Box

##  Project Overview
This project simulates the motion of multiple particles inside a 2D square container.  
The particles move with random initial velocities, and collisions with the container walls are detected and handled by reversing velocity components.  

The simulation is visualized in real time using **Matplotlib**, where particles are shown as moving points inside the container.  
The code also tracks and prints the **number of collisions per time step** along with the **average number of collisions**.

##  Features
- Real-time 2D animation of particles moving in a container.
- Collision detection with container walls (elastic collisions).
- Running calculation of:
  - Number of collisions per time step
  - Average number of collisions across the simulation
- Configurable parameters such as number of particles, speed, and container size.

##  Simulation Parameters
- **Number of particles:** 100  
- **Container size:** 10 × 10  
- **Time steps:** 1000  
- **Particle speed (initial):** 0.1 (randomized directions)  

You can adjust these values in the script under the **Constants** section.

##  How It Works
1. Particles are randomly placed inside the container with random initial velocities.
2. At each time step:
   - Positions are updated.
   - Collisions with walls are detected and velocity components are inverted.
   - The collision count is updated.
3. The simulation updates the particle positions on a scatter plot.
4. Collisions per time step and the running average are displayed in the console.

##  Example Output
During runtime, you will see:
- An animated scatter plot of particles bouncing within the container.
- Console output like:

