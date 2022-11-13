# PicoMemcardforall
This is an evolving collection of PCBs and 3D printable shell based off of the PicoMemcard+ project. This project offers a handfull of easilly assembled PCBs for a variety of devboards, these PCBs fit inside a 3D printed shell that mimmicks the footprint of the stock PS1 memory card.

The Goal of this project to make aesthetically pleasing, easilly accesible, and inexpensive Picomemcard+ assemblies.
![image](https://user-images.githubusercontent.com/81984062/200209498-ddf6e46e-e810-403d-a393-29caeef8cbea.png)
![image](https://user-images.githubusercontent.com/81984062/200209594-98ad0a1e-9026-4861-91f3-234e100c7d52.png)
![image](https://user-images.githubusercontent.com/81984062/200210406-c683c869-dbcd-4abe-ad6a-d7481a336dc8.png)
![image](https://user-images.githubusercontent.com/81984062/200211891-e4b5a3f2-dcda-4cd1-9e76-04fa45092e55.png)
![image](https://user-images.githubusercontent.com/81984062/200211914-5af21ed9-bc82-4fc2-a769-f1a1bbc7ce1b.png)

The Zero and Xiao 2040 fit into the same shell, the PCBs themselves are near identical barring the footprint. Moving forward I plan to adapt a few more devboards to this project, boards I'm looking into include the Tiny 2040, 2040 Stamp, and the Adafruit QT Py RP2040. I'm also working on a dedicated PCB that uses the RP2040 IC directly on the board, Idealy this can be ordered near fully assembled and the SC0914 (RP2040 IC) is all that needs to be soldered on.

# Ordering PCBs
You can probably use some other websites, but www.JLCPCB.com is my fab of choice. Inside the .zip file that has the gerber files you will find two .csv files, one is a BOM (bill of materials) and the other is a Pick and Place (this tells the machine where to put the items).
Upload the .zip file with the PCB design files in it and you will be brought to this screen 
![image](https://user-images.githubusercontent.com/81984062/201547483-d4ea9924-8855-4e3d-a81f-ae41718efd52.png)
Select "4 layers", "1.0mm" for PCB thickness, and then select the top, inner one, inner two, and bottom layers as follows: PCB1.GTL, PCB1.G1, PCB1.G2, PCB1.GBL. All other options should be correct by default, but use the above image as reference to be sure.
enable SMT assembly and select "Assemble top side" 
![image](https://user-images.githubusercontent.com/81984062/201547594-9efa9dba-5eb1-4799-85e1-6400235e039b.png)
at the next screen select the PIP and BOM files.
![image](https://user-images.githubusercontent.com/81984062/201547969-63a5db7f-4776-42ac-b959-42ece5761ac7.png)
you will have to match many of the parts with ones from JLCPCBs parts libreary, BE CAREFUL HERE!!! Ensure it is set up exactly as I show here!
![image](https://user-images.githubusercontent.com/81984062/201548052-cb07d476-a480-4c5e-b2f6-d32fc4c94dcd.png)
the TVS diode array and the LDO orientation is incorrect by default
![image](https://user-images.githubusercontent.com/81984062/201548126-3b179157-da05-407b-9eb4-4c478251e697.png)
 make sure you flip them like so
![image](https://user-images.githubusercontent.com/81984062/201548163-286dbd60-a979-45e5-93a2-dcd5229dcf7d.png)
That's it! Save it to your cart and apply your coupons. You should be able to get each PCB for around $5 fully assembled, including shipping. All you need to do is solder your Zero or Xiao to your PCB. I suggest you take care in doing so, and make sure there are no bridges. I had to make the footprint pretty small for size constraints,so you need to ensure  alighnment, the PCB of the deboard should be flush with therear of the interposer PCB. Enjoy your new memory card! =)
