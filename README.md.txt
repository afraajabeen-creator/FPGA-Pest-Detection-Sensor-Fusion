# FPGA Based Real-Time Pest Detection Sensor Fusion Engine

## Project Idea

This project implements a real-time pest detection system using FPGA RTL design.
Camera pixel stream is processed using simplified Sobel edge detection and fused with environmental sensor signals such as humidity, temperature and spectral intensity.

## Working Principle

* Pixel stream processed sequentially
* Strong edges counted for full image frame
* Environmental sensor conditions checked
* Final pest detection decision generated

## Modules

* hacktronics.v → Top decision module
* sobel_simple.v → Edge detection module
* tb_compare.v → Simulation testbench

## Applications

Precision agriculture, smart farming, embedded vision accelerators.

## Author

Afraa Jabeen
B.Tech ECE | Interested in VLSI & Chip Design
