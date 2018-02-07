[![SHT31](SHT31_I2C.png)](https://store.ncd.io/product/sht31-humidity-and-temperature-sensor-%C2%B12rh-%C2%B10-3c-i2c-mini-module/)

# SHT31

SHT31 is the next generation of Sensirion’s temperature and humidity sensors. The SHT31 has increased intelligence, reliability and improved accuracy specifications compared to its predecessor. Its functionality includes enhanced signal processing, temperature and humidity can be read out using I2C communications.
This Device is available from www.ncd.io 

[SKU: SHT31_I2CS]

(https://store.ncd.io/product/sht31-humidity-and-temperature-sensor-%C2%B12rh-%C2%B10-3c-i2c-mini-module/)
This Sample code can be used with Arduino.

Hardware needed to interface SHT31 sensor with Arduino

1. <a href="https://store.ncd.io/product/i2c-shield-for-arduino-nano/">Arduino Nano</a>

2. <a href="https://store.ncd.io/product/i2c-shield-for-arduino-micro-with-i2c-expansion-port/">Arduino Micro</a>

3. <a href="https://store.ncd.io/product/i2c-shield-for-arduino-uno/">Arduino uno</a>

4. <a href="https://store.ncd.io/product/dual-i2c-shield-for-arduino-due-with-modular-communications-interface/">Arduino Due</a>

5. <a href="https://store.ncd.io/product/sht31-humidity-and-temperature-sensor-%C2%B12rh-%C2%B10-3c-i2c-mini-module/">SHT31 Temperature and humidity Sensor</a>

6. <a href="https://store.ncd.io/product/i%C2%B2c-cable/">I2C Cable</a>

SHT31:

SHT31 is the next generation of Sensirion’s temperature and humidity sensors. The SHT31 has increased intelligence, reliability and improved accuracy specifications compared to its predecessor. Its functionality includes enhanced signal processing, temperature and humidity can be read out using I2C communications.

Applications:

• Temperature monitoring.

• Computer peripheral thermal protection.

• Weather station applications

How to Use the SHT31 Arduino Library

The SHT31 has a number of settings, which can be configured based on user requirements.
          
1.Address calling:The following command is used to call the SHT31 sensor to begin the transmission.

          sht.getAddr_SHT31(SHT31_DEFAULT_ADDRESS);   // 0x44
            
2.Heater status:The following command is used to ENABLE the heater.

          sht.setHeaterStatus(SHT31_CMD_HEATERENABLE);          // Heater enable command
             
