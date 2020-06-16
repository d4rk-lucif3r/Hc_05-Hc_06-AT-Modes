# Hc_05-Hc_06-AT-Modes
-AT Commands stands for **Attention command**

-AT commands mode is used to change default settings of Bluetooth module.

-When if there some need like to change the BT device name, device role like master or slave, Password of device BT module need to set in AT Command mode and default setting can change.

## Steps To be Followed
- Connections
	- VCC/5v to 5v of Arduino
	- Gnd to Gnd of Arduino
	- RX pin to Digital Pin 10
	- TX pin to Digital Pin 11
	- Key pin to Digital Pin 9
- Flash Code into Arduino.
- Keep the button Present on Bluetooth Module pressed Before turning on power
- Open Serial Monitor in Arduino IDE and type AT then click Enter. If you get Output OK. Voila!!! you Successfully Entered AT Mode.
-  Enter Commands of your choice.

## Some AT Commands
- AT : Checks the connection.  
- AT+NAME : Displays default name  
- AT+ADDR : Displays default address  
- AT+VERSION : Displays version  
- AT+UART : Displays Default baudrate  
- AT+ROLE: Displays role of bt module(1=master/0=slave) 
- AT+RESET : Reset and exit AT mode
- AT+ORGL : Restore factory settings  
- AT+PSWD: Displays default password
- More commands Given in [**HERE**](https://github.com/arshanwar/Hc_05-Hc_06-AT-Modes/blob/master/At_Mode_Overview.pdf)
