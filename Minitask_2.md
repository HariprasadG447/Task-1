# Sun Tracking Solar Panel

## Problem Statement 

Designing a solar panel mount which automatically adjusts its position based on the position of the sun in order to get maximum amount of sunlight on the panel.

## Ideation and Planning

The solar tracker is designed to adjust its position such that the sun rays always fall perpendicular to the solar panel. This is achieved by placing two LDRs at the sides of the panel. A servo motor connected to the system rotates the panel to the direction in which one of the LDRs have low resistance that is, in the direction where sunlight has higher intensity.

## Pipeline



## Ideas for Improvement

| Part/Attribute improvements | Feasibility | Advantages | Disadvantages |
| :---: | :---: | :---: | :---: |
| Single axis to Dual Axis | Is feasible by using a support containing two hinges for the movement in the two directions | Improves the efficiency of the light collection by the solar panel | Involves the use of multiple gears and motors thus increasing the cost as well as the complexity of the design |
| Replacing the LDR by a sun tracking algorithm | Is feasible as it is an algorithm which can be coded | Negates the use of another component in the circuit such as LDRs | Complicated algorithm to design and meticulous testing needs to be done to ensure minimum errors |
| Power Line Communication system (PLC) | Is feasible as the power line can also be used as a data communication line | Helps in preventing overcharging of a particular charging device by transferring power to the next device | Improper setup may lead to damage in the power storage devices |

## Prototyping Phase

Initially, a single axis panel using a simple cardboard and servo motor setup can be used and tested. On having built a successful prototype, we can build the intended design with the multiple upgrades.


# Human Detection Robot 

## Problem Statement

Designing a robot which can sense the presence of human beings in emergency situations such as natural disasters.

## Ideation and Planning

The Human detection Robot is a moving system designed to detect Humans in under debris or other solid separations in the case of accidnets and emergencies. The system is a wireless robot and consists of two circuits, the transmitter circuit and the receiver circuit. The transmitter circuit is connected to the PC and is used to control the robot and receive and process data from the robot. The receiver circuit consists of the microcontroller, motors to drive the robot and a PIR sensor used to detect humans.

## Pipeline

## Ideas for Improvement

| Part/Attribute improvements | Feasibility | Advantages | Disadvantages |
| :---: | :---: | :---: | :---: |
| Replacing the PIR sensor with a motion detection sensor such as XeThru | XeThru is a sensor available in the market and is therefore feasible to replace it | The XeThru can detect humans with much greater accuracy as it can detect the faint heartbeat and motion of a human | The sensor is expensive and adds to the cost of production |
| Adding cameras to the robot | Is feasbile as several cameras such as GoPros are light weight and can be integrated to the microcontroller whose image can be then be seen on PC through wifi module such as EPS8266 | Adding a camera can help the robot go through tight spaces in the hazard zone and can thus explore the area better | The system is becomes a complex to assemble and also the load on the microcontroller is increased |
| Adding data graphing and checks | Graphs can be easily plotted in the PC from the data collected and simple checks can be coded into the robot such as giving a clear signal when there is no presence of humans | Improves the reliability of the robot and improves efficiency of accident rescue teams | Adds higher computational load on the microcontroller |

## Prototyping phase

A prototype with a simple PIR sensor and a data receiver is first made. The sensor is then moved manually and the human detection capacity is checked. Then a movable robt prototype is made to which the PIR sensor is attached. Finally the total circuits and design is implemented.






