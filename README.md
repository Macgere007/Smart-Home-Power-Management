Smart Home Power Management Simulator
Using Cisco Packet Tracer
1. INTRODUCTION
The Smart Home Power Management Simulator is a system designed using Cisco
Packet Tracer to simulate and optimize power usage within a smart home environment. This
system integrates various IoT devices, smart appliances, and energy management tools to
create a realistic model of a connected home. Each device is configured to interact with a
central management system, enabling real-time monitoring and control of energy consumption
patterns.
Many households struggle with inefficiencies and a lack of centralized control in
managing and optimizing their energy use, leading to higher electricity bills and unnecessary
environmental impacts.
Goals:
1. Implement a centralized Home Energy Management System (HEMS) to monitor and
control energy usage across all devices and appliances.
2. Integrate smart technologies and IoT devices to enable real-time monitoring and
automated control of energy-consuming devices.
3. Develop algorithms and predictive analytics to optimize energy consumption based on
household patterns, preferences, and real-time electricity pricing.
4. Provide user-friendly interfaces and mobile applications for homeowners to track energy
usage, receive alerts, and adjust settings remotely.
5. Reduce electricity bills and environmental impact by promoting energy-efficient practices
and leveraging renewable energy sources where feasible
2. MATERIALS AND METHODS
MATERIALS
1. Software
1. Cisco Packet Tracer
2 Hardware
1. Actuators: Air Conditioner, Humidifier, and Light
2. Sensors: Power Meter, Humidity Monitor, and Thermostat
3. Electronic Devices: Laptop, Smartphone, and PC
4. Servers: DHCP Server (main) , DNS Server
5. Router: Home Router
6. Switch: Switch 2960
3. METHODS
In this project, the author utilizes Cisco Packet Tracer, a software tool essential for simulating
and monitoring IoT devices in electronic systems.
STEPS
1. Router Configuration:
● Wireless settings:
○ SSID: Rustam
○ Password: Rustam123456789
2. Server Configuration:
● DHCP Server:
○ IP: 192.168.1.10
● DNS Server:
○ IP: 192.168.1.11
3. Devices Configuration
● Laptop Configuration:
○ Set IP address automatically using DHCP
● Actuators Configuration:
○ Configure wireless settings:
■ Connect actuators to router
● Sensors Configuration:
○ Configure Ethernet adapter:
■ Use auto cable for connection
4. Power Meter Auto Turn-off Algorithm
● Monitors electricity usage and initiates a turn-off sequence when usage exceeds a set
threshold.
● Stops all devices when the usage time reaches approximately 5 minutes runtime.
4. RESULTS AND DISCUSSION
RESULTS
Connection: All devices, server, and router are connected
Simulator Monitoring Platform:
Here is the demo attached below.
https://drive.google.com/drive/folders/1KrB6XrHZxvGqFVxvu8Wy6JplsbwhbuHM?usp=sh
aring
DISCUSSION
The connection between sensors and actuators is monitored on electronic devices through an
IoT monitor and web server accessible by typing "rustam.local" in the search bar. Conditions are
set such that when the power meter reads 2 W or higher, the lamp and thermostat are activated;
when it reads 0 W, all devices are turned off. The humidifier activates when the power meter
reads 2 W and the humidity monitor indicates 50% or higher humidity. For the AC, it operates
based on temperature, turning on when the temperature exceeds 18°C and auto and the AC is
turned off when the status is off or under 18°C.
5. CONCLUSION
In conclusion, the Smart Home Power Management Simulator, implemented in Cisco Packet
Tracer, emerges as a powerful tool for simulating and optimizing energy consumption within
smart home environments. By seamlessly integrating IoT devices, smart appliances, and
comprehensive energy management tools, this system establishes a realistic model capable of
monitoring and dynamically controlling energy usage patterns in real time. Overall, this
simulation underscores the potential of technology to promote sustainable energy practices and
improve living comfort in modern households
