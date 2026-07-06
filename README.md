## 🤖 Autonomous Obstacle-Avoiding Robot

## 🎯 Objective

Build an autonomous robot that can move without manual input and avoid obstacles in real time using sensor data and decision-making logic. It continuously senses its surroundings, makes decisions, and controls the motors automatically.


## ⚙️ Core Engineering Principle

**Sense → Process → Decide → Act**

This control loop runs continuously while the robot is powered on.

## 🧠 Decision Logic

- Read distance from the ultrasonic sensor.
- Compare the distance with a predefined threshold.
- If the path is clear, move forward.
- If an obstacle is detected:
  - Stop
  - Move backward slightly
  - Scan left and right (optional)
  - Compare available space
  - Turn toward the safer direction
  - Resume forward movement

## 📏 Threshold

| Distance | Meaning |
|----------|---------|
| > 20 cm | Path is clear |
| ≤ 20 cm | Obstacle detected |

## 🔄 Obstacle Avoidance Flow

1. Move Forward
2. Read Distance Continuously
3. Detect Obstacle
4. Stop
5. Move Backward
6. Scan Left & Right (Optional)
7. Compare Available Space
8. Turn Toward Safer Direction
9. Resume Forward Movement

## 🛠️ Technologies Used

- Arduino
- Ultrasonic Sensor
- Motor Driver
- DC Motors
- Embedded C


