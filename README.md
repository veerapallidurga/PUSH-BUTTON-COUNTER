# PUSH-BUTTON-COUNTER
**COMPANY NAME**: CODTECH IT SOLUTIONS
**NAME**: V DURGA PRASAD
**INTERN ID**: CT08IMG
**DOMAIN**: EMBEDDED SYSYTEMS
**BATCH DURATION**: January 10th, 2025 to February 10th, 2025.
**MENTOR NAME**: NEELA SANTHOSH

# ENTER DESCRIPTION OF TASK PERFORMED NOT LESS THAN 500 WORDS
The Push Button Counter System is an embedded system designed to track and display the number of times a button is pressed, providing a simple yet effective method for counting events in real-time. This project uses a microcontroller (such as Arduino Uno) to handle the button presses, ensuring that the counter only increments once for each valid button press. The system integrates key concepts of embedded systems, including digital input processing, debouncing techniques, and LCD or serial display for output. The primary goal is to create a user-friendly, cost-effective system that can be applied to a variety of fields requiring event counting, such as attendance tracking, click counters, or manual counting tasks in industrial or consumer environments.

The system relies on a simple yet efficient hardware setup, consisting of a push button, a microcontroller (Arduino Uno), a 16x2 LCD display (for visual feedback), and basic passive components such as resistors. The push button, which is connected to one of the digital input pins on the microcontroller, detects changes in state (pressed or not pressed). A pull-down resistor is used to ensure a stable input signal, preventing fluctuations when the button is not pressed. The LCD display provides a clear output of the current count, making the system easy to monitor in real-time.

A critical aspect of this design is the debouncing mechanism. Mechanical push buttons are prone to “bouncing,” where rapid on-off signals are generated when the button is pressed or released. These multiple transitions can result in erroneous counting, leading to false increments in the counter. To prevent this, a debouncing algorithm is implemented in the software. The microcontroller checks the button state at regular intervals, and if the state remains stable for a predefined period (debounce delay), the button press is considered valid. This ensures that only one increment occurs per press, even if the button physically bounces.
# OUTPUT OF THE TASK 1
https://github.com/veerapallidurga/PUSH-BUTTON-COUNTER/issues/1#issue-2782292210
