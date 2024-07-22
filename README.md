# PLC-Based Waste Sorting System for Smart Cities

<p align="justify">
The PLC-Based Waste Sorting System for Smart Cities is designed to automate the sorting of waste materials using Programmable Logic Controllers (PLCs). This project enhances the efficiency of waste management in smart cities by integrating advanced sorting technologies and methodologies. By leveraging the principles of the 3R (Reduce, Reuse, Recycle) and 5R (Reduce, Reuse, Recycle, Recovery, Disposal) concepts, this project aims to minimize waste, maximize resource recovery, and promote sustainable practices. The system classifies and sorts various types of plastics and metals using sensors and air jet solenoids, ensuring precise and effective waste segregation.
</p>

## Key Features & Stages

### 1- Waste Classification and Sorting:

- **Plastic Sorting:**

    - Classifies plastic containers into three categories (Clear, Natural, Opaque) based on their electromagnetic properties.

    - Utilizes analog plastic sensors to measure and classify the plastic objects.

- **Metal Sorting:**

    - Differentiates between ferrous (steel and iron) and non-ferrous (copper and aluminum) materials.

    - Employs analog metal sensors for precise classification.

### 2- Sensor Integration and Data Processing:

- **Electromagnetic Radiation Detection:**

    - Uses electromagnetic radiation to penetrate plastic and metal objects.

    - Analog sensors receive the propagated signals, which are fed into PLC analog-to-digital (ATD) channels for processing.

- **Sensor Readings and Averaging:**

    - Collects multiple sensor readings over a specified time period (2 seconds for plastics, 1 second for metals).

    - Averages the readings to ensure accurate classification.

### 3- Automated Sorting Mechanism:

- **Air Jet Solenoids:**

    - Activates specific air jet solenoids based on the classified object type to direct it to the appropriate sorting bin.

    - Ensures continuous operation and sorting efficiency.

- **Conveyor Belt System:**

    - Moves objects through the sorting areas.

    - Integrates start (ON) and stop (OFF) buttons with corresponding indicators (green light for ON, red light for OFF).

### 4- System Indicators and Controls:

- **Indicator Lights:**

    - Displays system status with green (system ON) and red (system OFF) lights.

- **Full Container Indicators:**

    - Activates container full indicators when the sorting bins reach their capacity.

    - Disables related air jets to prevent overflow.

### 5- Implementation of Advanced Sorting Concepts:

- **3R and 5R Principles:**

    - Integrates waste management strategies to reduce, reuse, recycle, recover, and dispose of waste efficiently.

- **Profibus and Profinet Integration:**

    - Utilizes Profibus and Profinet for digital input/output (DI/DO) connections, enhancing communication and control within the system.

## System Design & Implementation

### System Diagram

<div align="center">
  <img src="https://drive.google.com/uc?export=view&id=17pDojKPZixbRmxck8lOyYhnR9CxDDSwg" alt="System Diagram" />
</div>

### Main Configuration

<div align="center">
  <img src="https://drive.google.com/uc?export=view&id=1xojf1z-RWoYCpm6hes4anArNXsamBdj5" alt="Main Configuration" />
</div>

### Main PLC Unit Configuration

<div align="center">
  <img src="https://drive.google.com/uc?export=view&id=1c6i0feL0MyUbSh6uBKROAjN3F-cmxvLq" alt="Main PLC Unit Configuration" />
</div>

### Profibus PLC Unit Configuration

<div align="center">
  <img src="https://drive.google.com/uc?export=view&id=1CmesZJr1tj_emA0nmJiZmLM0b8nlXHm5" alt="Profibus PLC Unity Configuration" />
</div>

### Profinet PLC Unit Configuration

<div align="center">
  <img src="https://drive.google.com/uc?export=view&id=1A5XbjMN7FZxWvg9PkXNUpPt29WYub2FX" alt="Profinet PLC Unit Configuration" />
</div>

### Network Configuration 

<div align="center">
  <img src="https://drive.google.com/uc?export=view&id=1CU2Hlc4lBsX24RGtSXNZBmjk_XPsOYJ5" alt="Network Configuration" />
</div>

### Symbol Table

<div align="center">
  <img src="https://drive.google.com/uc?export=view&id=10b6wVT1708ofMS7P3x1v-P8TjU0_AKfH" alt="Symbol Table" />
</div>

### System Simulation Interface

<div align="center">
  <img src="https://drive.google.com/uc?export=view&id=1hIERP3NpuWNoxqBcHJMm33X8rPtK2FDB" alt="System Simulation"/>
</div>

## Installation & Setting Up the Project

#### 1- Download Siemens Step 7 Software:

#### 2- Download the Repository.

#### 3- Open Siemens Step 7.

#### 4- Open the Project.

#### 5- Review and Configure Hardware Settings.

#### 6- Check Network Settings.

#### 7- Set Up the Simulator.

#### 8- Download to Simulator

#### 9- Run and Monitor the Simulation.

## Contact for Support

For any queries or support related to this project, feel free to contact me at ibrahimsaffarini2001@gmail.com.
