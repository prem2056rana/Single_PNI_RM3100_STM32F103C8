# Single_PNI_RM3100_STM32F103C8
markdown
Copy code
# Single_PNI_RM3100_STM32F103C8

## Overview

This project is designed to interface the PNI RM3100 magnetic sensor with an STM32F103C8 microcontroller. The RM3100 provides highly accurate magnetic field measurements, and this project demonstrates how to read and process these measurements using an STM32 microcontroller.

## Features

- **Magnetic Field Sensing**: Read magnetic field data from the RM3100 sensor.
- **Data Processing**: Process the raw data from the sensor to obtain usable magnetic field values.
- **Communication**: Uses SPI communication protocols to interface with the sensor.
- **Microcontroller**: Based on the STM32F103C8.

## Getting Started

### Prerequisites

- **Hardware**:
  - STM32F103C8 microcontroller
  - PNI RM3100 magnetic sensor
  - Development board (e.g., Blue Pill)
  - Connecting wires or PCB for connections
- **Software**:
  - STM32CubeIDE or any compatible IDE
  - STM32CubeMX for configuration
  - ARM GCC Toolchain

### Installation

1. **Clone the Repository**:
    ```sh
    git clone https://github.com/your_username/Single_PNI_RM3100_STM32F103C8.git
    cd Single_PNI_RM3100_STM32F103C8
    ```

2. **Open the Project**:
    - Open STM32CubeIDE and import the project.
    - Alternatively, use STM32CubeMX to generate the project files and then open them in your preferred IDE.

3. **Configure the Microcontroller**:
    - Set up the I2C or SPI interface in the STM32CubeMX or your IDE.
    - Configure the GPIO pins according to your hardware setup.

4. **Compile and Flash the Firmware**:
    - Compile the project in your IDE.
    - Flash the firmware onto the STM32F103C8 microcontroller using a suitable programmer (e.g., ST-Link V2).

### Usage

1. **Power up the system**.
2. **Run the firmware**.
3. **Observe the output**:
    - Use a serial monitor to read the magnetic field data output.
    - Connect to the microcontroller via UART to observe data in real-time.

### Documentation

- [RM3100 Datasheet](https://www.pnicorp.com/download/12261/)
- [STM32F103C8 Datasheet](https://www.st.com/resource/en/datasheet/stm32f103c8.pdf)
- [STM32CubeIDE User Guide](https://www.st.com/resource/en/user_manual/dm00373530.pdf)

