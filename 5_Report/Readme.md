# OBJECTIVE OF THIS PROJECT:
 By using STM32F407,buttons,4 LED's the project should be done using the timers and the sequence of glowing 
 of LED's RED,GREEN,BLUE and the 4th acc mode either ON or OFF mode.If we press for a long time car should 
 start or stop and by clicking the buttons the wipers speed mode should change.
 
# INTRODUCTION:
 
  The STM32F4xx-discovery board is used to demonstrate an automobile wiper control system. Most car wipers are 
  controlled by a DC motor, but because the STM32F4xx-discovery lacks a motor, we are investigating the use of 
  LEDs in this application. Consider the wiper control system. The STM32F4xx-discovery board includes four LEDs 
  as well as a Push Button. These LEDs are orange, green, red, and blue in colour. A current limiting resistor 
  connects four user LEDs to the PORTD pins PD12, PD13, PD14, and PD15 on the Discovery board. The GPIO pins will 
  be set as digital input pins to make a push button work with the STM32F407VG microcontroller.If you hold the 
  user button down for two seconds, the Red The LED illuminates when the ignition key is positioned at the ACC. 
  Furthermore, the LEDs are flashing, indicating that the wipers have been activated.
  
 # COMPONENTS:
  
  !) STM32F407 Discovery Board
  2) LED's
  3) Resistors
  4) Push Button
  
 # ADVANTAGES:
 
   • It is very simple to use.
   • Rain sensor-based systems are extremely easy to set up.
   • Individual rain sensors are reasonably priced.
   • As a result, less energy is consumed.
   • Turn off the irrigation system to save money during wet seasons. As a result, electricity bills are reduced.
   • Rain sensors collect water during rain events and store it for use throughout the summer and winter.
  
 # DISADVANTAGES:
   
    • To avoid erroneous rain detection, rain sensors must make a decision within a few minutes.
    • The mechanism activates when water falls directly on the rain sensor.
    • When more components, such as a rain sensor, are required, the overall system cost rises.
    
  # STM32F407VG:
    The STM32F407 Kit takes advantage of the advanced capabilities of the STM32F407 microcontroller to make it
    simple for customers to create sound-based applications. It includes an ST-LINK inserted troubleshooting 
    instrument, an ST-MEMS computerised accelerometer, a sophisticated mouthpiece, a sound DAC with coordinated 
    class D speaker driver, LEDs, pushbuttons, and a USB OTG miniature AB connector. The STM32F4 DISCOVERY unit 
    now includes an Ethernet network, an LCD display, and other components. The STM32F405xx and STM32F407xx 
    families are based on the Arm cortex - M4 bit RISC centre, which operates at up to 168 MHz.
    
  # FEATURES OF STM32F407VG:
   
   • 512 bytes of OTP memory.
   • Up to 192+4 Kbytes of SRAM including 64-Kbytes of CCM (Core Coupled Memory) data RAM.
   • Flexible static memory controller supporting Compact flash SRAM, PSRAM, NOR and NAND memories
   • Up to 1 Mbyte of flash memory
   
 # 4W & H (WHO,WHAT,WHEN,WHERE,HOW):
  
   Accept the car to be the microcontroller. If the button is pressed, the main drive (red) will activate,
   the wiper will begin, and the subsequent drive (blue) will activate for an optimal rate. If the button 
   is pressed again, the third driven (green) will turn on, and the wiper's speed will be increased in 
   comparison to the previous one. The fourth press will activate the fourth driven (orange), and the wiper
   speed will be increased in accordance with the previous one. After the fifth snap, the microcontroller 
   (vehicle) is turned off.
   
 ## WHAT:
    
    A wiper speed control mechanism based on rain conditions controls the operational speed of a vehicle wiper. 
    The control system includes a rain sensor (30) that detects rain conditions in order to generate. The 
    amplitude of an analogue signal is determined by the rain conditions detected.
    
 ## WHY:
     To keep the windscreen clean enough at all times to provide an adequate view. #WHEN The windshield wipers 
     clear the windshield of rain and snow, while the headlights improve visibility at night.
  
 ## WHO:
     Mark Anderson invented on 1902.
     
 # Exploring STM32F407 Discovery Board:
     
  

   

   
