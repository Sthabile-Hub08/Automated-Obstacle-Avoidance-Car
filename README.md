# Automated-Obstacle-Avoidance-Car
An autonomous car that detects and avoids obstacles using ultrasonic sensor
Built with Arduino Uno, HC-SR04 ultrasonic sensor, L298N motor driver, and 2 DC motors

# Watch the DEMO VIDEO on Youtube
https://youtube.com/shorts/yKph24JBiZI?feature=share

## How It Works
1. The HC-SR04 ultrasonic sensor continuously sends out sound waves and measures the distance to the nearest object.
2. If the distance is more than 20cm, the car moves forward.
3. If an obstacle is detected within 20cm, the car stops.
4. It then looks left and right by checking distance, chooses the clear side, turns, and continues driving.
5. This loop repeats, so the car drives on its own without hitting anything.

## Components Used
- 【entity-Arduino¦canonical_name=Arduino】 Uno
- HC-SR04 Ultrasonic Sensor
- L298N Motor Driver Module
- 2x DC Motors + Wheels + Chassis
- 9V Battery / Battery Pack
- Jumper Wires
- Breadboard

## Wiring
| Component | 【entity-Arduino¦canonical_name=Arduino】 Pin |
| --- | --- |
| HC-SR04 Trig | D9 |
| HC-SR04 Echo | D10 |
| L298N IN1 | D2 |
| L298N IN2 | D3 |
| L298N IN3 | D4 |
| L298N IN4 | D5 |
| L298N ENA | D6 |
| L298N ENB | D7 |

## Project Structure
Automated-Obstacle-Avoidance-Car/
├── code/
│   └── obstacle-avoidance-car.ino
├── README.md
└── circuit-diagram.png

## How To Run
1. Open code/obstacle-avoidance-car.ino in 【entity-Arduino¦canonical_name=Arduino】 IDE
2. Select Board: 【entity-Arduino¦canonical_name=Arduino】 Uno, and your COM Port
3. Upload the code
4. Place the car on the floor with an obstacle in front of it and watch it avoid it

## Author
Sthabile-Hub08
