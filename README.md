# RFID Door Locking System

This project involves creating a door locking system using an Arduino UNO board, RFID module, LCD with I2C module, servo motor, and jumper wires.

## Functionality

1. **Power On:**
   - Upon powering on, the servo motor activates, pushing the door lock forward.
   - The LCD displays "Welcome, put your card."

2. **RFID Tag Scanning:**
   - When an RFID tag is moved closer to the RFID reader, it is scanned.
   - The LCD displays "Scanning."

3. **Validation:**
   - If the RFID tag is correct:
     - The servo motor is activated to pull back the door lock.
     - The LCD displays "Door is Open."

4. **Locking:**
   - When the RFID tag is moved closer again and is correct:
     - The servo motor pushes the door lock forward.
     - The LCD displays "Door is locked."

5. **Incorrect RFID Tag:**
   - If an incorrect RFID tag is used, the LCD displays "Wrong card."

## Components Used

1. Arduino UNO board
2. RFID module
3. LCD with I2C module
4. Servo motor
5. Jumper wires

