# synchronous_fifo_using_verilog
# Synchronous FIFO in SystemVerilog

## 📌 What is a Synchronous FIFO?  
A **Synchronous FIFO (First-In-First-Out) buffer** is a type of memory queue where data is written and read using the same clock signal. It follows the FIFO principle, meaning the first data written is the first data read.

## 🔹 Why is it Used?  
- **Data Buffering** → Stores data temporarily to handle speed differences between producer and consumer.  
- **Pipeline Stages** → Helps in smooth data transfer between processing units.  
- **Flow Control** → Uses **full** and **empty** flags to prevent data loss.  
- **Clock Synchronization** → Ensures reliable data transfer in a **single clock domain**.  

This project implements a **32-bit width, 8-entry depth synchronous FIFO** using **SystemVerilog**, along with a testbench for simulation and verification.  
![Image](https://github.com/user-attachments/assets/4a8167dc-ac25-465d-93f3-dd5cc7197873)
![Screenshot 2025-03-21 091446](https://github.com/user-attachments/assets/39b29aeb-9704-471e-9c63-cbd15010ef17)
