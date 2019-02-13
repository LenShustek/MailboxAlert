The "MAILBOX Alert" device from MySpool is a great gadget for notifying 
you when mail has been delivered to your mailbox. 
https://myspool.com/?q=content/what-is-mailbox-alert 

But there were a couple of things I wanted that it didn't do: 
 - provide a resettable light in the house that shows when there is mail
 - work outside the house's WiFi range 

So in the Maker/Hacker spirit, I took it apart and used the components 
differently to achieve those goals. What I did was:

- figure out the schematic of the MAILBOX Alert device, and identify the 
only critical component: the Wifi/processor module, which is a WEMOS D1 
Mini based on the ESP8266 CPU with custom programming.

- use a 315 Mhz RF wireless remote control in the mailbox instead, 
connected to MySpool's magnetic proximity switch and enclosed in a 
waterproof box mounted on the exterior of the mailbox. 
https://smile.amazon.com/gp/product/B00W8V4KQ4 
https://smile.amazon.com/gp/product/B06ZYN12WN 

- wire the Wifi/processor module into a new circuit mounted inside a 
standard wall-mounted receptacle box in the house. The faceplate of the 
box has a single lighted pushbutton. When mail is delivered to the box, 
the light comes on, and the usual text message and emails are sent 
using the house WiFi. Pushing the lighted button turns off the light. 

Schematics and photos are in this repository. This is a hardware-only 
project. No coding is required, because it was all done by MySpool! 
