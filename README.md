# Getting Started with Raspberry Pi Pico WH and Socket Connections

As we move forward into IoT, we will work with another board: the [Raspberry Pi Pico WH](https://www.raspberrypi.com/documentation/microcontrollers/raspberry-pi-pico.html#raspberry-pi-pico-w-and-pico-wh).

In this assignment, you will start getting to know the Pico and also connect it to your computer using a socket connection over WiFi.

Note that if you are completing this assignment outside ALIC, you will need to bring the following items with you:

- Your laptop
- Your Pico and breadboard
- Your USB data cable
- One LED light
- A resistor with 300Ω or more

## References

- [Pico Pinout](https://datasheets.raspberrypi.com/picow/PicoW-A4-Pinout.pdf?_gl=1*1hl5e8g*_ga*MzUyNDQ3NTAwLjE3MDg0NTU5MjE.*_ga_22FD70LWDS*MTcxMDE5NDYzMy4zLjAuMTcxMDE5NDYzMy4wLjAuMA..)
- [Pico Digital Inputs and Outputs](https://projects.raspberrypi.org/en/projects/getting-started-with-the-pico/6)
- [Socket Tutorial](https://projects.raspberrypi.org/en/projects/get-started-pico-w/0)

## Steps

1.  [Follow this tutorial.](https://projects.raspberrypi.org/en/projects/get-started-pico-w/0) The tutorial covers how to connect your Pico to WiFI and open a socket so that you can control it from a web browser. It shows you how to use the Pico's onboard temperature sensor to write the temp to a web page, and also how to control its on-board LED light from that same web page. Here are few notes to take into account while you follow the tutorial:

    - The code in the tutorial requires a simple WiFI connection with network and password. Since Allegheny internet uses certificate authentication, you may need to complete this assignment in Alden using the CIS network. 
    - The tutorial uses the Thonny IDE instead of Arduino Lab. You can use Arduino Lab instead, or you can download Thonny if you have the space for it and would like to test out a different IDE.
    - If you don't download Thonny, you'll need to download the `picozero` library from [the source](https://raw.githubusercontent.com/RaspberryPiFoundation/picozero/master/picozero/picozero.py?token=GHSAT0AAAAAABRLTKWZCT53CGKBFHMJGE54YSC762A) and save it to `lib/picozero.py` on your Pico. 

2. Adjust the code from the tutorial to convert the temperature displayed from Celsius to Fahrenheit.

3. Connect an external LED light to the Pico. Adjust the code so the new LED turns on when the user clicks the "Light On" button. Use [the references](https://projects.raspberrypi.org/en/projects/get-started-pico-w/0) above to complete this step. Be sure to use at least 300Ω resistance. 

4. When you are finished, show the professor your Pico working to receive credit for this assignment. (You can also email the professor a video.)
