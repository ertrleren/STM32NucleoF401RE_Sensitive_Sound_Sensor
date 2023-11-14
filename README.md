# STM32NucleoF401RE_Sensitive_Sound_Sensor

<b>This project is an STM32F4 microcontroller application that reads data from a sound sensor and transmits it over UART. The data from the sensor is converted to a digital value using an ADC (analog-to-digital converter). This digital value is then transmitted using a UART (universal asynchronous receiver-transmitter).

<h2>The project consists of the following steps:</h2>

Initialization of ADC and UART: In this step, the necessary settings for ADC and UART are made.
Reading data from the sound sensor: The ADC converts the analog voltage from the sound sensor to a digital value.
Converting the sound value to Hertz: The value read from the ADC is converted to a sound value in Decibel.

<h2>Transmission of the sound value over UART: The sound value is transmitted using the serial communication port over UART.
The project works as follows:</h2>

After the microcontroller is initialized, the ADC and UART are initialized.
The microcontroller uses the ADC to read data from the sound sensor.
The read value is converted to a sound value in Decibel.
The sound value is transmitted using the serial communication port over UART.

<h2>The project can be used in the following applications:</h2>

Monitoring the sound of machines and equipment
Earthquake detection systems
Monitoring the sound of motor vehicles

<h2>Advantages of your project:</h2>

This project is a simple application that reads data from a sound sensor and transmits it over UART.
This project uses an STM32F4 microcontroller. STM32F4 microcontrollers are powerful and versatile microcontrollers.
This project uses important peripherals such as ADC and UART. ADC and UART are important peripherals used in many different applications.
This project is an open source project. Open source projects give developers more flexibility.</b>

<h2>Required Equipment</h2>
  <div class="row flex-column">
    <div class="col-md-12">
      <h3>STM32 NUCLEO F401RE</h3>
      <img src="https://github.com/ertrleren/STM32NucleoF401RE_Sensitive_Vibration_Sensor/assets/98084030/10c8da88-c6e0-47c9-9bda-014d660d565f" alt="STM32 NUCLEO F401RE" height="250" width="250">
    </div>
    <div class="col-md-12">
      <h3>801S Sound Sensor</h3>
      <img src="https://github.com/ertrleren/STM32NucleoF401RE_Sensitive_Sound_Sensor/assets/98084030/1d4fbbb3-3d6e-48dd-b195-c101b49c36f7">
" alt="801S Vibration Sensor" height="250" width="300">
    </div>
  </div>




