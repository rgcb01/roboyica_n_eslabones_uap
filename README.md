# n-Link Robot Dynamics with Lagrange–Euler (MATLAB)

A MATLAB-based engineering project for symbolic dynamic modeling of serial robotic manipulators with an arbitrary number of links. The model uses Denavit–Hartenberg (D–H) parameters and the Lagrange–Euler formulation to derive the kinematic and dynamic quantities required for motion analysis.

> **Focus areas:** Robotics · Dynamic modeling · MATLAB · Symbolic computation · Mechanical systems

## Project Overview

This project was developed as part of a Mechatronics Engineering robotics course. Its purpose is to provide a reusable framework for analyzing an **n-link serial robot**, rather than a single fixed mechanism.

Given user-defined robot parameters, the MATLAB Live Script calculates:

- Kinematic relationships based on Denavit–Hartenberg parameters
- Link center-of-mass motion
- Kinetic energy of the mechanism
- Gravitational potential energy
- Joint torque expressions using the Lagrange–Euler method

The workflow can support different serial manipulator configurations by updating the robot's geometric, mass, inertia, and joint variables.

## Engineering Problem

Robotic manipulators require torque estimates to select actuators, evaluate motion profiles, and understand how gravity, inertia, and link geometry affect performance. Manually deriving these equations becomes increasingly complex as the number of links increases.

This project automates that symbolic derivation in MATLAB, making it easier to study and adapt the model for multiple robot configurations.

## Technical Approach

1. Define the robot geometry using **Denavit–Hartenberg parameters**.
2. Define symbolic joint variables, link masses, inertias, and gravity.
3. Compute the position and velocity of each link's center of mass.
4. Calculate total kinetic energy and potential energy.
5. Form the Lagrangian: \( L = T - V \).
6. Apply the Lagrange–Euler equation to obtain the required torque for each joint.

## Repository Contents

| File | Description |
| --- | --- |
| `Lagrange_Euler_Para_N_Eslabones.mlx` | MATLAB Live Script containing the symbolic dynamic analysis for an n-link robot. |
| `README.md` | Project documentation, scope, requirements, and execution instructions. |

## Requirements

- MATLAB R2021a or later recommended
- Symbolic Math Toolbox
- Basic familiarity with serial manipulator kinematics and D–H notation

## How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/rgcb01/roboyica_n_eslabones_uap.git
   ```

2. Open MATLAB.
3. Open `Lagrange_Euler_Para_N_Eslabones.mlx`.
4. Update the manipulator parameters and symbolic variables as needed.
5. Run the sections of the Live Script to generate the energy and torque expressions.

## Inputs and Outputs

**Typical inputs**

- Number of robot links
- D–H parameters
- Link lengths and center-of-mass locations
- Link masses and inertia matrices
- Joint positions, velocities, and accelerations
- Gravity vector

**Typical outputs**

- Symbolic kinetic-energy expression
- Symbolic potential-energy expression
- Lagrangian formulation
- Joint torque equations for the defined robot model

## Skills Demonstrated

- Mathematical modeling of robotic systems
- MATLAB Live Scripts and symbolic programming
- Denavit–Hartenberg parameterization
- Lagrange–Euler dynamics
- Mechanical system analysis
- Technical documentation

## Future Improvements

- Add a worked example for a 2-link planar arm
- Export example torque plots and simulation results
- Add a diagram of the robot coordinate frames
- Compare symbolic results with a numerical simulation
- Include unit tests or validation cases for a known configuration

## Author

**Rómulo Giancarlo Colorado Balboa**  
Mechatronics Engineer — Automation, Robotics, Computer Vision, and Manufacturing Engineering  
[LinkedIn](https://www.linkedin.com/in/rgcb/)

## License

This project is shared under the MIT License.