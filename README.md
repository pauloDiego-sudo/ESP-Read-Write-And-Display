# ESP Read Write and Display

This project aims to demonstrate how to read and write data from a SPIFFS partition using an ESP microcontroller and display it on a OLED module.

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/pauloDiego-sudo/ESP-Read-Write-And-Display.git
    ```

## Usage

1. Connect the ESP microcontroller to your computer.

2. Build the code using PlataformIO:

    ```bash
    pio run
    ```

3. Upload the code to the ESP microcontroller using PlatformIO:

    ```bash
    pio run --target upload
    ```

4. Open the serial monitor to view the data being read and written:

    ```bash
    pio device monitor
    ```

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.
