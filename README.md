# Security_Alert_System
I built a motion-activated Security Alert System using a Raspberry Pi. This project allowed me to connect physical hardware components with Python code to build a real world security tool! 

 Here's how the system works⬇️:

1. When the system starts, the LCD screen displays "Warming Up." This gives the PIR motion sensor a few seconds to settle down and adjust to the room's temperature, which prevents the system from triggering false alarms.

2. Once the sensor is ready, the LCD screen changes to "Monitoring." This means the Raspberry Pi is officially active and constantly listening for any movement in the area.

3.The moment the sensor detects movement, it sends a signal to the Raspberry Pi. The code immediately triggers two actions at the exact same time:

	• It updates the LCD screen to show a clear alert message: "Intruder detected!"

	• It tells the Pi Camera to instantly snap a photo and save it to the device.
