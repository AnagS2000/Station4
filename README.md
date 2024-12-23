# Buddy Electrical Station 4 Automation Project

This project focuses on the automation of Station 4 (Exteriors) for the Buddy Electrical vehicle manufacturing process. The automation system is to be simulated in the **Automation Laboratory at Tecnológico de Monterrey**. The goal is to replicate the processes in Station 4 and simulate them using available laboratory equipment.

## Overview

A physical implementation was carried out in the **Automation Laboratory** at Tecnológico de Monterrey. **Station 4**, which handles exterior components of the car, was selected to be simulated at the facilities. The station includes several processes, such as AGV transportation and various installation tasks, which will be automated and monitored in real time.

### Station 4 Processes

The following processes are involved in Station 4 automation:

1. **AGV Transportation**: Automated Guided Vehicle (AGV) transports components within the station.
2. **Body Frame Installation**: Managed by two operators.
3. **Exterior Lights Installation**: Managed by one operator.
4. **Hood Installation**: Managed by one operator.
5. **Windshield Installation**: Managed by one operator.
6. **Doors Installation**: Managed by two operators.

Each of these processes is integrated into the simulation for optimization and efficiency analysis.

### RFID Sensor and HMI Integration

An **RFID sensor** is used to scan components when they are retrieved from the warehouse, providing confirmation that the process has started. The RFID sensor is simulated in the lab using a **button on the HMI**, representing that a component has been manually grabbed and scanned by the operator.

In addition to the RFID system, the station includes a **Human-Machine Interface (HMI)** that allows operators to:

- Mark task completion.
- Advance to the next process step in the correct sequence.
- Record quality checks for each process, indicating whether the outcome is good or bad.

The **Schneider Electric** and **Magelis** systems were used to program and manage the automation processes in Station 4.

### Simulation Details

#### Assumptions for Station 4 Simulation

Since there is no physical plant or actual RFID sensors available, the following assumptions were made:

1. **RFID Sensor Simulation**: The RFID sensor is simulated through a button on the HMI. When the button is pressed, it represents the manual retrieval and scanning of a component by the operator. The state of this button will be visualized in the simulation.
  
2. **Simulation of Physical Activities**: Physical activities are simulated using **single and double-effect pistons**. These pistons represent the actions of the operators. An **extended piston** signifies that an operation is in progress, while a **retracted piston** indicates that the operation has either not started or has been completed. Each piston is assigned to a specific process, and their statuses will be visualized.

3. **Quality Check**: After each process, a quality check is performed. The operator uses the HMI to indicate whether the quality of the operation is **good** or **bad**. These inputs are recorded and visualized in the simulation.

### Programming and Logic

The files uploaded to the repository were used for programming the **HMI** and the **ladder logic** for the **PLC**. These files contain the configuration and logic needed to control the simulated processes, including the handling of RFID sensors, operator tasks, and quality checks.

## Results

A video of the physical implementation of the project is available. You can view the implementation video at the following link:
[Implementation Video](https://drive.google.com/file/d/1w6d39z9hM3CSn1z_oVqoCSAur2E7vjz9/view?usp=sharing)

## Contact

For further inquiries or detailed information, please contact the project team:
- Ana Gabriela Sepulveda: [A01283682@tec.mx](mailto:A01283682@tec.mx)
- Enrique Villar: [A01658095@tec.mx](mailto:A01658095@tec.mx)
