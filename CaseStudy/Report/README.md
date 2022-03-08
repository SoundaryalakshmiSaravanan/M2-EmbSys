 # TABLE OF CONTENTS

## 1. INTRODUCTION
1.1  ABSTRACT

1.2  PRINCIPLE OF THE SYSTEM

1.3   FEATURES OF THE SYSTEM

1.4 ADVANTAGES OF THE SYSTEM

1.5  SWOT ANALYSIS

1.6 4W & 1H

## 2 REQUIREMENTS

2.1 HIGH LEVEL REQUIREMENTS

2.2 LOW LEVEL REQUIREMENTS

## 3 ARCHITECTURE

3.1 SEQUENTIAL DIAGRAM

3.2 BLOCK DIAGRAM

3.3 COMPONENTS REQUIRED

3.4 APPLICATIONS

3.5 FUTURESCOPE

# AUTOMATIC DOOR OPENING SYSTEM


## 1. INTRODUCTION

 ### 1.1  ABSTRACT

The project concerns an automatic door opening and closing system. An automatic door control system includes a sensor for sensing a person or object approaching the door. Systems and methods are very common in the art for opening and closing doors to enter and exit buildings, facilities etc. Automatic doors are commonly found in retail stores, supermarkets, and the like.
 
## 1.2  PRINCIPLE OF THE SYSTEM
The project generally relates to an automatic opening and closing of doors which will sense a person or object approaching the door and open automatically. This system is controlled by an Arduino microcontroller. The system includes DC motor which makes door to slides during opening or closing by rack and pinion gearing, a LCD to display information state of door, an audio buzzer to make sound through the duration of opened door and a controller for controlling the opening and closing of the door as a person or object detected by sensor.
 
## 1.3   FEATURES OF THE SYSTEM

1. Automatic opening of the door 

2. Ability to detect the movement of people

3. Can be accessed everywhere

## 1.4 ADVANTAGES OF THE SYSTEM

1. Helpful for people in wheelchairs and disabled.

2. Contactless operation of the door which prevents the spread of germs.

3. Reduces manual power.
 
## 1.5  SWOT ANALYSIS
![swot drawio (1) drawio](https://user-images.githubusercontent.com/98818008/157258093-dae6e900-8d35-46c2-88d5-29538f383bf5.png)

## 1.6 4W & 1H
### WHAT 
Automatic Door Opening System helps in contactless operation of the door.
### WHERE 
Can be implemented where entry of people is controlled.
### WHEN 
It can be used whenever required.
### WHY 
In order to control the entry of people.
HOW - By implementing the system wherever required.
 
## 2 REQUIREMENTS
### 2.1 HIGH LEVEL REQUIREMENTS
HLR ID|DESCRIPTION|CATEGORY|STATUS
|-|-|-|-|
HLR1|System shall detect the movement of people|Technical|Upheld
HLR2|System shall open the door automatically|Technical|Upheld
HLR3|System shall have user interface| Technical|Upheld
HLR4|System shall indicate the user about the entry| Technical| Upheld

 
## 2.2 LOW LEVEL REQUIREMENTS
LLR ID|HLR ID|DESCRIPTION|CATEGORY|STATUS
|-|-|-|-|-|
LLR1|HLR1|System shall have a sensor to detect the people| Technical|Upheld
LLR2|HLR2|System shall have a motor to open the  door|Technical|Upheld
LLR3|HLR3|System shall have a LCD to communicate with user|Technical|Upheld
LLR4|HLR4|System shall have a buzzer to indicate the users|Technical|Upheld

 
## 3 ARCHITECTURE

### 3.1 BLOCK DIAGRAM
![FINGERPRINT (5)](https://user-images.githubusercontent.com/98818008/157259509-db436d38-185b-4e2b-be0b-cf976f467825.jpg)


### 3.3 COMPONENTS REQUIRED

ATmega328-PU

HRSC04 Ultrasonic sensor

 DC Motor
 
LCD 16 X 2

Piezo Buzzer

Power Supply

**1. ATmega328-PU**

The ATmega328 is a single-chip microcontroller created by Atmel in the megaAVR family It has a modified Harvard architecture 8-bit RISC processor core.

**2.HRSC04 Ultrasonic sensor**

 HRSC04 Ultrasonic sensor is used as a proximity sensor to detect a    person or object arrived at door
Ultrasonic ranging module HC - SR04 provides 2cm-400cm non-contact measurement function, the ranging accuracy can reach to 3mm. The modules include ultrasonic transmitters, receiver and control circuit.

**3.DC Motor**

The DC motor is the actuator used to open the door when the movement of people is detected.
Here DC motor of specification 
          Load current: 70mA (250mA MAX) (3V pm)
          Operating voltage: 3V ~ 12V DCTorque: 1.9 Kgf.cm
           Speed without load: 170 RMP (3V) is  used.


**4. LCD DISPLAY**

         
  LCD display is the Human Interface of this system. Here a 16 x 2 LCD display is used. Liquid crystal display is used for displaying the messages. 

**5. Piezo Buzzer**

 Piezo buzzer is a type of electronic device that's used to produce a tone, alarm or sound.
Here piezo buzzer is a human interface used to alert  the user.

**3.4 APPLICATIONS**

Immense helpful for disabled people

Can be implemented in hospitals to reduce the contamination since people do not need to handle doors manually.

Can be implemented in warehouse to make people easier for people to go around.

**3.5 FUTURESCOPE**

Upgrading the system using higher-bi microprocessor for speed operation

Face-detection through cameras can be implemented for automatic attendance systems.
 
 
 
 


