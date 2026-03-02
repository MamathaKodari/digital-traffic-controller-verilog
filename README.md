# 🚦 Traffic Light Controller using Verilog (FSM)

## 📌 Project Overview

This project implements a **Traffic Light Controller** using **Verilog HDL** based on a **Finite State Machine (FSM)** design approach.
The controller manages traffic signals for multiple roads by switching between different states with predefined timing intervals.

The design is simulated using a Verilog testbench to verify correct state transitions and signal outputs.

---

## 🎯 Objectives

* Design a traffic signal controller using **FSM concept**
* Implement sequential logic using Verilog HDL
* Control multiple traffic signals with timing delays
* Verify functionality using simulation

---

## ⚙️ Design Description

The controller operates using **6 states**:

| State | Description        |
| ----- | ------------------ |
| S1    | Main road Green    |
| S2    | Main road Yellow   |
| S3    | Turn signal active |
| S4    | Transition state   |
| S5    | Side road Green    |
| S6    | Side road Yellow   |

Each state remains active for a specific number of clock cycles controlled by an internal counter.

---

## ⏱️ Timing Parameters

| Parameter | Duration (Clock Cycles) |
| --------- | ----------------------- |
| sec3      | 3 cycles                |
| sec4      | 4 cycles                |
| sec6      | 6 cycles                |
| sec8      | 8 cycles                |

---

## 🧠 FSM Architecture

The design consists of:

* **State Register** – Stores current state
* **Next State Logic** – Controls transitions
* **Counter** – Maintains timing delays
* **Output Logic** – Controls traffic lights

---

## 🚥 Signal Encoding

Each traffic light uses 3-bit encoding:

| Code | Light  |
| ---- | ------ |
| 001  | Green  |
| 010  | Yellow |
| 100  | Red    |

---

## 🧪 Simulation

A Verilog **testbench** is used to:

* Generate clock signal
* Apply reset
* Observe state transitions
* Verify traffic light outputs

---

## 🛠️ Tools Used

* Verilog HDL
* ModelSim / Vivado Simulator
* Digital Design (FSM Concept)

---

## 📚 Concepts Used

* Finite State Machine (FSM)
* Sequential Circuits
* Counters
* RTL Design
* Digital System Design

---

## ✅ Results

The simulation confirms correct:

* State transitions
* Timing control
* Traffic light sequencing

---

## 👩‍💻 Author

Mamatha Kodari/
Electronics / ECE Student

---

## ⭐ Future Improvements

* FPGA implementation
* Sensor-based adaptive traffic control
* Emergency vehicle priority system
* Real-time traffic optimization

---

## 📜 License

This project is created for educational purposes.
