# Cyber.io

                              ,ad8888ba,              88                                           88               
                             d8"'    `"8b             88                                           ""               
                            d8'                       88                                                            
                            88           8b       d8  88,dPPYba,    ,adPPYba,  8b,dPPYba,          88   ,adPPYba,   
                            88           `8b     d8'  88P'    "8a  a8P_____88  88P'   "Y8          88  a8"     "8a  
                            Y8,           `8b   d8'   88       d8  8PP"""""""  88                  88  8b       d8  
                             Y8a.    .a8P  `8b,d8'    88b,   ,a8"  "8b,   ,aa  88             888  88  "8a,   ,a8"  
                              `"Y8888Y"'     Y88'     8Y"Ybbd8"'    `"Ybbd8"'  88             888  88   `"YbbdP"'   
                                             d8'                                                                    
                                            d8'   
                
                
                
# Overview

A Cybersecurity and Pentesting script to assist in Wi-Fi audits.  

It allows to decrypt WEP / WPA / WPA2 encrypt (no commands needed) in a graphical and intuitive way. 
In addition, it also allows to emulate a Rogue AP (dummy access point) with customs logins.

# Functions
- Two runtime enviroments:

      1. Graphical -> Fully intuitive environment and similar to the installation of any software. Without Terminal.
      2. Terminal  -> In terminal. Without commands, just press the numbers to choose the desired option (recommended for light PCs or launched from mobiles or tablets. 
                      It consumes almost no resources).

- .....
  
# Contents

# Installation

# Pre-requisites

Software

- Ubuntu/Debian/Kali-linux/Parrot
- Dependencies/packages:
    1. 
    2.
    3.
    4.
  

Hardware

You need a wifi card that supports "access point"/"master" mode. You can check whether it does by running: iw list You want to see "AP" in the output. Something like:

Supported interface modes:
         * IBSS
         * managed
         * AP
         * AP/VLAN
         * monitor
         * mesh point

Example of working cards:

Ubiquiti SR-71: (chipset AR9170, driver carl9170 http://wireless.kernel.org/en/users/Drivers/carl9170)
Alfa Black AWUS036NHA (chipset Atheros AR9271)
TP-Link TL-WN722N (chipset Atheros AR9271 )


# Running

You have to run it as root (the script will detect if you are root or user, in that last case, it will exit automatically).

# Designed by
Recse
