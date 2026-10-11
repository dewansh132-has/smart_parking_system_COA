# Smart Parking Management System

## Introduction

The **Smart Parking Management System** is a digital hardware-based project that aims to manage parking spaces automatically. The system will be designed and simulated using **Logisim** and will use different concepts from Computer Organization and Architecture such as logic gates, combinational and sequential circuits, registers, counters, multiplexers, encoders, decoders, comparators, and control units.

The system will simulate a real parking area where vehicles can enter and exit, parking slots can be assigned automatically, the availability of slots can be checked, and important information can be shown using digital displays. The main aim is to understand how these COA concepts can work together to solve a real-world problem using digital hardware.

## Major Components and Contributions

The project will include the following features:

- **Multiple Parking Slots:**  
  The system will have multiple parking slots, such as 8 slots. Each slot will have an occupied or vacant status, which will be shown using LEDs.

- **Parking Slot Status Storage:**  
  Registers and flip-flops will be used to store the status of each parking slot. The status will change whenever a vehicle enters or leaves.

- **Automatic Slot Allocation:**  
  When a vehicle enters, the system will check the available slots and automatically assign a vacant slot.

- **Entry Control:**  
  Before allowing a vehicle to enter, the system will check whether a parking slot is available. If the parking area is full, entry will not be allowed.

- **Exit Control:**  
  When a vehicle leaves, the selected parking slot will be marked as vacant and the parking count will be updated.

- **Vehicle Counters:**  
  Counters will be used to keep track of the number of vehicles entering and leaving the parking area.

- **Available Slot Counter:**  
  The system will maintain the number of currently available parking spaces and update it after every valid entry or exit.

- **Parking Full and Empty Detection:**  
  The system will detect both full and empty parking conditions. When all slots are occupied, a **"PARKING FULL"** indication will be shown. Similarly, invalid exit operations will be prevented when there are no vehicles in the parking area.

- **Digital Display:**  
  Seven-segment displays will be used to show information such as the number of available and occupied slots and other relevant values.

- **Parking Fee Calculation:**  
  A simple hardware-based fee calculator will be included. The parking fee will be calculated according to the simulated parking duration using counters, comparators, and logic circuits.

- **Reserved Parking Slots:**  
  Some slots will be marked as reserved. The automatic allocation system will avoid assigning these slots during normal parking operations.

- **Invalid Operation Detection:**  
  The system will detect invalid operations such as trying to enter when the parking area is full, trying to exit when it is empty, or trying to occupy a slot that is already occupied.

- **Control Unit:**  
  A central control unit will manage the different operations of the system, including entry, exit, slot allocation, counter updates, fee calculation, and display control.

- **Multiplexers and Selection Logic:**  
  Multiplexers will be used to select information from different parking slots and send the required data to the processing or display sections.

- **Encoders and Decoders:**  
  Encoders and decoders will be used for identifying and selecting parking slots and for handling the required digital information.

- **Comparators and Decision Logic:**  
  Comparators will be used to check parking conditions such as full/empty status and to help determine the parking fee based on the parking duration.

- **Reset Mechanism:**  
  A reset input will be provided to return all parking slots, counters, registers, and displays to their initial state.

- **Testing:**  
  Different situations will be tested, including multiple vehicle entries and exits, full parking, empty parking, reserved slots, invalid operations, and different parking durations.

## Novelty and Practical Feasibility

The main idea of this project is to implement a **real-world parking management system using digital hardware instead of depending on software or a microcontroller**. It will show how inputs can be received, stored, processed, and converted into useful outputs using digital circuits.

The project will be designed in a modular way, so each part such as slot management, counters, fee calculation, and display can be developed and tested separately before combining everything into the final system. The system can also be extended in the future by adding features such as multiple parking floors, different parking zones, vehicle identification, or more advanced authorization.

The project is practically feasible because it will be completely designed and simulated using **Logisim**. Switches can be used to represent vehicle and sensor inputs, while LEDs, registers, counters, and seven-segment displays can represent the system outputs.

Overall, this project will provide a practical application of important **Computer Organization and Architecture concepts** by combining digital logic, memory elements, counters, control logic, and display systems into a single working system.
