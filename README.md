To install the Wemos boards, you'll need to:
	1. Open up Arduino IDE
	2. Preferences
	3. Additional Boards Manager URLs
	4. Click the Windows next to the input element.
Copy and paste the line below onto a new line:
	http://arduino.esp8266.com/stable/package_esp8266com_index.json

Note on OSX:
	For OSX you will need to install a driver and disable csr.
	Download the drivers from the link below:
		http://blog.sengotta.net/wp-content/uploads/2015/11/CH34x_Install_V1.3.zip
	Reboot into recovery mode (hold Command+Shift+R).
	Open a terminal.
	Type in "csrutil disable" and hit enter.
	Reboot normally.