# Advanced-Embedded-Web-Server
Advanced Embedded Web Server with Multiple Sensors, Motor Control, and Data Logging (Using Mongoose)
Overview:
This project will involve a web-based control system that allows remote monitoring of multiple environmental sensors (e.g., temperature, humidity, light intensity), motor control (e.g., turning a fan on/off), and real-time logging of data. The system will have multiple files to modularize the code, implement security, and improve scalability. The Mongoose library will handle the HTTP requests, while the system will have a structured file system with clear separation between hardware control, web server logic, and utility functions.

Key Features:
Multiple Sensors:

Use a combination of DHT22 (Temperature and Humidity), BH1750 (Light Sensor), and BMP180 (Pressure sensor).
Periodically read sensor values and serve them via HTTP.
Motor Control:

Control a DC motor or servo motor via web-based sliders or buttons.
A PID controller can be implemented for precise motor control.
Data Logging:

Log sensor data and motor states to an SD card (or a local file) for later analysis.
Web Interface:

Provide a user interface to visualize data and control devices using AJAX for real-time updates without reloading the page.
User Authentication:

Implement basic authentication for securing access to the web server.
File Structure:

The project will be modularized into several files for better organization and readability.
