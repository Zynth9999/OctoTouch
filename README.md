# OctoTouch

![image](https://github.com/Zynth9999/OctoTouch/assets/126088340/9bd7acc9-dca2-42fb-b155-b8a458af49a3)

## Overview

**OctoTouch** is a project designed to provide an affordable and user-friendly interface for managing your 3D printer using an ESP32 touchscreen device, commonly known as The Cheap Yellow Display (CYD). This project integrates with OctoPrint to offer remote control and monitoring of your 3D printing processes.

## Features

- **Remote 3D Printer Management**: Control and monitor your 3D printer using the CYD device.
- **Touchscreen Interface**: Intuitive and easy-to-use interface for managing print jobs, adjusting settings, and viewing status.
- **Real-Time Monitoring**: Keep track of print progress, temperatures, and other critical parameters.
- **Open Source**: Built on open-source technologies, making it easy to customize and extend.

## Getting Started

### Prerequisites

Before you begin, ensure you have met the following requirements:

- An ESP32 development board
- The Cheap Yellow Display (CYD) touchscreen
- A 3D printer with OctoPrint installed and configured
- A computer with the Arduino IDE or PlatformIO installed

### Installation

1. **Clone the Repository**:

   ```git clone https://github.com/Zynth9999/OctoTouch.git```
   
   ```cd OctoTouch```

2. **Install Required Libraries**:
   Make sure you have the necessary libraries installed in your Arduino IDE or PlatformIO.

3. **Configure the Project**:
   - Open the project in your development environment.
   - Configure the Wi-Fi settings and OctoPrint API key in the source code.

4. **Upload the Code**:
   - Connect your ESP32 to your computer.
   - Compile and upload the code to the ESP32.

5. **Connect the CYD**:
   - Connect the CYD touchscreen to the ESP32 following the wiring diagram provided in the documentation.

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

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

- Thanks to the developers of OctoPrint for their amazing software.
- Special thanks to the open-source community for their contributions and support.

## Contact

For more information, DM me on discord! ```@zynthrodak```
