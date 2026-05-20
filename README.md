This repository includes a collection of practical embedded systems and RTOS-based experiments developed using the STM32F446RE Nucleo Board and STM32CubeIDE. The aim of these experiments is to understand how microcontrollers interact with hardware peripherals and how real-time applications are designed using FreeRTOS.


The experiments begin with basic embedded programming concepts such as GPIO control and button interfacing, then gradually move toward sensor integration, PWM generation, interrupt handling, and RTOS-based multitasking. By the end of this series, the user gains practical knowledge of both bare-metal programming and real-time system design.

Key Concepts Covered

 Area                   Topics                                                  

 Embedded Systems      GPIO, Timers, PWM, UART, EXTI                           
 Sensor Interfacing    HC-SR04 Ultrasonic Sensor                               
 Programming Approach  Super Loop, Event-Driven Execution                      
 RTOS Fundamentals     Tasks, Scheduler, Priorities                            
 Synchronization       Binary Semaphore, Counting Semaphore, Task Notification 
 Communication         Queues, UART Data Transfer                              
 Concurrency           Shared Resource Handling                                
 Timing                Delays, Counters, Timer-Based Operations               

 Tools and Hardware Used

* STM32F446RE Nucleo Board
* STM32CubeIDE
* FreeRTOS Middleware
* Embedded C
* UART Serial Monitor
* HC-SR04 Ultrasonic Sensor
* LEDs and Push Buttons

 Applications

The concepts practiced in these experiments are useful for developing:

* Smart parking systems
* Industrial automation projects
* IoT monitoring devices
* Robotics applications
* Real-time safety systems
* Sensor-based automation systems

 Topics Included

1. GPIO digital output and LED control
2. Digital input using push buttons
3. HC-SR04 ultrasonic sensor interfacing
4. PWM signal generation and duty cycle control
5. Super loop architecture
6. FreeRTOS task creation and scheduling
7. Task priorities and preemption
8. External interrupt handling with RTOS synchronization
9. Inter-task communication using queues
10. Shared resource management using counting semaphores

Conclusion

This experiment series provides a step-by-step learning path for embedded systems and RTOS development. It helps in understanding how hardware peripherals are controlled, how real-time tasks are created, and how synchronization and communication are handled in FreeRTOS-based applications.
