# Low cost, high efficiency, step-up DC-DC converter  
This is an easy and tiny way to flexible small input battery to your MCU project.
Using the [LTC3525](http://www.linear.com/product/LTC3525) you always get constant output voltage with the flexibility of a variable voltage input. Even at 1.2V as input the step-up keep >85% of the energy.

* **ultra small case 6x11mm**
* Input startup voltage min 0.7V avg at 0.85V
* External solar panel input with diode protection
* External small battery AAA 1.2V or a super capacitor
* Up to 95% Efficiency
* Output Disconnect and Inrush Current Limit
* Fixed Output Voltages of 3V, 3.3V or 5V
* Delivers 65mA at 3V from a 1V Input
* Delivers 60mA at 3.3V from a 1V Input, or 140mA at 3.3V from a 1.8V Input
* Delivers 175mA at 5V from a 3V Input
* <1μA Shutdown Current

<!-- ![efficiency](http://cds.linear.com/image/6470.png) -->

# The PCB
![The PCB board](https://raw.github.com/evaletolab/evaletolab-tiny-dcdc/master/docs/pcb.png "v0.0")


**THIS IS ALPHA SOFTWARE/HARDWARE AND SHOULD BE TREATED ACCORDINGLY.**
**IT IS FUN TO GET RUNNING, BUT EXPECT THINGS TO BE BROKEN.**
 
## License
GPL3
> Copyright (c) 2012 Olivier Evalet (http://evaletolab.ch/)

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the “Software”), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
