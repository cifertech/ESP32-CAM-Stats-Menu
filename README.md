# ESP32-CAM-Stats-Menu
In projects where ESP boards act as APs or Soft APs, it is always a matter of how to identify the IP created by the board and view the specified username and password at the same time.

### Project working method

In this project, first the ESP32-CAM board will be converted to Soft APs mode. In this case, because we do not use the Internet to receive images, we call it the Soft Access Point. Also in this case it is not possible to send an Http request or upload libraries available on the Internet. Next, for Soft APs, we specify the username and password values, and it will also give us the desired IP, so that we can access the web server to receive the images. We will display all these values ​​on the OLED screen for easier process and better communication with the user. Of course, we have provided a microswitch to display the password, so that the password can be displayed just by pressing the switch, in order to increase security as much as possible.

