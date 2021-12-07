# Fluxion-on-esp8266
This is a Advance Fluxion tool on esp8266...

Welcome to the project. This project is inspired by https://github.com/M1z23R/ESP8266-EvilTwin

How to use:
Connect to the AP named M1z23R with password deauther from your phone/PC.
Select the target you want (list of available APs refreshes every 30secs - page reload is required)
Click the Start Evil-Twin button and reconnect to the newly created AP named same as your target (will be open)
After connecting, make sure you chooes "Use this network as is" (may differ on different devices)
Go to your favorite browser and navigate to 192.168.4.1/admin
Once there DO NOT change your target, only start/stop deauthing and wait for someone to try and use the correct password.
Once correct password is found, AP will be restarted with default ssid M1z23R / deauther and at the bottom of a table you should be able to see something like "Successfully got password for - SSID - Password

For compile this file visit https://github.com/SpacehuhnTech/esp8266_deauther/tree/v1

Note: feel free to provide bin file in pull request..
