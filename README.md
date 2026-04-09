# Design and System-Level Validation of an 18-Transistor Full Adder

This project presents the design, simulation, and system-level validation of a compact **18-Transistor (18T) Full Adder** developed using a **truth-table-based synthesis approach**. The proposed design reduces transistor count compared to conventional 28T full adders while maintaining correct logical functionality and stable signal operation.

This work has been **accepted at IEEE International Conference on Intelligent Systems for a Sustainable Future (ISSF 2026)**.

---

##  Project Overview

Full adders are fundamental building blocks in digital arithmetic systems. Conventional CMOS full adders typically require 28 transistors, increasing circuit complexity and power consumption. This project introduces an optimized **18-transistor full adder architecture**, designed to improve compactness while maintaining reliable arithmetic operation.

The proposed design was validated at both:

- **Circuit Level** using Cadence gpdk 90 nm simulations  
- **System Level** using a MATLAB-based fingerprint matching framework  

The full adder was used to perform **popcount operations**, which are essential for computing **Hamming distance** in binary similarity applications.

---

##  Key Features

- Designed a **compact 18-transistor full adder**
- Reduced transistor count compared to conventional **28T full adder**
- Verified correct **Sum and Carry outputs** for all input combinations
- Demonstrated stable operation within defined **logic noise margins**
- Integrated into **MATLAB-based fingerprint matching system**
- Used for **popcount computation** in Hamming distance calculation
- Compared performance with conventional full adder architectures
- Evaluated delay and power characteristics

---

##  Methodology

The proposed full adder design was developed using:

1. **Truth-table-based logic synthesis**
2. **Complementary Pass Transistor Logic (CPL) implementation**
3. **Cadence gpdk 90 nm simulation**
4. **MATLAB system-level validation**
5. **Performance comparison with literature-reported architectures**

---

## Simulation Details

| Parameter | Tool Used |
|----------|------------|
| Circuit Design | Cadence Virtuoso |
| Technology Node | 90 nm gpdk |
| System Validation | MATLAB |
| Performance Evaluation | Vivado |
| Logic Style | Pass Transistor Logic (CPL) |

---

##  Results Summary

- Verified correct operation for all **8 input combinations**
- Achieved reliable logic operation within defined **noise margins**
- Successfully integrated into a **fingerprint similarity system**
- Demonstrated reliable **popcount-based arithmetic computation**
- Reduced transistor count from **28T to 18T**

---


