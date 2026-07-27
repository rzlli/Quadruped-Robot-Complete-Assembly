# Quadruped Robot Complete Assembly Project

## Overview
This repository contains the complete assembly project of a quadruped robot using Onshape. The project focuses on integrating pre-designed mechanical and electrical components, applying precise assembly mates, mounting servo motors, securing parts with fasteners, attaching the legs, and fitting the outer cover.

## Key Features
* Component Integration: Assembling all premade parts including the robot's main body, moving joints, and legs.
* Servo Motor and Hardware Assembly: Precise positioning and mounting of servo motors alongside structural fasteners and screws.
* Mechanical Mates: Applying accurate assembly constraints and surface matching to ensure stable movement and alignment.
* Shell Fitting: Proper alignment and offset positioning of the external protective cover over the fully assembled structure.
* Exploded Views: Step by step breakdown views illustrating how all components, joints, and fasteners fit and interact together.
* Engineering Outputs: Generated technical assembly drawings and PDF documentation.

## Tools Used
* Platform: Onshape
* Key Techniques: Assembly Mates, Exploded Views, Hardware/Servo Integration, and Technical Drawings.
------------------------------------------


### Engineering Design Report and Algorithmic Framework for a Quadruped Robot (Robot Dog)
#### 1. Technical and Engineering Specifications of the System
The design criteria for the robot were established to balance mechanical requirements with load-bearing capacity:
 * Target Total Weight: Ranging between 10 to 14 kilograms to ensure stability and maneuverability.
 * Geometrical Dimensions: Length (50–70 cm), Width (40 cm), and Height (40 cm).
 * Locomotion and Joint System: The robot relies on a quadruped structure, where each limb requires 3 Degrees of Freedom , totaling 12 actuators distributed across the hip, thigh, and knee joints.
 * Torque and Transmission System (Gearbox): Due to the robot's weight class (10–14 kg), high-torque actuators supported by planetary or harmonic gearboxes are utilized to multiply torque and withstand static and dynamic loads.
#### 2. Hardware Bill of Materials 
 * Actuators: High-torque digital servos or specialized quadruped actuator modules supporting fast communication protocols.
 * Central Controller: A micro-processing unit ,such as Raspberry Pi or Nvidia Jetson for managing high-level algorithms, coupled with a real time microcontroller ,such as Teensy or STM32 for precise PWM control signal generation.
 * Power System: A 6S Lithium Polymer battery (approx. 22.2V) with a capacity ranging between 5,000 to 10,000 mAh to ensure adequate current supply for the actuators and processors.
 * Sensors: An Inertial Measurement Unit for monitoring balance and acceleration, along with joint angle tracking sensors (encoders) integrated into each joint.
#### 3. Algorithmic and Methodological Steps for Design and Fabrication
 * Phase One: Initial CAD Modeling
   * 3D modeling of the main body frame and limbs using computer-aided design software (such as Onshape), adhering to the specified dimensions (50–70 cm length, 40 cm width, 40 cm height).
   * Precise distribution of centers of mass and allocation of mounting spaces for the battery and actuators to ensure stability during locomotion.
 * Phase Two: Fabrication and Material Selection
   * Fabricating the outer chassis using lightweight, high rigidity materials (such as Aerospace Aluminum 6061 or Carbon Fiber) or via 3D printing using durable engineering filaments such as PETG or Nylon to minimize overall weight and stay within the 10–14 kg range.
 * Phase Three: Mechanical and Electrical Assembly
   * Installing joint actuators and gearboxes securely into their designated positions within the legs with high engineering precision.
   * Connecting the power distribution board to the battery, routing actuator signal wires via the appropriate communication network, and mounting the sensors at the center of the robot's chassis.
 * Phase Four: Programming and Control Algorithms
   * Integrating Inverse Kinematics algorithms to accurately compute leg angles and step coordinates.
   * Programming the dynamic stabilization system relying on IMU sensor feedback to correct the robot's posture and ensure stability during movement.
