# UART-Verification-using-System-Verilog
This project designs and verifies a UART communication protocol using System Verilog, featuring a UVM-like testbench for automated, reliable data transmission and reception verification.


This project focuses on designing and verifying a Universal Asynchronous Receiver Transmitter (UART) communication protocol using SystemVerilog. It implements both transmitter and receiver modules with configurable baud rates to enable flexible serial communication. A UVM-like verification environment is developed consisting of a Generator, Driver, Monitor, Scoreboard, and Interface — all connected via mailboxes for synchronized and automated testing.

The verification ensures correct end-to-end data transmission and reception using a self-checking testbench, reducing manual effort. Simulation results on EDA Playground confirm successful data exchange and validate the functionality of the UART protocol. The project demonstrates a modular, reusable, and scalable verification framework applicable to other communication interfaces like SPI or I²C.
