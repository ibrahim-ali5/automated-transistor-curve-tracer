# Devlog

### 05-23-2026
Settled on the automated transistor curve tracer as my main summer project idea. Created the repo also.

The goal is to build something that combines analog circuits, embedded programming, measurement, PCB design, and Python-based plotting.
<br><br>


### 05-28-2026
Today I set up the initial GitHub repository for this project. Wrote `tools.md` to track what ima need for this. Gotta write out the roadmap next and get this project started.
<br><br>


### 05-29-2026
Roadmap complete (`roadmap.md`).
Started phase 1, verified PlatformIO works by wiring external LED blinking with 220Ω resistor on pin 8, verified that reading analog input works, and verified serial monitor. 
<br><br>


### 05-30-2026
Got Python reading serial data from the Arduino. The Arduino sends raw ADC values and calculated voltage from a potentiometer, and the Python script parses these and prints the readings.
<br><br>
