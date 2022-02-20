## FINGERPRINT BASED BIOMETRIC ATTENDANCE SYSTEM

### 1 INTRODUCTION
#### 1.1 OBJECTIVE
             Biometric Attendance systems are commonly used systems to mark the presence in school, college, business organization, offices where marking of attendance is required accurately with time. Fingerprint based biometric Attendance system is proposed. By using the fingerprint sensor, the system will become more secure for the users. The Biometric Attendance system is designed using an AVR microcontroller.

#### 1.2 FINGERPRINT BASED BIOMETRIC ATTENDANCE SYSTEM PRINCIPLE
           Fingerprint identification is based on the fact that no two persons will have the same fingerprint in this world. Finger print module differentiates between two fingers based on the ridges and valleys on finger print. Main heart of the circuit is the fingerprint module. This sends commands to the controller whenever the fingerprint is matched. Microcontroller receives these commands from the finger print module and uses the internal EEPROM to store the attendance. Keypad is used to send the requests to the controller either to enroll the new one or to save the attendance or to exit. LCD displays display the messages related to the commands received.

#### 1.3 FEATURES OF THE SYSTEM
1.Integrated image collecting and algorithm chip together, ALL-in-One
2.Fingerprint can conduct secondary development & embedded into a variety of end products
3.Low power consumption, low cost, small size, excellent performance

#### 1.5 4 W & 1 H ANALYSIS

**WHAT** - Biometric Attendance system is used to mark the attendance along with       time and date automatically by using the fingerprint which is placed on the sensor.

**WHERE** - Wide application in school, college, business organization, offices where marking of attendance is required accurately with time. 

**WHEN** -  Can be used whenever required in order to mark attendance.

**WHY** - Biometric Attendance system is capable of marking and maintaining  attendance without any manual needs and hence the attendance marked is accurate and precise.

**HOW** - By building the perfect system, testing and executing it.

### 2 REQUIREMENTS

#### 2.1 HIGH LEVEL REQUIREMENTS


ID
DESCRIPTION
CATEGORY
STATUS
HR01
User should be able to register his/her fingerprint
Technical
Upheld
HR02
System should be able to match input fingerprint
Technical
Upheld
HR03
System should be able to save attendance with accurate date and time  
Technical
Upheld
HR04
System should have human interface
Technical
Upheld
HR05
System stored and maintain attendance
Technical
Upheld




#### 2.2 LOW LEVEL REQUIREMENTS

      
ID
DESCRIPTION
HLR ID
STATUS
LR01
System should have fingerprint sensor module to sense the fingerprint
HR01
Upheld
LR02
System should have external memory to match fingerprint
HR02
Upheld
LR03
System must have RTC module to set date and time
HR03
Upheld
LR04
System must have LCD and keypad for human interface
HR04
Upheld
LR05
System should have external memory to store fingerprint
HR05
Upheld

### 3    SYSTEM DESIGN

#### 3.1 BLOCK DIAGRAM


 #### 3.2 COMPONENTS REQUIRED
      The whole system is divided into following parts: 
Fingerprint Sensor module
ATmega 32
Power supply unit
Keypad Interface
Real Time Clock
LCD Display
External Memory 
##### FINGERPRINT SENSOR MODULE
         The Fingerprint module is the Sensor module. Fingerprint Sensor module is used to authenticate a person or employee’s identity by taking their finger-print input in the system. Here fingerprint sensor R305 is used. FingerPrint Sensor (R305) -TTL UART is a fingerprint sensor module with TTL UART interface. The user can store the fingerprint data in the module and can configure it in 1:1 or 1: N mode for identifying the person. The finger print module can directly interface with a 3v3 or 5v Microcontroller.

##### ATMEGA 32 MICROCONTROLLER
        ATmega32 microController is a low power CMOS technology based controller. Due to RISC architecture AVR microcontrollers can execute 1 million instructions per second if the cycle frequency is 1 MHz provided by a crystal oscillator. It has 1024 bytes EEPROM, with 32 programmable I/O lines. It has 8 KB of flash memory, 512 bytes of EEPROM, 1KB of SRAM.

#### KEYPAD INTERFACE
       The Keypad interface is the Human Interface of this system. Here the keypad used has 4 push buttons to enroll, Delete, Increment and Decrement finger-print data. Their functions are mentioned below
Key 1 is used for enrollment of fingerprint  a new person into the system. 
key 2 has double function, like when user enrolls new finger and key 2 is also used for reset or delete data 
Key 3 & 4 is used to select finger-print ID 

REAL TIME CLOCK (RTC)
        Real-time clocks (RTC) are timers dedicated to maintaining a one-second timebase. In addition, an RTC is often used to keep track of clock time and calendar date either in software or hardware. Here RTC is used to track attendance with accurate time and date. 



LCD DISPLAY
           LCD display is the Human Interface of this system. Here a 16 x 2 LCD display is used. Liquid crystal display is used for displaying the messages. 

EXTERNAL MEMORY
        External memory used is EEPROM. EEPROM (electrically erasable programmable read-only memory) is user-modifiable read-only memory (ROM) that allows users to erase and reprogram stored data repeatedly in an application. Here it is implemented to writing attendance data to EEPROM and reading attendance data from EEPROM.

### PIN DIAGRAM OF ATMEGA 32

PIN CONFIGURATION FOR THE SYSTEM
 Push or Membrane Buttons 
              Pin PA2 (ENROL key 1)
              Pin PA3(DEL key 2)
              Pin PA0(UP key 3)
              Pin PA1(DOWN key 4) of microcontroller with respect to the ground or PA4. 

Fingerprint module’s Rx and Tx directly connected at Serial pin PD1 and PD3 of microcontroller.

16x2 LCD is configured in 4-bit mode and its RS, RW, EN, D4, D5, D6, and D7 are directly connected at pin PB0, PB1, PB2, PB4, PB5, PB6, PB7 of microcontroller

  RTC module is connected at I2Cpin PC0 SCL and PC1 SDA.
  PD7 is used as soft UART Tx pin for getting the current time.

APPLICATIONS OF THE SYSTEM
This can be used in educational institutions.
Biometric attendance systems can be used in industries.
Biometrics can be used in ATMs for authentication.
Fingerprint authentication can be used in access control.
 
#### CONCLUSION
        Thus the  Fingerprint Based Attendance System finds its application in all the sectors where the  timely attendance maintenance is necessary. By implementing this system attendance can be maintained without any manual interruptions. Hence the system and the records created by the system become more reliable.  








