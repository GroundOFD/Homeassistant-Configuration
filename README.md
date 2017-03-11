# Homeassistant-Configuration
Initial configuration after first pass through documentation and examples


This all started with ONE ECHO DOT ...

We now have three ... a whole bunch of Philips Hue lighting devices .... Z-Wave sensors ... Webcams ... Raspberry Pi 3s 
... Netatmo, Home Coach, and Indoor/Outdoor monitor plus Welcome device ... TP-Link Switches ... and an iBeacon.

I am of course always in trouble with my lovely wife (Only Joking ... she actually thinks it's good to keep me out of trouble!).

The inspiration to move to Homeassistant came after an aborted attempt at OpenHabian ... I just couldn't get anything to work in that;
most likely my fault not the product!

I wanted accurate monitoring and control of the vivarium that my pet tortoise uses (when she isn't wandering around the upstairs rooms).

With this initial configuration as commited I have acheived all of that and more besides.

The Bathroom light is controlled by the positon of the sun and during the night hours by a PIR sensor in the bedroom.

The heater and UV lamp in Moo's (my tortoise is called Martha ... but she is grumpy :-)  ) vivarium are trigered by the temperature sensor 
installed and also dependent on the position of the sun (she needs to be a little warmer during the day) plus the UV lamp really only needs
to be on in the first part of the day when she basks under the heat lamp.

The Kitchen and Living room lights are turned on if either my wife or myself (or both) are at home just before sunset this is facilitated
by a companion implemetation of OwnTracks and the iBeacon previoulsy listed.

I have installed an additional Aeotec Gen5 Multisensor in our office room and am currently working on integrating that to improve the logic
that controls the lighting as the later part of the evening sets in. Right at the moment the single PIR in the bedroom provides a limited
set of options and the automation lacks some finesse.

Altogether this is proving to be a challenging project which is extremely educational as I come from an almost pure windows background.
Working with the linux based OS of the Raspberry Pi provides an enormous number of both frustrating and at times almost childishly 
joyful moments as barriers are met and overcome.

I am not young (58 at the initial commit date) but I find my mind is blissfully unaware of the creeping up of physical limitations and as
such I expect to be expanding this amazing area of discovery for quite some time!
