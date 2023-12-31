# YAACS - Yet Another Astrocomputer Case System
For Raspberry Pi or other (e.g. Stellarmate and Astroberry on Raspberry or Thin Client PC)

Hi there,

this is a 3D printable case system to build an astro pc made initially for a raspberry Pi4 or/and thin client pc. It uses custom V-shaped connectors that are strong enough and easily interchangeable. There are different variants of the housing, depending on your set-up (see down my setup). You can use the Fusion360 project to alter everything upon your needs. You can combine everything and use the v-mount like dovetails and glue or screw them to whatever you like. Likewise, you require a bigger or smaller housing?: feel free to make your own with the attached Fusion360 code.

As always: please precheck, make prototypes, test before you print with high-quality PLA or PC. And double check the dimensions.

Licence is: Case system for Raspberry Pi © 2023 by Axel C. R. Pospischil is licensed under Attribution-NonCommercial-ShareAlike 4.0 International. To view a copy of this license, visit http://creativecommons.org/licenses/by-nc-sa/4.0/

![image](https://github.com/apos/case_system_stellarmate_astroberry/assets/456034/1d67b81f-250d-4325-87a3-b2c390186f6e)

For THIS PROJECT, you only need the following screws and glue:
- M3/36mm
- M2/12mm
- glue: I recommend Pattex Stabilit Express 2K or super glue)

I am printing the Vixen-style connectors with PLA  (Polymaker Polymax) an the housing parts with PC (Polymaker PC) due to temperature resistance. 
Everything always with 100% infill (you can use cubic infill with 50% but might get trouble. I am printing with a 0,4 or 0,6 nozzle at 0,2 mm layer heigth (you can try 0,3 layer heigt too).

I am printing with a housed Prusa MK3S (housing is needed for PC)

The vixen dovetails are glued to the parts. You could use screws. I do not like that. 


# Additions
## Fixation screw for v-mount
Connection screw for M3x36mm.

![image](https://github.com/apos/case_system_stellarmate_astroberry/assets/456034/bff28585-f9ef-4151-b5d9-16a0b49b1476)

## 12V Block
For the 12V support I am using DC 5,5mm diameter and 2,5mm pin (!!!) jack. I also added a simple fuse on the (+) side (5A to 10A, depending on you usage). They fit perfectly in the housing an can be wired manually using thick (0,4 mm) cable. Don't use to small cables, you'll need the current!

For the housing use these ones
![image](https://github.com/apos/case_system_stellarmate_astroberry/assets/456034/084c2678-271e-4453-a7ca-155448e8c141)

To connect to the box I strongly recommend using **preconfigured, cabled** plugs. You can solder, but it's a) no fun and b) a source for big trouble. Look out, you'll get them very cheap on ebay buying a set of 10 or 20. Nothing is more severe, than loose connections in the night!
- Be aware, there are two tpyes of 5,5mm jacks with a 2.1 and a 2.5mm pin! Use the bigger ones. Most astro equipment uses these. You can also add a few other plugs to the box, just in case (I never had 2.1 equipment).
  
![image](https://github.com/apos/case_system_stellarmate_astroberry/assets/456034/362cf0e7-f642-473a-9b31-183773268dab)

This is with a build in fuse (but you can also use one outside of the housing, which is probly easier).

![image](https://github.com/apos/case_system_stellarmate_astroberry/assets/456034/2c5b6344-7efc-46dd-a160-1202e7d786ab)

**Use a thick cable vor the 12 Input**. Everything is mounted on a Dell Wyse PC for the permanent setup. In the field I am using the Pi4 hat. 

![image](https://github.com/apos/case_system_stellarmate_astroberry/assets/456034/5290c4b2-2836-4a14-a09e-24ba53eba986)


## AZ-EQ-6 mount 
No screws. Glue together with long v-mount. I use simple velcro band to secure it around the mount head. 

![image](https://github.com/apos/case_system_stellarmate_astroberry/assets/456034/6505208a-0a21-4160-a092-0fff6ed295fe)

## Lenovo Think Centre M93P thin client mount
Uses M3x12. Glue together with long v-mount (bottom) and short v-mount on top. 

![image](https://github.com/apos/case_system_stellarmate_astroberry/assets/456034/08ad83d9-1e7d-45fd-8261-ecd764a5b1ca)

## Dell Wyse 5070 mount
Uses M3x12. Glue together with long v-mount (bottom) and short v-mount on top. 

![image](https://github.com/apos/case_system_stellarmate_astroberry/assets/456034/70754b24-77ff-477e-9c35-93da8a9eb406)


## My screws for my 3D printing projects
For all my 3D printig projects I am am using only the following screws (you do not need them all here). This has been proven to be good enough. Don't by them peace by peace! Minimum quantities of 50 or 100 will be as costly as a couple single ones. And you will need them for a lot of projects and can reuse them. 

![image](https://github.com/apos/case_system_stellarmate_astroberry/assets/456034/894673e6-734c-46ea-9cd9-65c6b7c348e7)


## My Stellarmate PC
This design is currently for a RPI 4B (not 3, not 5). Or a Thin client (Lenovo M93P, Dell Wyse 7050).

I currently build the Pi4 with the following hardware addons: 
 - Geekworm NVME hat (via USB) for Raspberry Pi 4 - X862 V2.0. How to boot from USB/NVME is shown here: https://www.stewright.me/2019/10/run-raspbian-from-a-usb-or-ssd-on-a-raspberry-pi-4 or here https://ioastro.com/raspberry-pi-4-boot-from-usb/
 - Geekworm Raspberry Pi 4 Model B passive heat sink

   ![image](https://github.com/apos/case_system_stellarmate_astroberry/assets/456034/d68de966-a92d-4ed0-97bf-c3a811d86933)
   
 - Geekworm X735 V3.0 power hat (https://wiki.geekworm.com/X735) for a stable power supply for the Pi4. I can use any input from 5V (USB-C, MIcro-USB) to 6-30V DC (via a round 5.1 mm jack).
   
   ![image](https://github.com/apos/case_system_stellarmate_astroberry/assets/456034/5eeaae78-9746-4423-adb2-ae63e5d9714e)   
   ![image](https://github.com/apos/case_system_stellarmate_astroberry/assets/456034/92c84bb9-a011-4aae-a41f-6eeed7032a0b)

 - More to come: a [PiFinder](https://www.pifinder.io) hat


 Image sources from amazon.de





### Examples

This is the setup for the Lichtenknecker M100B on my balcony with a PI and an USB-box. You see, this can be very useful.

![image](https://github.com/apos/case_system_stellarmate_astroberry/assets/456034/ca10f55d-26e7-42b1-befa-68aac09f844f)

This ist with an old Astrophysics QNC 400. I simply made a 3D printed connector to the DEC-Axis.

![image](https://github.com/apos/case_system_stellarmate_astroberry/assets/456034/e17fe38f-594d-44b3-8ea8-ac78ca7f67c3)




