## Tools
- 3D printer (PETG and PLA capable)
- Soldering iron with fine tip
- Solder
- Wire strippers
- Small Phillips head screwdriver set
- M3 hex key
- Multimeter
- Hot glue gun (optional, for securing wires)
- Deburring tool (for 3D prints)
- Pliers/Cutters (for support removal)

## Assumptions
- Basic soldering experience
- Familiarity with 3D printing and post-processing
- Understanding of basic electronics wiring and safety
- Access to a computer with Raspberry Pi OS/Linux environment for software development
- Arduino IDE or PlatformIO installed for ESP32 programming
- Appropriate small gauge wiring for electrical connections
- Knowledge of GPIO pinouts for Raspberry Pi 5 and ESP32

## 1. Fabrication
### 1.1 Print all 3D mechanical components and mounts
*(not yet generated)*

### 1.2 Install M3 brass heat-set inserts into all designated mounting points
*(not yet generated)*

### 1.3 Mount eye LEDs, camera, PIR sensor, microphone, and speaker into their respective 3D printed mounts
*(not yet generated)*

### 1.4 Mount Raspberry Pi 5, ESP32, TP4056 module, voltage regulator, cooling fan, power switch, WiFi antenna, and audio amplifier to their dedicated 3D printed mounts
*(not yet generated)*

### 1.5 Attach all servo motors to their specific 3D printed mounts
*(not yet generated)*

### 1.6 Insert 18650 batteries into the battery tray
*(not yet generated)*

## 2. Wiring
### 2.1 Connect 18650 batteries in series to the TP4056 charging module and to the power slide switch
*(not yet generated)*

### 2.2 Wire the power slide switch output to the buck-boost converter input
*(not yet generated)*

### 2.3 Connect the buck-boost converter output to the Raspberry Pi 5, ESP32, PIR sensor, microphone, cooling fan, audio amplifier module, and all servo motors
*(not yet generated)*

### 2.4 Connect the Raspberry Pi Camera Module 3 to the Raspberry Pi 5 MIPI CSI port
*(not yet generated)*

### 2.5 Wire Raspberry Pi 5 UART to ESP32 UART (TX/RX cross-connection)
*(not yet generated)*

### 2.6 Connect the cooling fan PWM input to Raspberry Pi 5 GPIO, and the PIR motion sensor output and microphone analog output to ESP32 GPIO pins
*(not yet generated)*

### 2.7 Connect eye LEDs and all servo motor PWM inputs to designated ESP32 GPIO pins
*(not yet generated)*

### 2.8 Wire Raspberry Pi 5 I2S output to the audio amplifier module input, and connect the amplifier output to the speaker
*(not yet generated)*

## 3. Bring-up
### 3.1 Verify power distribution and voltage levels from buck-boost converter to all components using a multimeter
*(not yet generated)*

### 3.2 Flash ESP32 with initial firmware for GPIO control and communication with RPi5, and test eye LED functionality
*(not yet generated)*

### 3.3 Install Raspberry Pi OS on RPi5, enable camera, I2S, and UART interfaces, and test camera video feed
*(not yet generated)*

### 3.4 Develop and test basic Python scripts on RPi5 to communicate with ESP32 via UART, and control the cooling fan
*(not yet generated)*

### 3.5 Test PIR motion sensor and microphone input on ESP32, and verify data transfer to RPi5
*(not yet generated)*

### 3.6 Test audio playback through RPi5 I2S to audio amplifier and speaker
*(not yet generated)*

### 3.7 Develop and test basic servo control code on ESP32 for head and wing movements, ensuring correct PWM signals and range of motion
*(not yet generated)*

## 4. Assembly
### 4.1 Mount the Raspberry Pi 5 assembly and ESP32 assembly into the lower body shell
*(not yet generated)*

### 4.2 Mount the battery tray, TP4056 module, voltage regulator module, audio amplifier, and power switch assemblies into the lower body shell, connecting the battery door
*(not yet generated)*

### 4.3 Assemble the head by joining the left and right halves, securing eye LED, camera, microphone, and head servo mounts
*(not yet generated)*

### 4.4 Mount the PIR sensor, cooling fan, and WiFi antenna assemblies into the upper body shell
*(not yet generated)*

### 4.5 Attach the head assembly to the upper body shell, ensuring proper routing of camera and servo cables
*(not yet generated)*

### 4.6 Assemble the left and right wings by mounting the inner and outer servo mechanisms to the wing parts, then attach the complete wings to the upper body shell
*(not yet generated)*

### 4.7 Secure the tail section to the upper body shell
*(not yet generated)*

### 4.8 Join the upper and lower body shells, route and secure all internal wiring, and finally attach the base and legs assembly
*(not yet generated)*
