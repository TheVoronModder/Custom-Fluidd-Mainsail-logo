# Custom-Fluidd-Mainsail-logo
How to create your own custom logo for Fluidd and Mainsail

At the top right of this page you will see a GREEN box (code) click it and select download.


**Things you are going to need / download**

**Inkscape**
https://inkscape.org/release/inkscape-1.3/windows/64-bit/msi/dl/

**WinSCP**
https://winscp.net/eng/download.php

**Windows Visual Code Stuido**
https://code.visualstudio.com/download

or

**Notepad++**
https://notepad-plus-plus.org/downloads/v8.5.5/

**Paint.net**
https://www.getpaint.net/download.html 

NOTE! You need a .png of your logo you want to use with an empty background.
You can use paint.net to accomplish this easily or inkscape, since I am new to inkscape we will be using paint.net
Logo making instructions.

1.	Open paint.net and make your logo
   
3.	Alternatively, if you have cad software and are able to save a 2d model as a .png or .jpeg do that, then proceed to paint.net, if you do not have that ability use paint.net or any file you like on the internet that is a .png
   
5.	Open inkscape
	a.	Open the file provided to you with inkscape, should be able to double click it.

8.	Drag and drop your .png and scale until it fits.
	
10.	Save file as logo_yourfilenamehere.svg
	a.	It must be saved as a “Plain svg” or it will NOT work.

File Upload Instructions

1.	SSH into your pi using WinSCP
	
2.	Navigate to /home/pi/fluid
	a.	Or /home/pi/mainsail
  
3.	Download config.json
  
4.	Using Visual Code Studio
	a.	Open the config.json
5.	You need to add this to the portion like this below:

![vcs json logo](https://github.com/TheVoronModder/Custom-Fluidd-Mainsail-logo/assets/142328467/1e9c9a22-27de-4052-a99b-2b2136002308)




6.	Save the file

7.	Drag and drop the config.json file back into WinSCP and click “YES” you want to overwrite it.

8.	Upload your file and your done.
	
 Fluidd / Mainsail interface

 You need to refresh your Fluidd or Mainsail page with an F5 from the keyboard.

 Navigate to your themes under settings and you should see it in the drop down menu. Viola! Your done!
