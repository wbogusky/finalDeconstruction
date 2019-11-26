# Morse Band Planning / Deconstruction
Couple's RF transceiver wearables with taps as input and quick vibrating clicks as output on the opposing band. For use in remote areas where low power and longer range might be issues.

### Use case:
Two friends are spending the day at the beach. One surfs; the other does not. In order to communicate that it's time to leave, the person on the beach taps their band _ .. __ . (TIME).

### Use case:
Two friends are skiing and decide to explore some side-country terrain. They become separated and cannot call to each other to locate themselves. One skier has ventured to far into a valley and can't reach the main run so they tap ... ___ ... (SOS) to let the other skier know it is an emergency. The other skier contacts ski patrol and the first skier is saved.

### Deconstruction
- Hardware
	- Enclosure
		- Band
		- ?
	- Controller 
		- On / off switch? Closed wristband for on, open > off
		- ATTiny?
	- Battery
	- Touch Sensor
	- Radio Transmitter
	- Radio Receiver
	- Vibration Motor [Here](https://www.adafruit.com/product/1201?gclid=Cj0KCQiAn8nuBRCzARIsAJcdIfNABtXtWxegX6MIYHq6byKu7LqfqwoOTtsmEaqDQcaluApI0elPZWAaAm77EALw_wcB)
- Data
	- User input
		- Taps start and end
	- Process
		- How to make start and end data transmittable via RF?
	- Render
		- In range? LED?
		- What about simultaneous communication? LED?
		- Interpret start and end data and trigger vibration patterns
