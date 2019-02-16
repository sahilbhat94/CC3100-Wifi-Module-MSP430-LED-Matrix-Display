# CC3100-Wifi-Module-MSP430-LED-Matrix-Display

The file contains the code to connect the microcontroller MSP430 to Wifi controller CC3100. The Wi-Fi controller with the help of the MSP430 microcontroller connects to a local home network and displays a unique IP address in the serial monitor of the software program used. The user can then type that IP address into a web browser which takes the user to a web server. Once the page has loaded the user can enter a message to be displayed on the LED matrix (connected using GPIO pins). The message scrolls along the five daisy-chained LED matrices and repeats five times. Before the first message is displayed a short one second beep from the buzzer ( connected using PWM signal) goes off to alert anyone nearby that a message is about to be displayed. To get a new message to display the user simply needs to enter a new message on the web server

Note: The code has been developed on sample code provided in the Energia Software. 
Also, The code didint work on the Universoty Wifi. But it works on the home Wi-Fi network.
