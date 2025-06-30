# emergmod8
1. Summarize the project and what problem it was solving.
This project involved developing a smart thermostat system using a Raspberry Pi, temperature/humidity sensor (AHT20), LEDs, an LCD display, and GPIO button inputs. The system detects environmental conditions, displays readings in real time, and adjusts states (e.g., heating or cooling) based on thresholds. It demonstrates practical embedded systems integration for home automation.

2. What did you do particularly well?
I successfully implemented a state machine that controls system behavior efficiently and clearly. I also ensured proper modular design by separating hardware interface logic (sensors, display, LEDs) from the core control logic. The use of object-oriented programming helped keep the code clean and scalable.

3. Where could you improve?
I could improve exception handling and system fault tolerance. For example, adding watchdog timers or implementing recovery from I2C communication errors would make the system more robust. Also, logging sensor data for diagnostics is something I’d include in future versions.

4. What tools and/or resources are you adding to your support network?
I’ve added Adafruit’s CircuitPython libraries, the Raspberry Pi GPIO documentation, and online forums like Raspberry Pi Stack Exchange to my toolbox. I also became more comfortable using I2C/SPI documentation and datasheets directly.

5. What skills from this project will be particularly transferable to other projects and/or coursework?
This project helped solidify skills in:

Python for hardware control and real-time systems

Embedded systems architecture

Working with communication protocols (I2C, UART)

State machine design

Project documentation and modular coding — all highly transferable to IoT, robotics, and real-time systems work

6. How did you make this project maintainable, readable, and adaptable?
I followed a modular, object-oriented structure with docstrings and comments throughout. Functions were single-purpose, and file separation kept sensor and actuator logic isolated. Variable and function names were descriptive, and I used constants for threshold values to allow easy configuration changes. The project is stored in a GitHub repo for version control and reuse.

