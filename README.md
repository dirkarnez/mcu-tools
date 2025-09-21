mcu-tools
=========
### PWM
- PWM output may interfere with other components, particularly if it’s driving a high-frequency component
- analog input should be protected from EMI to ensure signal integrity. 
- As a rule of thumb, you want the frequency of your PWM signal to be greater than 5 over 2 pi tau, where tau is the electrical time constant for your desired motor.
- [PWM Driving of Motors: Relationship between PWM Period and Electrical Time Constant of the Motor | Evolution and Kinds of Motors | TechWeb](https://techweb.rohm.com/trend/column/866/)
- Duty Cycle is a percentage
- τ is in seconds
- pwm + rc
- [Motor interfaces and PWM frequencies | Video | TI.com](https://www.ti.com/video/6272403276001)
- [Basics of PWM (Pulse Width Modulation) | Arduino Documentation](https://docs.arduino.cc/learn/microcontrollers/analog-output/)
