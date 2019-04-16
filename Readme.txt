********************************************************************************************
* Electronic Realization L.L.C.								   *
* Design: Battery charger 4 Li coin cells 24.5mm, maximum 800 mA charge current		   *
* Engineer: Cy Drollinger								   *
* Date: 5/18									           *
* Email: cy@elec-real.com								   *
* Address: 2023 Stadium Dr Suite 2B #210 Bozeman, MT 59715				   *
* Phone: 406-539-8117									   *
********************************************************************************************

![alt tag](https://github.com/cydrollinger/battery-charger/blob/master/hardware/eagleUp/BatChrgv1.png)
![Image of Yaktocat](https://octodex.github.com/images/yaktocat.png)
<img src="https://assets-cdn.github.com/images/modules/logos_page/GitHub-Mark.png" width="256" height="256" title="Github Logo">

*******NOTE*********************************************************************************
* This design is not perfect but is provdided gratis. Please think critically while using  *
* or redesigning for your success. Conversation is welcome, but be advised monetary compen-*
* sation is required for work toward this design for your success.			   *
********************************************************************************************	 
*******************************************
*File Arcitecture with a terse description*
*******************************************

FOLDERS:
	docs		: datasheets charging IC and battery holder
	hardware	: eagle cadsoft(v7.7) hardware design files 	
		eagleup		: 3D files 
		library		: eagle part files 
		manufacturing	: files required to produce the desing
			bom	: files created to order the parts
					batteryCharger.txt	: 
					batteryv1.1.csv		: digikey order
					hundredUnits.txt	
			gerber	: files generated to manufacture the board
				: https://oshpark.com/shared_projects/4os8OxLZ
	Readme.txt	: this file
	
