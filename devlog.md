# Devlog

### 05-23-2026
Settled on the automated transistor curve tracer as my main summer project idea, and created the repo.

The goal is to build something that combines analog circuits, embedded programming, measurement, PCB design, and Python-based plotting.
<br><br>


### 05-28-2026
Today I set up the initial GitHub repository for this project. Wrote `tools.md` to track what ima need for this. Gotta write out the roadmap next and get this project started.
<br><br>


### 05-29-2026
Roadmap complete (`roadmap.md`).

Started Phase 1: 
- verified PlatformIO works by wiring external LED blinking with 220Ω resistor on pin 8
- verified that reading analog input works
- verified that the serial monitor output works. 
<br><br>


### 05-30-2026
Got Python reading serial data from the Arduino. The Arduino sends raw ADC values and calculated voltage from a potentiometer, and the Python script parses these and prints the readings.

Finished the live Python plotting from Arduino serial data. Saved plots/pics in `docs/`, this completes phase 1!
<br><br>


### 05-31-2026

Took time to organize the electronic components into a binder system so parts are easier to find during prototyping. Started sorting resistors, capacitors, diodes, transistors, ICs, and modules into labeled sections.

This should make future breadboard testing and debugging less chaotic.