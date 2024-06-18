# OctoTouch

![image](https://github.com/Zynth9999/OctoTouch/assets/126088340/9bd7acc9-dca2-42fb-b155-b8a458af49a3)

## Overview

**OctoTouch** is a project designed to provide an affordable and user-friendly interface for managing your 3D printer using an ESP32 touchscreen device, commonly known as The Cheap Yellow Display (CYD). This project integrates with OctoPrint to offer remote control and monitoring of your 3D printing processes.

## Features

- **Remote 3D Printer Management**: Control and monitor your 3D printer using the CYD.
- **Touchscreen Interface**: Easy to use and modern looking interface.
- **Real-Time Monitoring**: Keep track of print progress, temperatures and other parameters.
- **Open Source**: This project is open source, if you have any ideas, scroll down to check contributing.

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
   - Configure the Wi-Fi settings and OctoPrint API key in the source code.

4. **Upload the Code**:
   - Connect the CYD to your computer.
   - Flash the device using PlatformIO, if you have any issues, feel free to open an issue.

## Usage

1. **Power On the Device**:
   Once powered, the device will connect to the configured Wi-Fi network and OctoPrint server.

2. **Navigate the Interface**:
   Use the touchscreen to navigate through the menus, start/stop print jobs, and monitor the printer status.

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
