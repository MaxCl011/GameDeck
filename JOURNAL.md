JOURNAL.MD


November 1st:

##What I did
I researched what specs and components would be required for playing light games and cloud gaming on the handheld, I decided on a Raspberry Pi CM4 with 4GB of RAM. This should allow me to play retro games, cloud games and maybe even some heavily optimised Minecraft Java Edition. Since I want all 4 of the ports (2x USB-A, USB-C, Micro-HDMI) on the top side of the handheld I will need to design a custom carrier board for the CM4. Wiring 2x 5,000mAh batteries in series will allow me to get 10,000mAh in capacity, I will also need to design a battery management board in KiCad and a 3d-printable chassis.  

#Current Component Specifications
##Specifications
-4GB Raspberry pi CM4
-Custom Carrier Board
-7 Inch IPS LCD Display 1024x600
-2x 3.7V 5000mAh LiPo
-Custom Power Board
-Custom 3D Printed Chassis with brass heat set inserts


#Next Steps
Design both the carrier board and the battery management boards in KiCad

Time Spent: 1hr

November 8th:

##What I did
I installed the library that contained the CM4 into KiCad, then I created the schematic for the main carrier board. Then I opened it on the PCB editor and laid out the components onto the board and I connected all of the components together

##Photos
<img width="1470" height="842" alt="Screenshot 2026-11-08 at 9 51 24 AM" src="https://github.com/user-attachments/assets/e01f6dd4-6133-4f6c-8d57-1ee152e46bcd" />
<img width="820" height="469" alt="Screenshot 2026-11-08 at 10 14 08 AM" src="https://github.com/user-attachments/assets/a245c0bc-03eb-4b34-85f1-462979056248" />
<img width="826" height="503" alt="Screenshot 2026-11-08 at 11 24 09 AM" src="https://github.com/user-attachments/assets/79fd142d-c41b-47e7-ada0-02ea103936f4" />

##Next Steps
Check for design rule errors and fix them, then create controller PCB's

Time Spent: 2.5hrs



