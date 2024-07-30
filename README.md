Smart Home Power Management Simulator
Using Cisco Packet Tracer

The Smart Home Power Management Simulator is a system designed using Cisco
Packet Tracer to simulate and optimize power usage within a smart home environment. This
system integrates various IoT devices, smart appliances, and energy management tools to
create a realistic model of a connected home. Each device is configured to interact with a
central management system, enabling real-time monitoring and control of energy consumption
patterns.
Many households struggle with inefficiencies and a lack of centralized control in
managing and optimizing their energy use, leading to higher electricity bills and unnecessary
environmental impacts.

MATERIALS
- **Software**
  - Cisco Packet Tracer

- **Hardware**
  - **Actuators**
    - Air Conditioner
    - Humidifier
    - Light
  - **Sensors**
    - Power Meter
    - Humidity Monitor
    - Thermostat
  - **Electronic Devices**
    - Laptop
    - Smartphone
    - PC
  - **Servers**
    - DHCP Server (main)
    - DNS Server
  - **Router**
    - Home Router
  - **Switch**
    - Switch 2960
      
METHODS 
<br>
In this project, the author utilizes Cisco Packet Tracer, a software tool essential for simulating
and monitoring IoT devices in electronic systems.

- **Router Configuration**
  - **Wireless Settings**
    - SSID: Rustam
    - Password: Rustam123456789

- **Server Configuration**
  - **DHCP Server**
    - IP: 192.168.1.10
  - **DNS Server**
    - IP: 192.168.1.11

- **Devices Configuration**
  - **Laptop Configuration**
    - Set IP address automatically using DHCP
  - **Actuators Configuration**
    - Configure wireless settings:
      - Connect actuators to router
  - **Sensors Configuration**
    - Configure Ethernet adapter:
      - Use auto cable for connection

- **Power Meter Auto Turn-off Algorithm**
  - Monitors electricity usage and initiates a turn-off sequence when usage exceeds a set threshold.
  - Stops all devices when the usage time reaches approximately 5 minutes runtime.

RESULTS AND DISCUSSION

Connection: All devices, server, and router are connected
![Screenshot 2024-07-21 131434](https://github.com/user-attachments/assets/cdbc47c9-1eba-4c17-a87e-40eedfddbfad)
Simulator Monitoring Platform:
![image](https://github.com/user-attachments/assets/fb32270e-6f62-4cb1-b39a-7634dcd812df)


The connection between sensors and actuators is monitored on electronic devices through an
IoT monitor and web server accessible by typing "rustam.local" in the search bar. Conditions are
set such that when the power meter reads 2 W or higher, the lamp and thermostat are activated;
when it reads 0 W, all devices are turned off. The humidifier activates when the power meter
reads 2 W and the humidity monitor indicates 50% or higher humidity. For the AC, it operates
based on temperature, turning on when the temperature exceeds 18°C and auto and the AC is
turned off when the status is off or under 18°C.

In conclusion, the Smart Home Power Management Simulator, implemented in Cisco Packet
Tracer, emerges as a powerful tool for simulating and optimizing energy consumption within
smart home environments. By seamlessly integrating IoT devices, smart appliances, and
comprehensive energy management tools, this system establishes a realistic model capable of
monitoring and dynamically controlling energy usage patterns in real time. Overall, this
simulation underscores the potential of technology to promote sustainable energy practices and
improve living comfort in modern households
