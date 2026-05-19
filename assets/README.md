This folder contains system diagrams and images.

## Hardware Components ##

The system is built using multiple embedded hardware modules integrated through Arduino Mega 2560.

- **Arduino Mega 2560** – Central controller managing all sensors and communication.
- **MPU6500 Sensor** – Detects abnormal tilt angle and calculates vehicle speed using accelerometer and gyroscope data.
- **BMP280 Sensor** – Measures environmental temperature and altitude.
- **Neo-6M GPS Module** – Provides real-time latitude and longitude tracking.
- **SIM800L GSM Module** – Sends emergency SMS alerts containing crash information and Google Maps link.
- **16×2 LCD Display** – Displays system status and live sensor readings.
- **Buzzer & LEDs** – Provide audible and visual emergency alerts.
- **L298N Motor Driver & Car Chassis** – Used for vehicle motion simulation.
