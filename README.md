# CHERNARUS-Shipwrecks-Snippets-PC-and-Console

.XML and .JSON Files for my Shipwrecks Around Chernarus Custom Locations. A ship has broken in two off the coast of Chernarus, Rumor has it that it was carrying military shipments and supplies, Get there quick because theyre begining to float away....

This Repository contains 3 shiwreck locations which are the exact same ship however are in different locations around the map, pick and choose which ones youd like.

Files that can be put into your Mappos.xml files and the json that goes into your custom folder

KamyShipwreck.json or SvetShipwreck.json or BerezinoShipwreck.json file - This file is fine as it is, you can just upload it straight into the CUSTOM folder in dayzOffline.chernarusplus Folder above the DB folder.

KamyShipwreckPOS.XML or SvetShipwreckPOS.XML or BerezinoShipwreck.XML - All you do with this file is Highlight ALL of the code, copy it and paste it into your mapgrouppos.xml file, making sure ther is an empty line above and below it. Highly recommend you do this adding in Notepad++ instead of directly on your server, when done just upload it in the dayzOffline.chernarusplus folder over the top of your old mapgrouppos.xml file and thats it your done.

Last thing you need to do is go into your cfggameplay.json file in the dayzOffline.chernarusplus folder, go to line 31 and put in the JSON file name in the brackets and iverted commas MAKING SURE its starts with custom/ EXAMPLE: "objectSpawnersArr": ["custom/KamyShipwreck.json"], If you want to usemore that one custom location at any given time put a comma after the closing inverted commas and add in the other locations JSON file. EXAMPLE: "objectSpawnersArr": ["custom/KamyShipwreck.json","custom/TISYnpp.json"],

if you need extra help with this i HIGHLY recommend ScaleSpeeders Youtube Video on this - https://www.youtube.com/watch?v=mFPzPId38Qc this shows you in detail how to upload these files to your nitrado server for PC and Console! Skip to timestamp 23:50 and watch from there as it shows you where to put the files and how to get them there.

Thanks for using my Custom Location and i hope you enjoy it
