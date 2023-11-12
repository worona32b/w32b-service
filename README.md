# w32b-service

W32B-Service is an evolving monitoring solution in active development, leveraging xmake and the Windows API to meticulously track battery status and CPU load on Windows-based systems. This service aims to provide users with meaningful insights into system performance, ensuring a vigilant understanding of their device's power consumption and processing capabilities.

## Features

- **Battery Monitoring:** Rigorously monitor your device's battery status, including charge levels and power source indicators (plugged in, unplugged).

- **CPU Load Monitoring:** Real-time observation of CPU load, offering detailed insights into the utilization of processing power.

- **Cross-Platform Aspirations:** While currently tailored for Windows systems, the project is designed with aspirations for future cross-platform compatibility.

- **Minimal Resource Footprint:** W32B-Service, built with xmake, is engineered for efficiency, imposing minimal demands on system resources.

## Getting Started

To integrate W32B-Service into your development environment, follow these steps:

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/worona32b/w32b-service.git
   ```

2. **Navigate to the Project Directory:**
   ```bash
   cd w32b-service
   ```

3. **Install Dependencies:**
   ```bash
   xmake
   ```

4. **Initiate the Service:**
   ```bash
   xmake run
   ```

   The service will initiate, actively monitoring battery and CPU status, providing real-time updates.

## License

This project is licensed under the MIT License. Refer to the [LICENSE](LICENSE) file for details.
