Network-on-Chip (NoC) Simulator

This project involves the development of a Network-on-Chip (NoC) simulator using SystemC, a versatile hardware description language designed for modeling and simulating System-on-Chip (SoC) designs. The simulator aims to replicate the communication framework of NoC architectures, which are essential for efficient data transfer among processing elements in multi-core processors.

- Features
  
  - Modular Design:
    - Source Module: Generates packets with attributes like data payload, source and destination IDs, and timing to simulate real-world packet generation.
    - Sink Module: Records incoming packet information for analyzing packet delivery and latency.
    - Router Module: Manages packet routing based on destination addresses using sub-modules like FIFO buffers, crossbars, and arbiters.
      
  - Simulation Environment:
    - Define module interfaces and establish connections between modules.
    - Configure simulation parameters such as packet size, network topology, and routing algorithms.
      
  - Performance Evaluation:
    -Run simulations with different configurations to evaluate throughput, latency, power consumption, area utilization, and other performance metrics.
    
- Goals
  - Gain hands-on experience in designing and analyzing on-chip communication systems.
  - Understand the behavior and performance characteristics of NoC architectures through simulation and analysis.
