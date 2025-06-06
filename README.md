# Wind Turbine System Control

## 📝 Overview

This repository contains a detailed student project on implementing and evaluating different control strategies for a wind turbine system. The objective is to apply theoretical control concepts to analyze, design, and compare the performance of multiple controller types in a complete simulation environment developed in **MATLAB/Simulink**.

The project starts with the modeling and analysis of the turbine system (transfer function, pole-zero stability) and progresses to the implementation and testing of controllers on a complex, non-linear model.

---

## 🚀 Implemented Control Approaches

Three distinct control methods were designed, simulated, and compared:

**Pole-Zero Placement:** A classic control technique where the designer specifies the desired location for the closed-loop poles and zeros.

**Internal Model Control (IMC):** A strategy that explicitly uses a model of the process to design the controller, aiming to cancel the system's dynamics.

**RST Control:** A robust polynomial controller with a two-degree-of-freedom structure, allowing for the separate handling of reference tracking and disturbance rejection.

---

## 🏆 Conclusion & Results

After a comparative performance analysis, the **RST controller** was identified as the most effective.

**Performance:** While all controllers showed similar disturbance rejection, the RST controller demonstrated the best attenuation of high-frequency measurement noise.

**Reference Tracking:** The pole-zero placement method showed the poorest performance when tracking ramp inputs.

**Final Implementation:** The RST controller was chosen for the final implementation on the detailed, non-linear model.It successfully controlled the system and improved energy production and efficiency, even with the real model's non-linearities.

---

## 🛠️ Technologies Used

MATLAB/Simulink
