# Sun Tracking Solar Panel

The various pieces of the solar tracking system goes like this :

Circuit with LDR --> Microprocessor --> Servo motor --> Solar panel

Therefore, when the system doesn't work as intended, any possible bugs/errors in the system would be present in one of the above components.

## Troubleshooting

* Switch the circuits on and check if the solar panel is producing power. If not, then there is an issue with the solar panel.
* Check the working of the servo motors by giving them an always run code. See if the servo motor runs. If runs check if it heats up quickly or makes any high frequency and chattering sounds. If servo motor doesn't start then there is an issue with the microprocessor.
* Check whether the wiring has been done properly with the arduino and microprocessor.
* In case all the above issues fail, then there is an issue with the LDR.

### Solar Panel

When there is a zero output, this is often due to the case that one of the pv modules may have failed. As all pv modules are connected in series the failing of one causes the entire system to fail. Overheating also causes voltage drops in solar panels, therefore we need to make sure there is adequate airflow in between the panels. If the bug is not due to any of the above issues, then the panel is faulty and we need to contact support.

### Servo motor

When a servo motor overheats, it may be due to reasons such as poor ventilation, extended use or a fault in the motor. As the servo motor in the case of a solar panel is exposed to the sun, overheating may occur. Therefore, covering the servo motors with an insulating material will help fix the issue. If the servo motor doesn't turn on knowing that the remaining components are working properly, then there is a problem with some of the internal parts of the motor and we need to contact services to repair the motor. If the servo motor makes excessive noise, then this might be due to a wiring issue. Therefore, we need to check connections and grounding before switching on the circuit.

### Microcontroller

If both the solar panel and the servo motor work individually but upon connection, the system doesn't work , then there is an issue with the microcontroller. One of the ways to test if the ATmega328p is working is by importing a simple LED blinking code and checking whether it works.

```
#ifndef F_CPU
#define F_CPU 16000000UL // 16 MHz clock speed
#endif
#include <avr/io.h>
#include <util/delay.h>
int main(void)
{
  DDRC = 0xFF; //Nakes PORTC as Output
  while(1) //infinite loop
  {
    PORTC = 0xFF; //Turns ON All LEDs
    _delay_ms(1000); //1 second delay
    PORTC= 0x00; //Turns OFF All LEDs
    _delay_ms(1000); //1 second delay
  }
}
```

The following code can be used to check the LED blinking. In case the LED doesn't blink, then the microprocessor is faulty and we need to contact support.

### Light Dependent resistor (LDR)

Before connecting the LDRs to the cicuit, we can check the functioning of the LDRs. To check the working of the LDRs take them in sunlight and connect the two ends with a multimeter. In sunlight record the resistance of the LDR. Now, cover the LDR with an opaque paper/cloth and measure resistance. If the resistance measured after covering is quite higher than the first case, then we can say that the LDR is working properly. Or else the LDR is faulty.

