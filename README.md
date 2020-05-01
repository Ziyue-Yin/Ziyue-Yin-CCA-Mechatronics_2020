# Ziyue-Yin_CCA_Mechatronics_2020

## Week 14: Final Project Presentation - Security Protection Device

![image](https://github.com/Ziyue-Yin/Ziyue-Yin-CCA-Mechatronics_2020/blob/master/final%20project/final%20week%20image/IMG_0269.jpeg) 

### Concept:
- This is a security device to drive strangers out of the door after midnight. It installs near the doorway. My roommates and I are living in a house in Ocean Ave. There is a potential safety hazard when we fall asleep, especially during the coronavirus time. This device can help us to scare the strangers coming at midnight. 

### Components :
- Basic Parts: Bread board / Wire / Arduino Uno board
- LDR - turn on the device when the surrounding is dark. 
- Ultrasonic Sensor - recognize if the strangers come close the house
- LED Lights - Red and Green, when someone comes close to the house, the red will turn on and the green will turn off. 
- Serial MP3 Player
- Speaker : yell at the strangers:"Get away from my house!"

![image](https://github.com/Ziyue-Yin/Ziyue-Yin-CCA-Mechatronics_2020/blob/master/final%20project/final%20week%20image/IMG_0256.jpeg) 
![image](https://github.com/Ziyue-Yin/Ziyue-Yin-CCA-Mechatronics_2020/blob/master/final%20project/final%20week%20image/IMG_0258.jpeg) 

### How it works and Prototype:

#### How it works:
This device turns on only at midnight which will be detected by the LDR. If there is someone close to the door at midnight, the distance sensor will discover. Then the speaker will yell at the stranger: “Get away from my house!”. Meanwhile, the red light will turn on and the green one will turn off. 

![image](https://github.com/Ziyue-Yin/Ziyue-Yin-CCA-Mechatronics_2020/blob/master/final%20project/final%20week%20image/IMG_0275.GIF) 

#### Prototype:
- At night, no one come close to the door:
![image](https://github.com/Ziyue-Yin/Ziyue-Yin-CCA-Mechatronics_2020/blob/master/final%20project/final%20week%20image/IMG_0269.jpeg) 

- Imitate someone comes close to the door:
![image](https://github.com/Ziyue-Yin/Ziyue-Yin-CCA-Mechatronics_2020/blob/master/final%20project/final%20week%20image/IMG_0270.jpeg) 

### Presentation link:
- https://youtu.be/iVoFrzQOh0c



## Week 12: Final Project Part 1

### Project revise: 
- Use the LDR  to achieve the function of switch: The device turn on during the night, turn off at the daytime.
- The MP3 speaker cable is to play the voice of "Get away from my house!"
- Distance sensor to perceive if the stangers come close to the outdoor.
- LED light will turn on fade with the speaker's voice at the same time.

#### Resources of the sensors:
- Ultrasonic sensor with speaker: https://youtu.be/gLDoFxYp-Ek
- LED Fade : https://youtu.be/emPE8WUIFRg
- LDR : https://www.youtube.com/watch?v=qKku-mmwNIA

#### Process part 1:
- Steps to do:
- - Install the LDR 
- - Ultrasonic sensor and Speaker
- - LED Sensor

##### Attempt of part 1:
1\ During this week, I attempt to install the ultrasonic sensor, LDR and the LEDs together. 
At first step, I coded the Ultrasonic sensor and LED together, then coded the LDR seperately. 
I would like to use the red LED and the Green LED first. When the distance is less than 5 cm, the red light will turn on and meanwhile the Speaker will work. When the distance is more than 5 cm, the Green LED will turn on and the red one will turn off. 
![image](https://github.com/Ziyue-Yin/Ziyue-Yin-CCA-Mechatronics_2020/blob/master/final%20project/IMG_0181.jpeg)  
Problems:
When I finish the code, the distance sensor can work, but the LEDs cannot work at the same time. 
![image](https://github.com/Ziyue-Yin/Ziyue-Yin-CCA-Mechatronics_2020/blob/master/final%20project/IMG_0182.jpeg)  

##### NEXT Step for the work: 
Next week, I am going to fix the LEDs' problem first, and then code the LDR, leds, Ultrasonic Sensor and Speaker togther. 


## Week 11: Final Project Proposal

### Concept: Get away from my house!

- This is a security device to drive strangers out of the door after midnight. It installs near the doorway. Now my roommates and I are living in a house in Ocean Ave. There is a potential safety hazard when we fall asleep, especially during the coronavirus time. This device can help us to scare the strangers coming at midnight. 

- How it works: This device turns on only at midnight. Use the remote control to turn on the device. If there is someone close to the door at midnight, the distance sensor will detect him. Then the speaker will yell at the stranger: “Get away from my house!”. Meanwhile, the led light will turn on. 

- Drawing of concept
![image](https://github.com/Ziyue-Yin/Ziyue-Yin-CCA-Digital-Electronic_2020/blob/master/week%2011/%E6%88%AA%E5%B1%8F2020-04-0921.20.44.png)  

##### Must have
- Basic Parts: Bread board / Wire / Arduino Uno board
- Remote Controller
- Ultrasonic Distance Sensor
- LED Light
- Speaker : https://www.adafruit.com/product/1314 / https://www.adafruit.com/product/1313 / https://www.adafruit.com/product/1313  (Select one of them)

##### Nice to have
- LED RGB Light (Coding the fade on)
- Remote Control the device on and off.

#### Steps to use the device :
- Use the remote controller to turn on the device at the midnight.
- When the strange person comes close, the led light will fade. 
- Meanwhile, the speaker will yell at the stranger: " Get away from my house!"
- Turn off the device when you get up.

- Optional : This device can also use during the time that the residents are not at home.

- Storyboard about how to use the device: 

![image](https://github.com/Ziyue-Yin/Ziyue-Yin-CCA-Digital-Electronic_2020/blob/master/week%2011/digital%20electric_20200409231120-01.png)  

#### Steps to make the device :
- Set up the remote controller to turn the device on at the midnight and turn off during the daytime.
- Write the coding of remote controller, ultrasonic distance sensor, LED and Speaker.
- Find a way to record the voice which can play on the speaker. 
- Install them on the outdoor. 


## week7

- In this week, Sissi, Tianbai and I work as a group to create the vehicle project. In our project, we make a vehicle which can avoid the obstacles and change the direction. 

 ![image](https://github.com/Ziyue-Yin/Ziyue-Yin-CCA-Mechatronics_2020/blob/master/week%207/mid%20term%20vehicle.GIF)  
 
 - Then we use the led as an output to develop our device. 
  ![image](https://github.com/Ziyue-Yin/Ziyue-Yin-CCA-Mechatronics_2020/blob/master/week%207%20/midterm%20pic/251584067709_.pic_hd.jpg)  
  
## week6

In week6, I make some sketches to describe how can I create a vehicle. At the beginning, I attempted to create a vehicle only with two motors. Later I found that it is difficult to make the vehicle change the direction. Then I decided to create a vehicle with 4 motors to motivate the wheels. 

 ![image](https://github.com/Ziyue-Yin/Ziyue-Yin-CCA-Mechatronics_2020/blob/master/week%206%20sketch/IMG_6989.JPG)  

In this sketch, I am going to laser cut the wheels to assemble the vehicle. I measure the size of the wheels and the board on the top of the vehicle. (Sorry to write in Chinese, it is to understand easier for me.)

 ![image](https://github.com/Ziyue-Yin/Ziyue-Yin-CCA-Mechatronics_2020/blob/master/week%206%20sketch/IMG_6988.JPG)  
 

## week5

In week 5, I attempt the digital screen display. This is one part of my midterm work. I plan to create a device that can detect the distance. The number of distance can display on the digital screen. Previously, I got fair on the screen, which showed only the several squares on it. Then professor and I try to figure it out. There is a mistake with the wire connection. Then we tried to reconnect it. It works as I expect.

- Mistake on digital screen:

 ![image](https://github.com/Ziyue-Yin/Ziyue-Yin-CCA-Mechatronics_2020/blob/master/week%205%20distance%20device/digital%20screen%20display.jpg)  
  
- Image of successful digital screen
  
  ![image](https://github.com/Ziyue-Yin/Ziyue-Yin-CCA-Mechatronics_2020/blob/master/week%205%20distance%20device/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202020-02-28%2012.36.45.png)

- Image of distance device
  
  ![image](https://github.com/Ziyue-Yin/Ziyue-Yin-CCA-Mechatronics_2020/blob/master/week%205%20distance%20device/IMG_6733.jpeg)  

link of video: https://youtu.be/qfcxuwiw81Q

## week4_2 led gif
- This week I create the circuit with 2 leds. These two leds can flash alternately.

 ![image](https://github.com/Ziyue-Yin/Ziyue-Yin-CCA-Mechatronics_2020/blob/master/IMG_6731.gif)  

## week 2_ link to drawing machine
- Here is my simply drawing machine recording video. It supposes to be drawing automatically motivated via a motor. However, there are some problems when I try to turn on the machine. First, the motor cannot drive the machine to spin automatically. Next, it might be a friction that affects the movement. I will continue to fix those problems as soon as possible. 
- link for video : https://youtu.be/MC7H1y6SRm8

- Image of my work
 ![image](https://github.com/Ziyue-Yin/Ziyue-Yin-CCA-Mechatronics_2020/blob/master/drawing%20machine/1131582913642_.pic_hd.jpg)

## week 1_ link to the Crank Driven Handle Contraption_ The Flying Fish
- This is my crank driven handle contraption. This is a flying fish installation.
- link for video : https://youtu.be/TxcafzaZeiY   https://youtu.be/llZvZ8AhMro


