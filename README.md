# ATTiny-85-programmer-powered-by-Arduino
A project focussed upon creating a DIY ATtiny 85 programmer board

Attiny85 is tiny yet powerful version of arduino. Attiny85 is an 8bit microcontroller , whereas arduino is 16bit , yet it can potentially replace many arduino in many projects (as arduino is overpowered for a project's requirement in most cases)

An Attiny85 contains no direct plugin ports to be programmed , it needs another microcontroller to program it. Since I have an easy access to arduino , Arduino becomes the programmer here

This is the common circuit used to program Attiny85 with an Arduino

![Arduino-Attiny85 Circuit connection](https://external-content.duckduckgo.com/iu/?u=http%3A%2F%2Fwww.mlbelanger.com%2Fwp-content%2Fuploads%2Fattiny85-with-arduino-step3-4.jpg&f=1&nofb=1)

when implemented through breadboard, the circuit fails in 60% of the cases due to loose connectivity , hence the circuit was converted to a diy Attiny85 programmer sheidl for arduino which looks likes this :

![PCB Implementation](https://github.com/Chidhambararajan/ATTiny-85-programmer-powered-by-Arduino/blob/master/Capture.PNG?raw=true)
