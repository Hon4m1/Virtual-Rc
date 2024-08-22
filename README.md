# Virtual-Rc
A project to allow anybody to use a usb controller to drive an Rc car or boat

# Project RC G25: Controlling a Remote-Controlled Car with a Logitech G25

## 1. Understanding the Components
- **Logitech G25**: A racing wheel with pedals and a gear shifter.
- **Remote-Controlled Car (RC Car)**: The car you want to control.
- **Microcontroller**: A device like an Arduino or Raspberry Pi to interpret signals from the wheel and send them to the car.
- **RC Receiver and Transmitter**: To send commands to the remote-controlled car.

## 2. Required Materials
- **Logitech G25**
- **Remote-Controlled Car**
- **Microcontroller (Arduino, Raspberry Pi, etc.)**
- **RC Receiver and Transmitter**
- **Cables and connectors**
- **Programming software (Arduino IDE, Python, etc.)**

## 3. Implementation Steps

### a. Connect the Logitech G25 to the Microcontroller
- Use a USB interface to connect the G25 wheel to your microcontroller. You can use libraries like `pyusb` for Python or specific libraries for Arduino.

### b. Read Data from the Wheel
- Write a program to read data from the G25 wheel. You will need to capture movements of the wheel, pedals, and gear shifter.

### c. Interpret the Data
- Convert the data from the wheel into commands for the remote-controlled car. For example, wheel movements can control direction, pedals can control acceleration and braking.

### d. Send Commands to the Car
- Use the microcontroller to send the interpreted commands to the RC transmitter, which will transmit them to the remote-controlled car.
