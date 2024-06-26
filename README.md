# Ping Pong Game

| | |
|-|-|
|`Author` | Barbulescu Alexandru

## Description This project implements a ping pong game displayed on an OLED screen using Arduino UNO. Players control the paddles using analog joysticks, and a buzzer provides audio feedback during gameplay.

## Motivation The motivation behind this project was to create an interactive and entertaining game using Arduino and OLED display technology.

## Architecture  Microcontroler Arduino Uno - Display - Input Devices - Buzzer  UI

### Block diagram

<!-- Make sure the path to the picture is correct -->
![Block Diagram](schematics/block_diagram.png)

### Schematic

![e01261d0-9b86-4e7e-a520-55756d98b271](https://github.com/UPB-FILS-AM-FR/am-projet-BarbulescuAlexandru/assets/161452707/becb0c96-5a0b-4ccb-8a8f-eb9d909bec17)
![WhatsApp Image 2024-05-27 at 1 13 15 AM](https://github.com/UPB-FILS-AM-FR/am-projet-BarbulescuAlexandru/assets/161452707/ab71cd54-95e0-47d8-ae5c-5144c8fc64d0)
![WhatsApp Image 2024-05-27 at 1 13 11 AM](https://github.com/UPB-FILS-AM-FR/am-projet-BarbulescuAlexandru/assets/161452707/fdec7721-c869-424c-b140-c13648116d29)


### Components


<!-- This is just an example, fill in with your actual components -->

| Device | Usage | Price |
|--------|--------|-------|
|Uno R3 ATmega328P| Uno R3 ATmega328P| [45 RON](https://www.emag.ro/placa-dezvoltare-uno-r3-atmega328p-cl201/pd/DPF3WJBBM/?cmpid=87002&utm_source=google&utm_medium=cpc&utm_campaign=(RO:Whoop!)_3P-Y)
| Activ Buzzer | Buzzer | [2 RON](https://www.emag.ro/buzzer-activ-5v-compatibil-arduino-raspberry-oky0151/pd/D7KJNNMBM/) |
| Oled| Display| [20 RON](https://www.emag.ro/afisaj-grafic-oled-128-x-64-px-spi-0-96-inch-multicolor-oled-096-spi-white/pd/DPZ798MBM/?cmpid=93116&utm_source=google&utm_medium=cpc&utm_campaign=(RO:eMAG!)_3P_NO_SALES_>_Jucarii_hobby&utm_content=111476631565&gad_source=1&gclid=CjwKCAjw3NyxBhBmEiwAyofDYdepSTpZeJRHLUfylAz0D0FFH1Qy-MPPTZx9lRWG9SpZlBKYltj9VxoCex4QAvD_BwE) |
| Breadboard | Project board | [13 RON](https://www.emag.ro/placa-test-breadboard-830-bb830/pd/D6SCSBMBM/?cmpid=87002&utm_source=google&utm_medium=cpc&utm_campaign=(RO:Whoop!)_3P-Y_>_Jucarii_hobby&utm_content=79559830074&gad_source=1&gclid=CjwKCAjw3NyxBhBmEiwAyofDYTk4lSftqBm5HNeuwBGRkPJC57FY5b366KsxQx3y0N8XTKtlN85YIhoCavAQAvD_BwE) 

### Libraries

<!-- This is just an example, fill in the table with your actual components -->

| Library | Description | Usage |
|---------|-------------|-------|
| Adafruit_SSD1306.h | For display.  |
| <Adafruit_GFX.h> | This is the core graphics library for all our displays, providing a common set of graphics primitives (points, lines, circles, etc.).  |
| <Wire.h>|  This is an I2C communications library that facilitates two-wire class communications with I2C/TWI devices |
|  <SPI.h> | The Serial Peripheral Interface (SPI) driver is a generic, full-duplex driver that transmits and receives data on a SPI bus. | 

## Log

<!-- write every week your progress here -->

### Week 6 - 12 May

### Week 7 - 19 May

### Week 20 - 26 May


## Reference links

<!-- Fill in with appropriate links and link titles -->

[Tutorial 1](https://www.youtube.com/watch?v=wdgULBpRoXk&t=1s&ab_channel=BenEater)

[Article 1](https://www.explainthatstuff.com/induction-motors.html)

[Link title](https://projecthub.arduino.cc/)
