LM35 TEMPERATURE SENSOR AND LCD INTERFACING WITH ARDUINO UNO

            The temperature sensor LM35  and Lcd display is connected to Arduino UNO.LM35 reads the current roomm temperature and the temperature is displayed on the Lcd .
            
COMPONENTS USED

1.Temperature sensor -LM35
2.resistor -1k ohm 
3.Arduino UNO
4.Connecting wires            



CONNECTION

The LM35 Sensor has 3 pins, Ground, VCC, Input. The Ground and the VCC pins of the sensor needs to be connected to the Ground and the 5 volts pins on the Arduino Board respectively and input pin to A0 of arduino .

RS pin of LCD connects to digital pin 12 of Arduino UNO.
Pin E (Enable) connected to digital pin 11.
Pin D4 connects to pin number 5.
D5 pin connects to digital pin 4 of Arduino.
Pin D6 connects to digital pin 3.
Pin D7 connects to digital pin 2 of Arduino UNO.
R / W pin connected to the GND.
Pin 1 and pin 4 are connected to GND.
Pin 2 connected to + VCC.
       
cconnect one leg of the 1k ohm resistor to pin 3 of lcd and other leg to GND .

![WhatsApp Image 2023-04-20 at 9 26 57 PM](https://user-images.githubusercontent.com/127237854/233421900-ea3cfcd4-a9ab-4cd8-9fcc-ab430507573e.jpeg)
