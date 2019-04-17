
![ER_LOGO](/docs/github.png)
>Electronic Realization L.L.C.								   
>Design: Battery charger 4 Li cells		   
>Engineer: Cy Drollinger								   
>Date: 5/18												           
>Email: cy@elec-real.com								   
>Address: 2023 Stadium Dr Suite 2B #210 Bozeman, MT 59715				   
>Phone: 406-539-8117	

**NOTE:**
 This design has been tested and functions as specified. The design is provdided gratis, but, please 
 think critically while utilizing and or redesigning for your success. Conversation is welcome, but be advised ER is a professional 
 design house and monetary compensation is required for work toward this design enabling your success.			   
	 
![Battery_charger](/hardware/eagleUp/BatChrgv1.png)

**PURPOSE:**
This is a hardware design that is capable of charging 4 li ion cells. The design employs four different circuits
and charge currents: 100mA, 200mA, 400mA, and 800mA. The design files were created with Eagle
Cadsoft v7.7 as a two layer board. Free Eagle version would be able to import these files. 

>**File Arcitecture with a terse description**


* FOLDERS:
	* docs		: datasheets charging IC and battery holder
	* hardware	: eagle cadsoft(v7.7) hardware design files 	
		* eagleup		: 3D files 
		* library		: eagle part files 
		* manufacturing	: files required to produce the design
			* bom	: files created to order the parts
					* batteryCharger.txt	: 
					* batteryv1.1.csv	: digikey order
					* hundredUnits.txt	
			* gerber	: files generated to manufacture the board
			* https://oshpark.com/shared_projects/4os8OxLZ
	* readme.md	: this file
	
