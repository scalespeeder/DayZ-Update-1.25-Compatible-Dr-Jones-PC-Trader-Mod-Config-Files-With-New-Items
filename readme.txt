1.25 Vanilla Dr Jones Update Config & Vehicle Parts Files README

Comments to scalespeeder@gmail.com


To update your Dr Jones Trader to include 1.25 additions, if you have a completely vanilla (no other mods / additions) setup,
 simply upload the included TraderConfig.txt & TraderVehicleParts.txt files over the exisiting files inside your Servers Trader folder, which will be in
 your servers profiles / config / settings (it can have different names) folder. Save & Restart Server.
 
I have also included in the pack the types.xml code snippets to add rubles into server economy.

 These are the classes that were added for 1.24, in case you want to add them to a custom trader config:
 	
	<Category> Sniper Rifles
	SV98,					W,		1600,	960
				
				
	<Category> Magazines
	Mag_SV98_10Rnd,		M,		480,	220

		
 
Thanks, Rob.

BONUS TIP (copyright WOBO!) to remove the gas attacks on Green Mountain Trader, comment out the following line in your Chernarus cfgeventspawns.xml:
<pos x="3710.000000" z="5993.000000" />
		



