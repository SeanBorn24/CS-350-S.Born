# CS-350-S.Born
Repository for CS350 Course

1. Summarize the project and what problem it was solving.
   
     This project implemented a thermostat system using a Raspberry Pi, an AHT20 temperature sensor, LEDs, buttons, an LCD display, and UART communication. The main problem it solved was automating room temperature monitoring and control in a way that gives clear feedback       to the user (via LEDs and an LCD) while also transmitting system data externally over a serial connection. The state machine design ensured that the thermostat could reliably switch between off, heating, and cooling states while maintaining a user-defined set point.

 2. What did you do particularly well?

     The things that I did well were that I successfully translated the thermostat’s requirements into a working state machine with well-defined transitions. I also integrated multiple hardware components (AHT20 sensor, LEDs, LCD, buttons, UART) into a       cohesive system and clearly implemented LED feedback logic (pulsing vs solid) to match system behavior, which improves usability. 

3. Where could you improve?

     I believe that I could improve my time management because I was consistently late with getting the projects in. Another thing I could improve is making sure that I am not trying to rush through things which may help me with a few of the problems that I did encounter        due to missed steps that were clearly outlined. Lastly, I beleive that the machine state diagrams that I created were not the best and I could improve on creating these.
   
4. What tools and/or resources are you adding to your support network?

     Tools that I will add to my support network include gpiozero library for handling LEDs and buttons more intuitively, Adafruit CircuitPython libraries for AUT20 and LCD that provide strong community documentation and examples, serial communication tools such as              pyserial for debugging UART output, and collaboration/visualization tools such as draw.io to help improve system design clarity.
   
5. What skills from this project will be particularly transferable to other projects and/or course work?

     Transferable skills include state machine design, hardware-software integration, threading for concurrent tasks, and system debugging. 

6. How did you make this project maintainable, readable, and adaptable?

     This project was maintainable, readable, and adaptable because it had class based designed where logic was separated into components that are easier to modify or reuse, navming conventions were also consistent, and parameraters such as default set point and GPIO pins       were configurable to make the code adaptable to other setups.
