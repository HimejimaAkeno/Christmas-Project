# Christmas Project:
## All the steps come from these websites:
  * ### "LEDs with Buttons and GPIO Pins" [Link to the website](https://www.hackster.io/Tisko/rgb-led-a-button-click-away-9886c1)
  * ### "How to set up static IP address" [link to the website](https://www.raspberrypi.org/documentation/configuration/tcpip/)
## Material List:
  * ### Female to Male cables
  * ### Male cables
  * ### Two Raspberry Pi Zero
  * ### A laptop
  * ### 3D printer
  * ### Solderless Breakboard
  * ### 2x 470Ω Resistors
  * ### 1x cathode LED
  * ### 2x tactile buttons
  * ### 1x portable charger/battery pack
 
 ## Coding Part:
 ### Connect one Raspberrypi Zero into your computer
 ![image of putty](https://timacw.weebly.com/uploads/1/3/2/1/132123452/raspberrypi05_orig.jpg)
 ### Log into your raspberrypi with your username and password.
 ![image of putty](https://timacw.weebly.com/uploads/1/3/2/1/132123452/putty_orig.png)
 ### First, type in the following line to download a module called "RPi.GPIO"
 ![image of downloading](https://timacw.weebly.com/uploads/1/3/2/1/132123452/gpio-module_orig.png)
 ### Enter the following line and create a python file called "chris.py"
 ![image of coding](https://timacw.weebly.com/uploads/1/3/2/1/132123452/nano-chris2_orig.png)
 ### Type in the following code into "chris.py". Use "Ctrl+O" to save it and "Ctrl+X" to exit it and the coding part is finished!
 ![image of coding](https://timacw.weebly.com/uploads/1/3/2/1/132123452/coding-part_orig.png)
  ### Congratulation! You successfully finish the coding part. 
 
 ## Building Part:
 ### Install the Cathode LED and the tactile button according to this graph:
 ![image of LED](https://timacw.weebly.com/uploads/1/3/2/1/132123452/rgb-button_orig.jpg)
 ### Congratulation! You successfully finish the building part. 

 ## Set Up SSH:
 ### Type in the following line
 ![image of IP](https://timacw.weebly.com/uploads/1/3/2/1/132123452/ip-address-conf_orig.png)
 ### Then delete all the "#" before Line 44-47 and your result should look like this. After that, hit "Ctrl+O" and "Enter" to save it and "Ctrl+x" to exit.
 ![image of IP](https://timacw.weebly.com/uploads/1/3/2/1/132123452/4lines_orig.png)
 ### After that, check your Static IP Address by enter "hostname -I" Make sure to use the last digits
 ![image of IP](https://timacw.weebly.com/uploads/1/3/2/1/132123452/hostname_orig.png)
 ### Then, plug this Raspberrypi Zero into a portable charger and then set it aside. Grab a new Raspberrypi Zero and log in with Putty as usual.
 ![image of IP](https://timacw.weebly.com/uploads/1/3/2/1/132123452/charger_orig.jpg)
 ### Enter "ssh pi@xyz", which "xyz" is your Static IP Address, then enter the password. (In my case, I enter shh pi@10.40.11.243)
 ![image of IP](https://timacw.weebly.com/uploads/1/3/2/1/132123452/ssh_orig.png)
 ### Congratulation! You successfully log in to the Raspberrypi Zero with the code on it!

 ## 3D-Design Part:
 ### Use a website called "tinkercad to design your box"
 ![image of box]()
 ### After you have accomplished all the steps above, assemble your "toy" into the box your just made
 ### Congratulation! You successfully made a Christamas toy! Have fun!
 ###
