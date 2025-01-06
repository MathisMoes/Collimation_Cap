# Collimation_Cap

The goal of this project is to design a cap placed between the particle source and the chip with two main objectives:

1. Reduce the hit rate of emitted particles to facilitate better analysis of error dynamics.
2. Focus the emitted particles on specific regions of the chip using a collimation feature to direct the particle flow.

A Python program has been developed to allow users to define the target area and hit radius on the chip. The program calculates the ideal dimensions and placement of cylindrical holes in the cap to achieve the desired collimation effect.

Key Features of the Program:
1. Define Hit Targets on the Chip:

The user can either define a cylinder on their own and simulate the collimation, or specify the hit radius and coordinates for each target region on the chip within the code. This allows precise control over where the particles should be focused.

2. Calculate Ideal Aperture Parameters:

Based on the specified source-cap distance, the code calculates the optimal dimensions and placement for cylindrical apertures in the cap. These apertures are critical for controlling the direction and focus of the emitted particles. The program also visualizes the setup, allowing users to easily see the arrangement of the apertures.

3. Simulate Setup and Optimize Hit Rate:

The program simulates the configuration, calculating the expected number of particle hits for each individual aperture. It then sweeps over a range of source-cap distances (from 0.5 cm to 3 cm for instance) to determine the optimal distance that achieves a target hit rate of approximately one particle per 10 seconds for each designated target region on the chip.

In summary, the program automates the process of designing a particle collimation cap by allowing users to specify target regions on the chip, calculate the ideal aperture dimensions, and simulate various configurations to achieve the desired particle hit rate for each region. This setup provides a controlled environment for particle-based experiments while reducing error rates and ensuring precision in particle targeting.
