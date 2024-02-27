# Smart Electronic Voting Machine (SEVM) using Arduino Uno

## Objective:
The SEVM project aims to revolutionize traditional paper-based voting systems by introducing a Smart Electronic Voting Machine (SEVM) powered by Arduino Uno and integrating RM07 biometric sensor to maintain integrity by eliminating proxy votes.

## Components/Software Required:
1. Arduino Uno Board
2. 16x2 LCD Display
3. I2C Module
4. Push Button Switches
5. Connecting Wires
6. Breadboard
7. Fingerprint Sensor (R307)

##Project Description (SOFTWARE):

##Libraries Used:

1. Wire.h: This library is used for I2C communication.
2. LiquidCrystal_I2C.h: This library allows easy interfacing with I2C LCD displays.
3. Adafruit_Fingerprint.h: This library facilitates communication with the Adafruit fingerprint sensor.
4. SoftwareSerial.h: This library enables software serial communication for the fingerprint sensor since the Arduino Uno has only one hardware serial port.

##Functions used:
1. enrollFingerprint(): Initiates the fingerprint enrollment process for voters.
2. getFingerprintEnroll(): Manages the step-by-step enrollment process for fingerprint data storage.
3. checkFingerprint(): Verifies if a fingerprint matches any enrolled fingerprint, ensuring each voter can cast only one vote.

4. readnumber(): Reads numerical input from the Serial monitor, primarily used for setting up fingerprint IDs during enrollment.

## Project Description (HARDWARE):
### Phase 1: Initialization and System Setup
- Microcontroller Operation:
- LCD Operation:
- Fingerprint Sensor Operation:
- Integration:

### Phase 2: Voting Process
- Microcontroller Operation:
- LCD Operation:
- Fingerprint Sensor Operation:
- Integration:

### Phase 3: Result Calculation and Display
- Microcontroller Operation:
- LCD Operation:
- Fingerprint Sensor Operation:
- Integration:

### Additional Features
- Fingerprint Enrollment
- Error Handling
- Overall Integration

## Implementation:
### Initialization Process
1. Setting up the Hardware
2. Writing the Initialization Code
3. Enrolling Fingerprints
4. Storing the Fingerprint Data

### Verification Process
1. Access Control for Voting
2. Fingerprint Verification
3. Legitimacy Check
4. Casting the Vote
- Security Considerations
- User Interface

## Challenges Faced:
The implementation encountered challenges in configuring the fingerprint sensor and integrating voting mechanisms with Arduino. Problem-solving involved extensive research, troubleshooting, and refining the integration process.

## Applications:
The SEVM technology has applications beyond voting systems, including secure access control, attendance tracking, secure transactions, biometric identification, healthcare, visitor management, library management, IoT security, e-government services, and border control.


