## Hello world! This repository holds information about significant aerospace-related projects I have completed during my time at Iowa State and a bit before. These projects range from 2021-2026. 
## UAV Design
## Lunar Orbiter Mission
## Technical Instruction Writing
## Aircraft Conceptual Design
## Solidworks Aircraft Replica
## Python Orbital Mechanics
## Airship Research Projects


# UAV Design  
**OpenUAS Research Team (2025–Present)**  
**Role:** Design Team Member; Design Team Lead (in training)

## Project Objective
I currently work with a team of around 30 undergraduate and graduate students to create a configurable, open-source, 3D-printable aircraft at Iowa State University.

## Processes
I work on iterating future designs of our plane and implementing edits requested by the Manufacturing Subteam for our current design. I primarily work with **SolidWorks**, **Computational Fluid Dynamics (CFD)** simulations such as **Star-CCM**, and **XFLR5** airfoil analysis as we iterate our aircraft.

We are constantly improving our previous year’s designs, such as *Pluma*, and creating new models by running our designs through drag analysis simulations and referencing existing aircraft. I have designed and led teammates in optimizing:

- Fuselages  
- Wings  
- Tail assemblies  
- Internal aircraft structures with Design for Manufacturing (DFM) considerations  

As a team, we are currently writing a research paper for the **AIAA Conference** hosted at Iowa State University.

## Individual Task Spotlight
One major issue we encountered was the wingspan and chord length of the aircraft’s main wing. We are limited by the bed size of the 3D printer while still needing sufficient structural integrity for flight.

I was responsible for:
- Selecting wing break locations for 3D printing  
- Editing the fuselage for electrical access  
- Maintaining an adjustable center of gravity  

### Wing Break
I collaborated with the Manufacturing Subteam to confirm printer constraints. The initial wing chord was unprintable, so I adjusted the **aspect ratio**, reducing chord length while increasing span to maintain the same lift coefficient.

Re-running drag analysis showed negligible increases in profile drag. Once approved, I edited the model considering:

- Aerodynamic forces  
- Propeller forces (one propeller per wing, aligned with the chord ~1/3 down the span)

Each wing was split into two printable sections:
- **Inner wing:** Fuselage connection and motor mount to handle high stresses  
- **Outer wing:** Ailerons, connected via two spars  

This design minimizes structural discontinuities while allowing airfoil configurability.

### Fuselage
I led the transition from a solid fuselage to a shelled design capable of housing electronics. Key decisions included:

- A top-mounted access door  
- Improved manufacturability and accessibility  
- Increased safety during battery failures  
- Reduced drag from fewer external hinges  

This resulted in a simpler, sleeker, and safer fuselage.

## Team Challenges
The OpenUAS team operates at a fast pace, making requirement definition difficult. We are working to:

- Reference NASA-style documentation standards  
- Create replicable and well-documented processes  
- Ensure designs are accessible to outside contributors  

## Results
I was selected to train as the next **Design Team Lead** due to my contributions during my first semester.

The current aircraft iteration:
- Is aerodynamically stable  
- Minimizes drag  
- Builds directly on prior designs  

---

# Lunar Orbiter Mission  
**AERE 3510 (Fall 2025)**  
**Role:** Research Lead; Code Contributor; Paper Lead

## Project Objective
Design a conceptual mission to send a spacecraft from low Earth orbit to lunar orbit, including all impulse vectors and angular constraints, presented using MATLAB simulations.

## Team Processes
I proposed investigating **lunar lava tubes** using radar instrumentation. I researched existing missions to define realistic initial parameters.

The mission placed a radar-equipped satellite into a circular lunar orbit using:
- Orbital perturbations  
- An initial plane-change maneuver  

### MATLAB Code Structure
The code consisted of four sections:
1. Orbit altitude evaluation  
2. Time-of-flight calculations  
3. Δv calculations  
4. Optimization of initial conditions  

I authored the first section, calculating:
- Angular momentum  
- Orbital altitudes and velocities  
- Transfer orbit eccentricities  
- Sphere-of-influence constraints  

## Challenges
The entire project (MATLAB code, 20-page paper, presentation) was completed in **one week**. I created paper outlines early to streamline integration.

## Results
- Launch duration: **3.7 days**  
- Lunar inclination changes: **~3.6 years**  
- Mission lifespan met realistic satellite constraints  

---

# Technical Instruction Writing  
**ENGL 3140 (Spring 2025)**

## Project Objective
Design a paper airplane demonstrating aerodynamic principles and write instructions at a fifth-grade reading level, tested by real students.

## Processes
The aircraft demonstrated:
- Steering surfaces (ailerons, flaps)  
- Center of gravity effects  

I simplified language through iterative drafts, parenthetical definitions, and readability analysis tools.

## Challenges
Explaining technical concepts to a non-technical audience while maintaining engagement.

## Results
Student feedback was primarily green and yellow, confirming clarity and accessibility.

---

# Aircraft Conceptual Design  
**AERE 2610 (Spring 2025)**  
**Role:** SolidWorks Lead; Wing Design; Moment Balancing Code; Research Contributor

## Project Objective
Complete a conceptual aircraft design for sub-Mach 0.3 flight.

## Processes
I proposed a twin-engine, high-wing, T-tail configuration and led:

- Wing aspect ratio calculations  
- Wing and tail design in SolidWorks  
- Lift and drag validation using XFLR5  
- MATLAB and Excel data visualization  

## Challenges
MATLAB errors caused by mixed unit systems were resolved through hand calculations.

## Results
- Aircraft range: **15,061.7 km**  
- Required mission range: **5,536 km**  

---

# SolidWorks Aircraft Replica  
**AERE 1610 (Spring 2024)**  
**Role:** SolidWorks Lead; Team Mentor; Presentation Lead

## Project Objective
Accurately model an existing aircraft in SolidWorks.

## Processes
I selected the **Airbus Beluga XL** and established image-based scaling using known wing length.

## Challenges
- Self-intersecting surfaces during nose lofting  
- Mentoring first-year students  

## Results
- Fully modeled aircraft  
- Animated opening fuselage  
- Realistic skins and branding  

---

# Python Orbital Mechanics  
**AERE 1600 (Fall 2023)**

## Project Objective
Simulate a rocket launch and planetary fly-by using Python.

## Processes
Used nested loops and conditionals to animate trajectory and visualize gravity effects.

## Challenges
- Debugging a 100+ line script  
- Defining fly-by parameters through iteration  

## Results
Sparked long-term interest in orbital mechanics and spaceflight simulation.

---

# Airship Research Projects  
**IDSEF (2021–2023)**

## Project Objective
Investigate airship efficiency and environmental benefits compared to drones.

## Processes
Built and tested two airships using RC helicopter and drone components, custom balsa frames, and helium balloons.

## Challenges
- Rapid helium deflation  
- Custom buoyancy fabrication  

## Results
- More than doubled motor endurance  
- Published a research paper  

### Awards
- Mu Alpha Theta Award (Mathematics)  
- 2nd place in division (both years)  
- Recognition from the Air Force Science Fair Program  
