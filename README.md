# Diy-OTTO-Robot

![Screenshot (1056)](https://user-images.githubusercontent.com/118633170/230275123-f8d824b7-f23a-4f75-b4a5-c7f08cd705ce.png)

If you have hard-time 3d printing stuff and other materials which i have provided in this project please refer the professionals for the help, [JLCPCB](https://jlcpcb.com/RNA) is one of the best company from shenzhen china they provide, PCB manufacturing, PCBA and 3D printing services to people in need, they provide good quality products in all sectors

[JLCPCB](https://jlcpcb.com/RNA)


Please use the following link to register an account in [JLCPCB](https://jlcpcb.com/RNA)

https://jlcpcb.com/RNA


Pcb Manufacturing

----------

2 layers

4 layers

6 layers

jlcpcb.com/RNA



PCBA Services

[JLCPCB](https://jlcpcb.com/RNA) have 350k+ Components In-stock. You don’t have to worry about parts sourcing, this helps you to save time and hassle, also keeps your costs down.

Moreover, you can pre-order parts and hold the inventory at [JLCPCB](https://jlcpcb.com/RNA), giving you peace-of-mind that you won't run into any last minute part shortages. jlcpcb.com/RNA

3d printing

-------------------

SLA -- MJF --SLM -- FDM -- & SLS. easy order and fast shipping makes [JLCPCB](https://jlcpcb.com/RNA) better companion among other manufactures try out [JLCPCB](https://jlcpcb.com/RNA) 3D Printing servies

[JLCPCB](https://jlcpcb.com/RNA) 3D Printing starts at $1 &Get $54 Coupons for new users

![Screenshot (1060)](https://user-images.githubusercontent.com/118633170/230275211-bc629bcf-065a-4965-88b8-faa2dbf00985.png)
![Screenshot (1058)](https://user-images.githubusercontent.com/118633170/230275225-06bd8c35-2ccd-4ee3-b5ca-65cc03909523.png)
![Screenshot (1059)](https://user-images.githubusercontent.com/118633170/230275235-f3230c77-0c22-4134-9563-b7a279ca6b0b.png)


The machines and projects must include the following features:

• use an Arduino microcontroller board (UNO, Leonardo, 101);

• request at least the use of an input sensor;

• generate at least one output interfacing with the real world, which can be visual (LED, screens) or physical (moving motors);

• use at least one device not explained in class, it can be a sensor or a motor and its pilot card.

The project we decided to build is a toy bipedal robot (taking the "Otto DIY" open source project as an example) able to walk and turn around using an Arduino board which is controlled by IR signals sent by another Arduino board (which will work as a remote control). 


Introduction
In this report we will explain the operation of a bipedal robot driven by

microcontrollers and controlled by a remote, able to walk and turn around.

Goal
The machines and projects must include the following features:

• use an Arduino microcontroller board (UNO, Leonardo, 101);

• request at least the use of an input sensor;

• generate at least one output interfacing with the real world, which can be visual (LED, screens) or physical (moving motors);

• use at least one device not explained in class, it can be a sensor or a motor and its pilot card.

The project we decided to build is a toy bipedal robot (taking the "Otto DIY" open source project as an example) able to walk and turn around using an Arduino board which is controlled by IR signals sent by another Arduino board (which will work as a remote control).

Used Material
The components necessary for the realization of the project are the following ones:

2x Microcontroller (Arduino UNO, Elegoo Nano);
4x Micro servo SG90;
IR LED;
IR receiver VS1838B;
joystick module;
100Ω resistance;
Arduino nano expansion board;
Jumper cables;
PLA pieces (obtained by 3D printing).
The printed pieces’ 3D drawing files were downloaded from the website “Thingiverse”, as “Otto DIY” is an open source project. 

![Screenshot (1063)](https://user-images.githubusercontent.com/118633170/230275279-d695ae1d-875d-46ee-b691-12cd164ed4c6.png)
![Screenshot (1061)](https://user-images.githubusercontent.com/118633170/230275300-76892285-d358-4546-bbf7-077ce642436c.png)
![Screenshot (1062)](https://user-images.githubusercontent.com/118633170/230275305-29be3259-7351-4a4f-bd05-4f43f284e624.png)

The servos and the IR receiver don’t require any resistance as it’s integrated in the components.

To make the robot’s wirings easier we mounted the Elegoo Nano on an expansion board.

Functioning
To make the bipedal robot we used 2 microcontrollers.

The first one is an Elegoo Nano board connected to the joystick module and to the IR LED to assume the function of a remote control: it calculates the position of the joystick to understand where the robot has to go (so, which code has to be sent).

The second microcontroller is the “mind” of the robot: it controls the movements of the 4 servos based on the infrared signals received by the sensor. The operation of both devices are described in the following flowcharts. 

An open-source modular robot with an epic personality. It means the hardware is easily discerned so that others can make it, is also Arduino compatible, 3D printable and customizable. Otto was inspired by another robot instructible BoB the BiPed and programmed using code from another open-source biped robot called Zowi. Otto robot walks, dances, makes sounds and avoids obstacles, easy to program and expand or customize, you will learn the logical connection between code and action, and by assembling it, you will understand how its components and electronics work. The motive of making the project cost efficient and user friendly is taken into account and achieved.

![Screenshot (1064)](https://user-images.githubusercontent.com/118633170/230275371-d50a6f85-53c8-4aa5-99cd-a9e1e33b1579.png)
![Screenshot (1065)](https://user-images.githubusercontent.com/118633170/230275379-30153fa4-0b2e-4f95-986b-06c2541e49a0.png)

The project is comprised of components such as an Arduino Nano, Arduino Nano Shield, Ultrasonic Sensor, Servo Motors, and Otto robot body parts. Keywords— component: Otto Robot Body Parts, Arduino Nano, Arduino Nano Shield I/O, USB-A to Mini-USB Cable, SG90 Micro-servo motor, Ultra-sound sensor HC-SR04, Buzzer, Female/Female jumper wire, Toggle switch, 4 x AA Battery holder AA Battery.

Arduino is an open-source computer hardware and software company, project, and user community that designs and manufactures single-board microcontrollers and microcontroller kits for building digital devices and interactive objects that can sense and control objects in the physical and digital world. The project's products are distributed as open-source hardware and software, which are licensed under the GNU Lesser General Public License (LGPL) or the GNU General Public License (GPL), permitting the manufacture of Arduino boards and software distribution by anyone. Arduino boards are available commercially in preassembled form, or as do-it-yourself (DIY) kits.

Arduino board designs use a variety of microprocessors and controllers. The boards are equipped with sets of digital and analog input/output (I/O) pins that may be interfaced to various expansion boards or Breadboards (shields) and other circuits. The boards feature serial communications interfaces, including Universal Serial Bus (USB) on some models, which are also used for loading programs from personal computers. The microcontrollers are typically programmed using a dialect of features from the programming languages C and C++. In addition to using traditional compiler toolchains, the Arduino project provides an integrated development environment (IDE) based on the Processing language project. Arduino Nano is one type of microcontroller board, and it is designed by Arduino.cc. It can be built with a microcontroller like Atmega328. This microcontroller is also used in Arduino UNO. It is a small size board and also flexible with a wide variety of applications.
![Screenshot (1066)](https://user-images.githubusercontent.com/118633170/230275424-5af20026-1237-4bdb-96aa-16c60798a643.png)
![Screenshot (1067)](https://user-images.githubusercontent.com/118633170/230275440-595e42b1-a798-42b5-98a6-76f46ede45fb.png)

![Screenshot (1068)](https://user-images.githubusercontent.com/118633170/230275406-9223d4c8-a33f-4107-837e-4bebf443fd8a.png)

In essence, it expands the Nano controller to link those devices in a simple and trouble-free manner. It is a perfect companion of Nano breadboard and compatible with both Nano v2.x and v3.x. This expansion shield provides:  14 I/O Pin (servo type with GND, power and signal)  8 analog Pin with power output and GND  6 PWM Pin  1 Servo power input  5 I2C expansion Pin  AREF output  3.3V output # Arduino Software part: 1. IDE: The Arduino integrated development environment (IDE) is a cross-platform application (for Windows, macOS, Linux) that is written in the programming language Java. It originated from the IDE for the languages Processing and Wiring.

It includes a code editor with features such as text cutting and pasting, searching and replacing text, automatic indenting, brace matching, and syntax highlighting, and provides simple one-click mechanisms to compile and upload programs to an Arduino board. It also contains a message area, a text console, a toolbar with buttons for common functions and a hierarchy of operation menus. The source code for the IDE is released under the GNU General Public License, version 2. The Arduino IDE supports the languages C and C++ using special rules of code structuring. The Arduino IDE supplies a software library from the Wiring project, which provides many common input and output procedures. User-written code only requires two basic functions, for starting the sketch and the main program loop

A program written with the Arduino IDE is called a sketch. Sketches are saved on the development computer as text files with the file extension.ino. Arduino Software (IDE) pre-1.0 saved sketches with the extension.pde. 3. C/C++ program: A minimal Arduino C/C++ program consist of only two functions: setup (): This function is called once when a sketch starts after power-up or reset. It is used to initialize variables, input and output pin modes, and other libraries needed in the sketch. loop (): After setup () has been called, function loop () is executed repeatedly in the main program. It controls the board until the board is powered off or is reset.

The HC-SR04 uses non-contact ultrasound sonar to measure the distance to an object, and consists of two ultrasonic transmitters (basically speakers), a receiver, and a control circuit. The transmitters emit a high frequency ultrasonic sound, which bounce off any nearby solid objects, and the receiver listens for any return echo. That echo is then processed by the control circuit to calculate the time difference between the signal being transmitted and received. This time can subsequently be used, along with some clever math, to calculate the distance between the sensor and the reflecting object! The HC-SR04 sensor works best between 2cm – 400 cm (1" - 13ft) within a 30-degree cone, and is accurate to the nearest 0.3cm The features of the HC-SR04 sensor include the following:  The power supply used for this sensor is +5V DC  Dimension is 45mm x 20mm x 15mm  Quiescent current used for this sensor is <2mA  The input pulse width of trigger is10uS  Operating current is 15mA  Measuring angle is 30 degrees  The distance range is 2cm to 800 cm  Resolution is 0.3 cm  Effectual Angle is <15°  Operating frequency range is 40Hz

![Screenshot (1070)](https://user-images.githubusercontent.com/118633170/230275479-cde25734-c99c-43f5-b45c-1e49c774df5c.png)
![Screenshot (1069)](https://user-images.githubusercontent.com/118633170/230275489-854036f0-06f2-44a6-96dd-8b74d53b8edb.png)

SG90 Micro-servo motor: Servo motors (or servos) are self-contained electric devices that rotate or push parts of a machine with great precision. The simplicity of a servo is among the features that make them so reliable. The heart of a servo is a small direct current (DC) motor, similar to what you might find in an inexpensive toy. These motors run on electricity from a battery and spin at high RPM (rotations per minute) but put out very low torque. An arrangement of gears takes the high speed of the motor and slows it down while at the same time increasing the torque.

The gear design inside the servo case converts the output to a much slower rotation speed but with more torque (big force, little distance). Servo can rotate approximately 180 degrees (90 in each direction), and works just like the standard kinds but smaller. You can use any servo code, hardware or library to control these servos. Features:  Weight: 9 g  Dimension: 22.2 x 11.8 x 31 mm approx.  Stall torque: 1.8 kgf.cm  Operating speed: 0.1 s/60 degree  Operating voltage: 4.8 V (~5V)  Dead band width: 10 µs  Temperature range: 0 ºC – 55 ºC Position "0" (1.5 ms pulse) is middle, "90" (~2 ms pulse) is all the way to the right. -90" (~1 ms pulse) is middle, "90" (~2 ms pulse) is all the way to the left. 

A toggle switch is a type of electrical switch that is actuated by moving a lever back and forth to open or close an electrical circuit. There are two basic types: maintained contact and momentary toggle switches. A maintained switch changes its position when actuated and will remain in that position until actuated again, such as an ON/OFF function. A momentary toggle switch is actuated only when someone is operating the switch. Toggle switches with different actuator styles and amperage ranging from 3 to 20 amps, as well as different load-carrying capabilities and locking combinations.

Application: Otto is open-source user friendly project. Also, Arduino compatible, 3D printable and customizable, the perfect opportunity to build and have your very first robot, learn robotics, STEM and have fun, you will learn the logical connection between code and action, and by assembling it, you will understand how its components and electronics work. Otto robot walks, dances, makes sounds and avoids obstacles, easy to program and expand or customize. Result: With the procedures mentioned, the implementation of the project “Otto DIY using the Arduino Nano Microcontroller” is successfully completed and implemented. The project is cost efficient and user friendly because it can be used by anyone.

Limitations and Problems Encountered: This project encountered certain difficulties that are described below. Initially, when all the connections were done, the major problem was the connection between the Servo Motors and the Arduino Nano. If the servos are connected with wrong pin, then it won’t move correctly. A second problem was also encountered with installing Arduino Nano with Arduino Nano Shield and Ultra-Sound sensor in Head part.

Future work and Upgrade: The current project presented the implementation of an inexpensive Otto DIY mini robot, within the framework of assistive technology. The system implementation is based on the Arduino microcontroller.

Open Arduino IDE and navigate to Sketch > Include Library > Add .ZIP Library. At the top of the drop down list, select the option to "Add .ZIP Library".
Navigate to the .zip file's location, that you just downloaded and open it.
In the main window you will see in the bottom back area a message that it has been installed.
To verify they are properly installed, go to Sketch > Include Library menu. You should now see the library at the bottom of the drop-down menu.
That means it is ready to use Otto example codes! you can find them in File

You can also find this library in the Arduino Manager as Otto DIYLib for quick installation, (do not use other non compatible libraries).
![Screenshot (1071)](https://user-images.githubusercontent.com/118633170/230275532-fccacee3-17af-4b53-a6db-640b5181ff96.png)
![Screenshot (1072)](https://user-images.githubusercontent.com/118633170/230275545-9f3ec8db-a0e5-45d1-950f-069266ff39c0.png)
![Screenshot (1073)](https://user-images.githubusercontent.com/118633170/230275521-582403af-ab04-4a6f-b333-1fa4131f1aa2.png)



Compatible Hardware


Arduino Nano
Arduino Uno
Arduino Micro
Arduino Mega
Arduino Mini
Arduino Leonardo
Arduino Nano Every
ESP8266
ESP32

Structure
Base set of libraries for any biped robot that uses 4 motors in the legs as Otto.

Otto.h and Otto.cpp contains all the main functions
Otto_gestures.h contains all the gestures functions
Otto_mouths.h contains all the mouth functions
Otto_sounds.h contains all the sound functions
Otto_matrix.h contains all the matrix functions
Oscillator.h is the main algorithm for the servos "smooth" movement
SerialCommand.c is for Bluetooth communication vis Software serial

Adding library
#include <Otto.h>
Otto Otto;

![Screenshot (1075)](https://user-images.githubusercontent.com/118633170/230276122-fb30faab-00c6-4cc1-9ad1-f1516740b0e5.png)


Pins declaration
These are the default signal connections for the servos and buzzer for AVR Arduino boards in the examples, you can alternatively connect them in different pins if you also change the pin number.

#define LeftLeg 2 // left leg pin
#define RightLeg 3 // right leg pin
#define LeftFoot 4 // left foot pin
#define RightFoot 5 // right foot pin
#define Buzzer 13 //buzzer pin

Initialization
When starting the program, the 'init' function must be called with the use of servo motor calibration as a parameter.

It is best to place the servo motors in their home position after initialization with 'home' function.

void setup() {
   Otto.init(LeftLeg, RightLeg, LeftFoot, RightFoot, true, Buzzer);
   Otto.home();
}
The home() function makes the servos move to the center position, Otto standing in the neutral position.

Add TipAsk QuestionCommentDownload
Step 8:


Predetermined Functions:
Many preconfigured movements are available in the library:


Movements:
These are actions that involve the use of the 4 servo motors with the oscillation library combined in synergy and with smooth movements. You can change the values inside the pratensis () to alter the speed, direction, and size of the movements.

![Screenshot (1074)](https://user-images.githubusercontent.com/118633170/230276138-83e4ad60-0373-4107-aced-c7bdaa701d86.png)

Walk function
Otto.walk(steps, time, dir);
steps are just how many times you want to repeat that movement without the need of further coding or adding additional rows.
time (noted as T below) translated in milliseconds is the duration of the movement. For a higher time value is slower the movement, try values between 500 to 3000.
dir is the direction: 1 for forward or -1 backward
Example:

Otto.walk(2, 1000, 1);
In this example 2 is the number of steps, 1000 is "TIME" in milliseconds and it will walk forward.

For example changing T value: Slow=2000 Normal=1000 Fast= 500

Otto.turn(steps, T, dir);
(# of steps, T, to the left or -1 to the right)

Otto.bend (steps, T, dir);
(# of steps, T, 1 bends to the left or -1 to the right)

Otto.shakeLeg (steps, T, dir);
(# of steps, T, 1 bends to the left or -1 to the right)

Otto.jump(steps, T);
(# of steps up, T) this one does not have a dir parameter Otto doesn't really jump ;P


Dances:
Similar to movements but more fun! you can adjust a new parameter h "height or size of the movements" to make the dance more interesting.

Otto.moonwalker(steps, T, h, dir);
(# of steps, T, h, 1 to the left or -1 to the right)

h: you can try change between 15 and 40

Example:

Otto.moonwalker(3, 1000, 25,1);
Otto.crusaito(steps, T, h, dir);
(# of steps, T, h, 1 to the left or -1 to the right)

h: you can try change between 20 to 50

Otto.flapping(steps, T, h, dir);
(# of steps, T, h, 1 to the front or -1 to the back)

h: you can try change between 10 to 30

Otto.swing(steps, T, h);
h: you can try change between 0 to 50

Otto.tiptoeSwing(steps, T, h);
h: you can try change between 0 to 50

Otto.jitter(steps, T, h);
h: you can try change between 5 to 25

Otto.updown(steps, T, h);  
h: you can try change between 0 to 90

Otto.ascendingTurn(steps, T, h);
h: you can try change between 5 to 15


Sounds:
Otto.sing(songName);
By just changing what is inside the () we can change the sounds easily to 19 different ones. Simple as copying and pasting in a new row to make the sounds as many times as you like.

S_connection
S_disconnection
S_buttonPushed
S_mode1
S_mode2
S_mode3
S_surprise
S_OhOoh
S_OhOoh2
S_cuddly
S_sleeping
S_happy
S_superHappy
S_happy_short
S_sad
S_confused
S_fart1
S_fart2
S_fart3
Otto can emit several sounds with the 'sing' function:

Otto._tone(10, 3, 1);
(noteFrequency, noteDuration, silentDuration)

Otto.bendTones (100, 200, 1.04, 10, 10);
(initFrequency, finalFrequency, prop, noteDuration, silentDuration)


Gestures:
Finally, our favorite, This is a combination of the 2 previous functions we learnt sing + walk Their goal is to express emotions by combining sounds with movements at the same time and if you have the LED matrix you can show them in the robot mouth!

Otto.playGesture(gesture);


Add TipAsk QuestionCommentDownload
Step 9:


Otto is very well designed for 3D printing, the files that you had downloaded are property oriented and centered, so wont give you trouble if you follow this common parameters:

Recommended to use a FDM 3D printer with PLA material.

No need supports or rafts at all.

Resolution: 0.15mm

Fill density: 20%

it should take around 12 hours to print a full set of parts for one Otto Humanoid.

For slicing and generating the g code for the machine FREE slicer software like Cura or any of your preference (If you are outsourcing the printing no need to worry about it).

After printing you will need to clean a little bit the legs and feet areas that fix the motors (generally) depends of the cleanness of your print.

For coding and use of the examples you will need Arduino IDE (version 1.8.5 preferably to avoid future errors)

Assembly Instructions

![Screenshot (1077)](https://user-images.githubusercontent.com/118633170/230276269-23154877-5227-4518-bea9-87a780ec3b24.png)
![Screenshot (1078)](https://user-images.githubusercontent.com/118633170/230276314-b7e7019d-de4d-42f7-acb2-4f8d118dd6df.png)![Uploading Screenshot (1076).png…]()

Gather all the off the shelf hardware parts that you'll need for this assembly. Then you only need to 3D print 10 parts in total:

3D printed head
3D printed body
3D printed leg (x2)
3D printed foot (x2)
Testing the electronics


As a good practice you should check your electronics and software in your computer, before assembling all robot to avoid having to disassemble the whole robot to fix something:

Download & install the Arduino IDE software (the vesion 1.8.5 has been the most stable)
Download all the libraries from the files tab and move to C:\Users\user\Documents\Arduino\libraries (or wherever your libraries folder was installed)
Connect your Arduino Nano through USB (your computer should install the drivers), and you should find your Otto connected in the Tools/Port menu in Arduino IDE (if your computer did not recognize the USB device you should install the driver CH340 for your Operative System)
Connect the Arduino to the Nano shield expansion board and only the servos to the output 2, 3, 4, & 5
Finally open & upload the "Otto_smooth_criminal.ino" sketch into your Arduino.
If all is good all your 4 servos should be moving and you are ready to build your own Otto!
Play with the examples!


Once the head is snapped in, prepare to upload other codes in the same way we tested the electronics.

Finally open & upload any of the Arduino sketches available under the software folder to your Arduino UNO.

