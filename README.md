# 🤖 3DOF Robotic Arm Torque Analysis & Motor Selection

This document provides a concise analysis of the torque requirements for a 3-Degrees-of-Freedom (3DOF) robotic arm and recommends suitable servo motors for each joint. The arm is designed to lift a 1 kg payload.

## 📐 Specifications & Assumptions

- Payload: 1 kg 📦

### Link Lengths:
- Link 2 (Joint 1 to Joint 2): 10 cm (0.1 m)
- Link 3 (Joint 2 to End Effector): 15 cm (0.15 m)
- End Effector: 4 cm (0.04 m)
- Gravity (g): 9.81 m/s²

## ⚡ Torque Calculations

Torque (τ) = Force (F) × Lever Arm (r)
Force (F) = Mass (m) × Gravity (g)

##  📷  Picture of the Calc :

![20250730_200356](https://github.com/user-attachments/assets/7b737a6a-f6bb-4925-a34e-bdb92f8518ba)

## ⚙️ Motor Recommendations

|     Joint     |  Torque (Nm)  |   Motor Type  |
| ------------- | ------------- | ------------- |
| Joint 3       | 0.39          | [ATO 25kg·cm RC Servo Motor](https://circuits-elec.com/products/servo-motor-sg-5010-5-kg-cm?srsltid=AfmBOooFash-SHPrXExL76KDNKCMLhT-AGROOM57dEgbM0KKjGpQ-OMn) |
| Joint 2       | 1.37          | [MG996R Motor](https://store.open-electronics.org/SERVO213)              | 
| Joint 1       | 2.45          | [ATO 25kg·cm RC Servo Motor](https://www.waveshare.com/st3020-servo.htm) | 




