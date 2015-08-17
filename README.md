# You-Don't-Know-Robotics

This is a series of book focus into the core Robotics of the Arduino code & Javascript language.

Arduino is an open-source microcontroller, that makes interacting with objects in environments easy. Microcontrollers are everywhere, from RC/cars, electronics, robotics. This language is based on C and C++, but don't worry if you're not a programmer. This book, I will give you all the programming instructions you need. If you have prior experience with C or a similar language, you might recognize some of the commands. This book is designed for beginners and give you a taste of several types of boards available today, including boards that can be sewn into your clothing. I hope you have fun for this book.

You're have access to the Example project I use in this book from @0xgi.

In this book, we will start with the most popular board, the Arduino Uno. Throught the book, we will also explore the Leonardo, the Esplora, and the Yun.

We'll start by covering some basic information about electronic components and circuits. In addition, I'll show you how to set up your computer to talk to the Arduino, on both a Mac and a PC. Let's get You Don't Know Robotics.

## Table of contents

* [Quick start](#quick-start)

Work your project

* [Basic electronics](#basic-electronic)

A Little About Electronics

In this segment. we're gonna talk.
The question is: how does power flow throught a circuit?
For this discussion, let's start with the basics about voltage, current, and resistance. These three concepts come together in Ohm's Law, which is the key to understanding a circuit.
Ohm's Law says that be voltage is equal to the current time the resistance, where the current is measured in amps and the resistanceis measured in Ohms. When working with the Arduino in a breadboard, we will be setting up circuits. A basic circuits is a closed loop with a source of electrical energy and a load.

How to Read Resistors

A resistor resists the flow of electricity.

Led: 
+ Long leg is positive (anode)
+ Short leg is negative (cathnode)

* [Hardware arduino](#hardware-arduino)

Here is the microprocesser, the brains of the board. Every board contains a reset button, which located here. This is the USB port. Whent it is connected to a computer, it becomes the power source as well as a communication tool. Once your project is uploaded to the Arduino board, you can use an alternative power source, such as AC/DC adapter or a battery pack which plugs in here. These are the power pins and they are labeled VIN, 5V, 3V3, and ground. We'll be using 3V3, 5V and ground in our activities. The board also contains a built-in LED located here. It is attached to Pin 13 on the board, and another LED indicating when the board is on or off. These are the fourteen digital IO pins. The six digital pins with the tilde symbol next to the number are the pins that allow for pulse width modulation, a technique for controlling power and simulating and analog signal on a digital input pin. And finally, we have six analog pins located on the opposite side from the digital pins on the board. In each segment, we will talk about how to connect your flexible wires to their repective pins.

* [Configuration enviroment](#configuration-enviroment)

Let's get started by downloading the latest version of the Arduino Software from the arduino.cc website. The arduino software includes all the components you need to write code,a text editor,complie, convert to machine language, and upload to your board to run the code. This type of software is called an IDE, or an Integrated Development Environment. The download from Arduino is a free download. The Arduino software and the Arduino hardware are both considered open-source and open hardware. On the website, go to "Download". Choose your operating system. Windows, Mac OS X, or Linux. For example, I'm gonna choose the Linux installer.

After the installation, you can see that Arduino put a shortcut on my desktop. I can use this to launch the IDE. The install of the Arduino IDE is pretty simple. Before we start programing, we need to give our computer some information about the hardware we wanna use. Such as the Arduino board. We need to install a driver. The good thing is, this only needs to be done once when you first start using your new board. If you're using Linux, connect the Arduino and your computer using the USB cord. I'm gonna do that now. You'll notice that the driver installation is starting. After a few moments, the process will probably fail despite its best effort, but this is expected.

Okay, we have the IDE, we have drivers installed, let's get started on programming. 

* [Arduino code](#arduino-code)

When you launch the Arduino executable, it automatically provides you with an empty sketch. Using the date as a file name, such as 0xgi_my12.

Since the microprocessor is limited in size, you need to make sure sketch does not exceed the limit of your board. It's always a good programming practice to verify your code before uploading it to your board. This finds any problems with the syntax of your sketch. Go ahead and give this a try.

* [Javascript code](#javascript-code)
* [Arduino with Javascript](#arduino-with-javascript)
* [Documentation](#documentation)
* [Contributing](#contributing)
* [Community](#community)
* [Versioning](#versioning)
* [Creators](#Creators)
* [Copyright and license](#copyright-and-license)



