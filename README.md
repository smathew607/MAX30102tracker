# MAX30102tracker
Arduino IDE and MAX30102 used to make a heart rate tracker

The Workout Intensity Tracker project uses an Arduino Uno, a heart rate monitoring system. This system averages your heart rate over 10 seconds and then compares it to a second set of beats collected. With these two averages, a percentage difference is calculated to show the effort expended through your total workout. Completing this project teaches users how to integrate software and hardware skills to develop a proper embedded system.

Hardware Requirements
  1. Arduino UNO
  2. MAX 30102
  3. Soldering Iron Kit
  4. Breadboard and Jumper Wires

Software Requirements
  1. Arduino IDE
  2. Sparkfun MAX30102 library
  
Setup and Configuration
1. Circuit Connection: Ensure that the Arduino Uno is fully connected to the MAX30102 through the 4 jumper cables.
2. Library Installation: Install the Sparkfun MAX30102 library in your Arduino IDE.
3. Operation: Plug the Arduino into the computer and upload the necessary code powering the microcontroller.

Usage:
Hold your finger on the MAX 30102 sensor for 10 seconds then let the average BPM be outputted.
Next, come back for a second session of 10 seconds and let your second average be calculated and a percentage difference.


Schematic

![image](https://github.com/smathew607/MAX30102tracker/assets/124748723/a1ae548b-56e1-4e66-863b-30032bb17375)

Code

![image](https://github.com/smathew607/MAX30102tracker/assets/124748723/e9902659-19d5-4e3b-984a-a6fbc82b6ea9)

![image](https://github.com/smathew607/MAX30102tracker/assets/124748723/cd03e221-2716-4b3e-b188-8231fed77cfa)

![image](https://github.com/smathew607/MAX30102tracker/assets/124748723/75b203b9-d196-4d96-be7d-91712b71502d)

![image](https://github.com/smathew607/MAX30102tracker/assets/124748723/89cc6eb3-9787-4fc8-a5b4-609fd119441a)
