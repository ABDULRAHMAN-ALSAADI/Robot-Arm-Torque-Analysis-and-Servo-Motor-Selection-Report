# 🤖 3DOF Robotic Arm Torque Analysis & Motor Selection

This document provides a concise analysis of the torque requirements for a 3-Degrees-of-Freedom (3DOF) robotic arm and recommends suitable servo motors for each joint. The arm is designed to lift a 1 kg payload.

## 📐 Specifications & Assumptions

- Payload: 1 kg 📦

  Link Lengths:
- Link 1 : 15 cm (0.15 m)
- Link 2 : 10 cm (0.10 m)
- Link 3:  4  cm (0.04 m)
- Gravity (g): 9.81 m/s²

## ⚡ Torque Calculations

- Torque (τ) = Force (F) × Lever Arm (r)
- Force (F) = Mass (m) × Gravity (g)

##  📷  Picture of the Calc :

![20250730_200356](https://github.com/user-attachments/assets/7b737a6a-f6bb-4925-a34e-bdb92f8518ba)

## ⚙️ Motor Recommendations

|     Joint     |  Torque (Nm)  |   Motor Type  |
| ------------- | ------------- | ------------- |
| Joint 3       | 0.39          | [Servo Motor SG-5010](https://circuits-elec.com/products/servo-motor-sg-5010-5-kg-cm?srsltid=AfmBOooFash-SHPrXExL76KDNKCMLhT-AGROOM57dEgbM0KKjGpQ-OMn) |
| Joint 2       | 1.37          | [MG996R Motor](https://store.open-electronics.org/SERVO213)              | 
| Joint 1       | 2.45          | [ATO 25kg·cm RC Servo Motor](https://www.waveshare.com/st3020-servo.htm) | 


# 🏋️‍♀️ Lifting 2 kg with Gears: Feasibility, Drawbacks, and Alternatives

**Could the same motors selected from the previous mission lift a weight of 2 kilograms instead of 1 kilogram by adding some gears?**

While adding gears can increase torque, it introduces several significant drawbacks:

1 - **Reduced Speed:** 🐢 The most immediate and noticeable drawback is a proportional reduction in the arm's speed. If you double the torque through gearing, you halve the speed. This can make the robotic arm very slow and inefficient for tasks requiring quick movements.

2 - **Increased Complexity and Weight:** 🏋️‍♀️ Adding gearboxes increases the mechanical complexity of the arm. This means more parts, more potential points of failure, and increased overall weight.

3 - **Reduced Efficiency and Increased Friction:** 🔥 Gearboxes are not 100% efficient; some energy is lost due to friction between the gear teeth. This reduces the overall efficiency of the system and can generate heat. 

4- ** Maintenance:** 🛠️ More mechanical components mean more maintenance. Gears can wear out, require lubrication, and may need periodic replacement.

5 - **Cost:** 💸 While individual gears might be cheap, designing, manufacturing, and integrating custom gearboxes can add significant cost to the project.

## What are the alternatives to address these drawbacks?

1 - **Use More Powerful Motors:** 💪 The most straightforward solution is to select motors that are inherently capable of providing the required torque for a 2 kg payload.

2 - **Redesign the Arm for Lighter Materials/Structure:** 💡 Reduce the weight of the arm itself by using lighter, yet strong, materials (e.g., carbon fiber, aluminum alloys) or optimizing the structural design.


In summary, while adding gears can technically increase torque, it often compromises speed, precision, and overall system performance. For a significant increase in payload capacity, investing in more powerful motors or a fundamental redesign of the arm is generally a more robust and effective solution. 💪🚀
