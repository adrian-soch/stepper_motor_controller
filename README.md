# stepper_motor_controller
Using a STM32L476 MCU to control stepper motor speed, direction, and step type.

Uses on board pushbuttons to increase/decrease speed

## Software
Program control based on the following FSM

![image](https://user-images.githubusercontent.com/6884645/90038529-88b3a800-dc93-11ea-8f7c-8364340fc010.png)

#### Required
- STM32Cube_FW_L4_V1.8.0 
- STM32 ST-LINK Utility

## Hardware
- SN754410NE H-bridge driver.
- 26M048B1B 48 Step
- Diodes (IN4001)
- 10 KOhm Resistor

![image](https://user-images.githubusercontent.com/6884645/90037421-31610800-dc92-11ea-9dad-39304ed0a1ba.png)
