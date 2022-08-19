# CS-350
System Architecture

1. Summarize the project and what problem it was solving
  The project for CS-350 was t develop a program for a smart home thermostat. The thermostat had multiple requirements in order to meet the company specifications for the system. The thermostat must be wifi capable and connect to cloud services. The thermostat must use the tmp006 sensor on the board in order to read room temperature. The setpoint temperature must be adjustable via GPIO buttons on the board. A red LED must illuminate when the room temperature is at or below the setpoint temperature. This indicates the thermostat heater is on. Once the room temperature exceeds the setpoint temperature, the LED light will shut off. The room temp, setpoint, heat off/on, and time since system reset should be displayed via UART in the serial terminal.
  
2. What did you do particularly well?
  I fee like the area that I did particularly well was breaking down the state machine of the state of the LED. I personally had quite a time trying to learn state machines and implementing them into C, but through time, perserverance, and a lot of trial and error, I was able to figure out the concept to properly implement it. Once I was able to break down the state machine and the concept instead of what it is supposed to do on a larger scale, I could grasp the goal without being overwhelmed. This mental roadblock was challenging, but very gratifying to overcome.
  
3. Where could you improve?
  The overall code worked well and was somewhat easy to follow for someone who may not be familiar with the project, but the notation and flow of the code could have been crisper in its appearance, but due to time constraints, I had to make due with what I was able to accomplish in the timeframe. If I could do anything else, I would clean this up and possibly look for any redundancies in the code to ensure no duplicate code is being written as well as more detailed notation to each part of the code.
  
4. What tools and/or resources are you adding to your support network?
  By better understanding the concepts of embedded systems and having a general project under my belt, I feel the tools presented in the project are tool to add to my arsenal. I will also be adding my fellow peers to my support network as well. This class made me use my fellow classmates as a resource multiple times to help me better understand concepts or ideas. This was invaluable, and I was fortunate enough to reciprocate the help to some of them as well. 
  
5. What skills from this project will be particularly transferable to other projects and/or course work?
  Understanding state machines in a more in depth manner will be transferable to many other courses or future projects. The understanding of states and transitions is a valuable skill to help break down future projects in order to draw out diagrams of how a system should work. Another skill is iteration of code. By understanding the concept of writing code in iterations and testing often, I was able to take a project that seemed daunting and break it down to small portions that were much more manageable. This is a process that will be valuable to future projects or career endeavors.
  
6. How did you make this project maintainable, readable, and adaptable?
  One way to make this project maintainable was to use best standards and practices throughout the code, creating a program that can be maintained through updates to libraries or other portions of the code, but in small portions. The code is made readable by having good notation throughout the program, as well as creating syntactically correct code that can be followed smoothly. The code is adaptable by using industry accepted libraries and and syntax. By using these, one can simply adapt the code to their personal needs, without changing the bulk of the program. One can simply change particular variables or objects to fit their needs, but maintain the overall functionality of the code.  
