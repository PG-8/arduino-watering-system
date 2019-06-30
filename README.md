# Arduino Uno clone watering system

This repo's purpose is to showcase a prototype I've built to automatically water a plant using an Arduino Uno clone and a small 12V water pump.

**The completed prototype:**

![](https://media.giphy.com/media/dZXA61X1MG99LhhaA6/giphy-downsized-large.gif)

The prototype runs its code for 10 seconds activating the pump which takes water from the bucket and pumps it back into the container. For testing purposes the code was set to run every other minute, however, when in "production", it can be set to any preferred value. (eg. 12-24h cycles to water the plant once or twice a day)

**Pros:**

- It works and can be left unsupervised for a few days (Onlyh after isolating all exposed circuits, because as you can see in the video they are not, which makes it a fire hazard)
- Learned a lot about microcontrollers and electronics
- Easy to setup with humidity, brightness, temperature sensors (but overkill if you can just water the plant every 24 hours for 10 seconds)

**Cons:**

- Can water only one plant effectively
- It will most likely stay a prototype
- Can't trust it in the long run as it can't automatically refill its own tank (water finishes in a few days due to evaporation and usage)

__________________________________________________________________________________________________________

**Software:**
* Arduino IDE

**Hardware and tools:**
* Arduino Uno or equivalent clone
* Water pump (5V or 9V or 12V)
* Transistor
* Breadboard
* Jumper wires
* Breadboard
* Silicon tubes
* Bucket
* 9V battery
* Scissors
* Soldering iron

**Optional:**
* Temperature sensor
* Brightness sensor
* Humidity sensor

__________________________________________________________________________________________________________

**Sketches from plannig:**

> ![Sketch 0](https://github.com/PG-8/arduino-watering-system/blob/master/Sketch0.jpg)
> ![Sketch 1](https://github.com/PG-8/arduino-watering-system/blob/master/Sketch1.jpg)
> ![Sketch 2](https://github.com/PG-8/arduino-watering-system/blob/master/Sketch2.jpg)
> ![Sketch 3](https://github.com/PG-8/arduino-watering-system/blob/master/Sketch3.jpg)
