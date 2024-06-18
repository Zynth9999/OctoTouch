
# OctoTouch

![image](https://github.com/Zynth9999/OctoTouch/assets/126088340/9bd7acc9-dca2-42fb-b155-b8a458af49a3)

## Overview

**OctoTouch** is a project designed to provide an affordable and user-friendly interface for managing your 3D printer using an ESP32 touchscreen device, commonly known as The Cheap Yellow Display (CYD). This project integrates with OctoPrint to offer remote control and monitoring of your 3D printing processes.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [Powering the Device](#powering-the-device)
- [Screens](#screens)
  - [Home Screen](#home-screen)
  - [Settings Screen](#settings-screen)
- [Contributing](#contributing)
- [Acknowledgements](#acknowledgements)
- [Contact](#contact)
## Features

- **Remote 3D Printer Management**: Control and monitor your 3D printer using the CYD.
- **Touchscreen Interface**: Easy to use and modern looking interface.
- **Real-Time Monitoring**: Keep track of print progress, temperatures and other parameters.
- **Open Source**: This project is open source, if you have any ideas, scroll down to check contributing.
- **Status bar**: Indicating WiFi connectivity, and temperatures.
- **Toolhead Control**: Control your toolhead's position with 1mm or 10mm steps.
- **Customizable Settings**: Wide rage of CYD lcd settings.
- **Updating**: Planned support for SD and OTA updates.

## Getting Started

### Prerequisites

Before you begin, ensure you have met the following requirements:

- An ESP32 development board
- The [Cheap Yellow Display](https://github.com/witnessmenow/ESP32-Cheap-Yellow-Display) (CYD) touchscreen
- A 3D printer with OctoPrint installed and configured
- A computer with PlatformIO installed

### Installation

1. **Clone the Repository**:

   ```git clone https://github.com/Zynth9999/OctoTouch.git```
   
   ```cd OctoTouch```

2. **Install Required Libraries**:
   Make sure you have the necessary libraries installed in PlatformIO.

3. **Configure the Project**:
   - Open the project in your development environment.
   - Configure the Wi-Fi settings and OctoPrint API key in the conf.h file, or use the online configuration file generator.

4. **Upload the Code**:
   - Connect the CYD to your computer.
   - Flash the device using PlatformIO, if you have any issues, feel free to open an issue.

## Usage

1. **Power On the Device**:
   Once powered, the device will connect to the configured Wi-Fi network and OctoPrint server.

2. **Navigate the Interface**:
   Use the touchscreen to navigate through the menus, start/stop print jobs, and monitor the printer status.
## Powering the device
**Powering via USB**
1. Connect a USB cable to a power source or a computer.
2. On the end of the cable, plug in your CYD.
3. Ensure that the display powers on, and if the flash was succesful by checking if you see a Screen prompting you to click.

**Powering via the JST 1.25 4-Pin**
This may be used as an alternative for powering the CYD, you can somehow integrate it into your printer mainboard. If anyone knows how to do that, please open an issue :)
![image](https://raw.githubusercontent.com/Zynth9999/OctoTouch/main/power-pinout.png)
1. Locate the JST connector, typically situated next to the USB slot.
2. Ensure that the text next to it contains: *VIN, TX, RX, GND*
3. Plug in the JST connector that came with your CYD.
4. Connect the other end with the broken out wires to a power source.


## Screens
**Top bar**: Displays WiFi status and temperatures. (VISIBLE ON ALL SCREENS)
### Home screen
-**Home (Tab 1)**: Overview of the printing process, data like temperatures, estimated time, time elapsed, gcode file name, and other general information.
-**Temperatures (Tab 2)**: On this tab, you will find buttons for temperature controls, as well as the target temperature and current real temperature.
-**Control tab (Tab 3)**: Here, you can home the toolhead, control the positions by 1mm or 10mm increments using 4 buttons *(Planned support for a touchable region for the control)*. If printer is idle, show a list of gcode files that OctoPrint recognizes, then click them to start printing.

### Settings screen
-**LCD Settings**: Change the brightness (backlight) intensity. Invert colors (Should be done automaticaly when flashing with PIO). Set sleep time, which adjusts the inactivity timer, if set to -1, the screen will never sleep (NOT RECOMMENDED! COULD CAUSE BURN-IN).



## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature/your-feature`).
6. Open a pull request.

I check pr's quite frequently!
## Acknowledgements

- Thanks to the developers of OctoPrint for, well OctoPrint itself.
- Special thanks to [chunkysteveo for his OctoPrintAPI repository](https://github.com/chunkysteveo/OctoPrintAPI)!

## Contact

For more information, DM me on discord! ```@zynthrodak```
