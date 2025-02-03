# Arduino-Push-Button-Combination
Foundation year assessment:

To create an Arduino push-button combination lock with C++, write a software that takes input from numerous push buttons and matches the sequence of button pushes to a specified combination. The Arduino's digital pins are wired as inputs to detect button pushes, using pull-down or pull-up resistors to assure accurate readings. In the C++ code, the setup() method initialises the pins and any required variables, while the loop() function constantly checks the button states. When a button is pressed, the software captures the input and determines whether it matches the appropriate digit in the combo sequence. If the complete sequence matches, the Arduino generates an output, such as turning on an LED or triggering a servo motor, to signal a successful unlock. Error handling can be used to reset the sequence following unsuccessful attempts or a timeout interval. This project teaches digital input processing, state management, and fundamental logic in embedded systems programming with Arduino and C++.

![circuit](https://github.com/user-attachments/assets/662645cc-74e0-41e2-9789-ecd4c86f5763)
