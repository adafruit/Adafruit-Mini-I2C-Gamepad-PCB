## Adafruit Mini I2C Gamepad with seesaw and STEMMA QT PCB

<a href="http://www.adafruit.com/products/5743"><img src="assets/5743.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>

PCB files for the Adafruit Mini I2C Gamepad with seesaw and STEMMA QT. 

Format is EagleCAD schematic and board layout
* https://www.adafruit.com/product/5743

### Description

Make a game or robotic controller for any I2C microcontroller or microcomputer with this tiny gamepad breakout board. This design has a 2-axis thumb joystick and 6 momentary buttons (4 large and 2 small). The board communicates with your host microcontroller over I2C so it's easy to use and doesn't take up any of your precious analog or digital pins. There is also an optional interrupt pin that can alert your feather when a button has been pressed or released to free up processor time for other tasks.

You can use our Arduino library to control and read data with any compatible microcontroller. We also have CircuitPython/Python code for use with computers or single-board Linux boards.

To get you going fast, this board comes with a STEMMA QT connector, making them easy to interface with. The STEMMA QT connector is compatible with the SparkFun Qwiic I2C connectors. This allows you to make solderless connections between your development board and the gamepad or to chain it with a wide range of other sensors and accessories using a compatible cable and a 'hub' board. QT Cable is not included, but we have a variety in the shop.

This board features Adafruit seesaw technology - a custom programmed little helper microcontroller that takes the two analog inputs from the joystick, and 6 button inputs, and converts it into a pretty I2C interface. This I2C interface means you don't 'lose' any GPIO or analog inputs, and it works with any and all microcontrollers or microcomputers - even if they don't have an analog input for the thumbstick! 

If you have an I2C address conflict, or you want to connect more than one of these to a board, there are two address-select jumpers so you have 4 options of I2C addresses.

There's an optional IRQ (interrupt) line that you can use if you'd like the gamepad to let you know when a button has been pressed. Since its optional you will need to connect a separate wire for the IRQ line, or just leave it disconnected.

Comes with one assembled and programmed Gamepad, and some 0.1" header. If you aren't using Stemma QT cables, some soldering is required to attach the header for breadboarding.

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

Designed by Limor Fried/Ladyada for Adafruit Industries.

Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution. 
See license.txt for additional details.
