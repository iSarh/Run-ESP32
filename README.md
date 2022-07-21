This guide is derived from random ner dtutorial page, which can be found here: https://randomnerdtutorials.com/installing-the-esp32-board-in-arduino-ide-windows-instructions/

# Installing ESP32 Add-on in Arduino IDE

- Download arduino: https://www.arduino.cc/en/software
- in Arduino go to **File** then **Preferences**
- into the **Additional Board Manager URLs** enter : https://dl.espressif.com/dl/package_esp32_index.json

  then click **OK**

- Open the **Boards Manager** . Go to **Tools** > **Board** > **Boards Manager**...

- Search for **ESP32** and press install button for the **“ESP32 by Espressif Systems“**

## Testing

-  Select your Board in **Tools** > **Board** (in my case it’s the WEMOS D1 MINI ESP32)

- Select the **Port** in **Tools** (if you don’t see the COM Port in your Arduino IDE, 
you need to install the https://www.silabs.com/developers/usb-to-uart-bridge-vcp-drivers#:~:text=CP210x%20Universal%20Windows%20Driver)

- Open **File** > **Examples** > Select any example you want 
- A new sketch opens
- Press the Upload
-  If everything went as expected, you should see a “Done uploading.” message.





