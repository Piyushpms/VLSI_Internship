COMPANY NAME : CODTECH IT SOLUTION

NAME : Piyush Mahesh Sharma

INTERN ID : CT08IPC

DOMAIN : VLSI

BATCH DURATION : January 5th, 2025 to February 5th, 2025

MENTOR NAME : NEELA SANTOSH

RAM DESIGN
Introduction and Overview 
In modern digital systems, Static Random-Access Memory (SRAM) is widely used for high-speed data storage. For this project, I designed a simple 4x4 SRAM module using Verilog, a hardware description language. The module was simulated to validate its functionality and understand how read and write operations are handled in a memory array. This project gave me deeper insight into how memory operations are controlled, and it helped improve my understanding of digital logic design. 
RTL Design Overview 
The SRAM design focuses on two main operations: 
1.	Write Operation: When the write enable (we) signal is high, data is written to the specified memory location. 
2.	Read Operation: When we is low, data is read from the memory location and presented on the data_out signal. 
img1
             
The module uses a clock signal (clk) for synchronization, ensuring memory operations occur at the correct time. The design allows for simple and efficient control of memory access.
Waveform Analysis and Simulation 
The simulation of the design helped validate the functionality of the SRAM module: 
•	During write operations (we = 1), data is stored at the specified memory address, but the data_out remains unchanged. 
•	During read operations (we = 0), data_out reflects the value stored at the specified memory address. 
img2 
The waveform analysis confirmed the correct behavior of the SRAM, with proper synchronization of the signals.![ram1](https://github.com/user-attachments/assets/5b1b1d00-b603-46a7-be57-d04f6e24c3a8)
