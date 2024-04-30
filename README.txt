<INSTRUCTIONS TO REPLICATE>

> format sd card to FAT for it to be usable by micro controllers.
> copy the files in the webData folder into the root of the sd card, that is to say do not put them in a folder other than the foldres already given
  copy straight out of the webData folder into the empty sd card.
> put images into the images folder, these are used by the website pages and rename reffering to the names in the html code.
> put your music (mp3 files) into the music folder in the sd card.
> put your videos (mp4 files) into the video folder in the sd card.
> load the ino file from the code folder code into your arduino ide.
> from the include lines on the top of the ino file in the arduino ide, you can see which libraries where used.
> use the library manager in the ide to download the required libraries.
> connect your esp32 board to the pc and upload the code.
> make sure your circuits are correct and assemble the circuit.
> press the reset button on the esp32.
>>it should start the led sequence but at the end green should be blinking, if red led is blinking then sd is not mounted(revist your circuit and try again).
>>connect to the Free Innernet Wifi and allow to connect even without internet.
>>in your browser, enter freenet.local or enter the IP 192.168.4.1(or the one that your arduino serial monitor gives you, look for it in the messages given out by the esp32 on the serial connection).
>>you are in the innernet👍️
