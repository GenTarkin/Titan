# KNC Titan Improved Firmware

*DUE TO ABUSE of the free version... only the PAID version is available now!*
TO PURCHASE go here: http://bitcoinlasvegas.net/kncminer-titan-custom-firmware-mod-paid-membership-page/

*NOTE!!!! THIS FIRMWARE WILL NOT WORK CORRECTLY FROM A SIMPLE GIT CLONE OF THE REPO!*
*it MUST be installed properly via a release .bin found under releases tab!*
---
Based on 2.0 firmware for KNC KNCminer Titan, My modificatoins:
*Coded w/ RELIABILITY & SAFETY of the Titan in mind...



New method of "Dead Die" handling - power cycles cube w/ "Dead Die" to attempt to get it working w/o manual power cycling.

*NOTE*: There seems to be an ever growing amount of confusion as to whats meant above. The "Dead Die" only refers to dies which "go to sleep, drop, stop hashing" .. my firmware DOES NOT handle completely dead(hardware level) dies! Those still need to be set OFF!

Added ability to switch between STOCK 5.1.0 BFGminer version vs newer 5.3.0 ver.

Added DCDC temp monitoring & corrective action of 25mhz dropping on dies till DCDC temps are below threshold specified.

In addition to the above, dies which were previously throttled will raise their clocks once under the threshold temperature setting by 10%.

FAN-FAIL protection - works when DCDC monitoring enabled, if temp rises 10C above threshold or goes to 115C it will set those dies to OFF.

FAN-FAIL notifications added to STATUS page & LCD showing the cube(s) w/ possible failed fan.

Dies which cause constant soft / hard resets will be auto-bypassed for future resets.
Message will be displayed on advanced page if any dies get autobypassed & option to clear the list.

Added "Wall Watts" to ADVANCED page.

Made "cube watts" consumption read out on ADVANCED page more accurate.

Added option to SYSTEM page to change PSU effeciency - defaults to 85%.

Added ability to choose between multiple webgui languages.

Added more stats to STATUS page.

Added miner name to not only STATUS but MINING & ADVANCED page.

Added "donation status" to reflect which donation plan ur Titan is running.

Added Mod version info on STATUS page.

Added "Upgrade" button to STATUS page to perform "OTA" updates to my latest releases!!

Ability to flash my mod to stock 2.00 KNC firmware via SYSTEM->UPGRADE page using the .bin files hosted on my releases!

Added option under SYSTEM to disable lighttpd access loggin(saves SD card life).

When creating backup, it now saves clocks, voltages & miner name(if specified).

Redesigned all branding graphics & information for webgui.

Modified LCD readout to show my mod & version information.

Integraded p4fg's KNCminion webgui interface & put link on status page to it.

Option to enable/disable readonly API access from all IP's in MINING page.



--------

*NOTES:*
DCDC threshold settings & BFGMiner version is settable in webgui under ADVANCED tab.
Current DCDC mod settings & running BFGMiner version are shown in ADVANCED tab.

For questions or development progress / info / feedback go here:
https://bitcointalk.org/index.php?topic=170332.msg12997995#msg12997995
OR
https://bitcointalk.org/index.php?topic=1161011.0
OR
https://litecointalk.org/index.php?topic=27635.0

--------

Ive implimented 2 payment options, details are below:

1. Upfront payment of $50:
TO PURCHASE go here: http://gentarkincustomtitan.pcriot.com (btc payment only) OR http://www.ebay.com/sch/i.html?_nkw=titan+firmware

2. NO LONGER AVAILABLE! - The version available for download as an img here on github in my releases, this has a built in .75% DAILY donation where your Titan mines for me roughly 11mins /day.

NOTE: The fee's / sales are ONLY for my custom modifications to the original firmware. Im not "selling" the original firmware.



DISCLAIMER: In the unforunate even of ur Titan catastrophically failing while my firmware is installed... I am in no way responsible for the damages.

*I have not coded anything harmful to the Titan, Ive largely created "smarter"(more reliable & safer) running condition handling of the Titan.


![Status Page](http://i.imgur.com/AMJFpLw.png)
![Advanced Page](http://i.imgur.com/CjByNgb.png)
