# AtumA3_Blog

## Introduction 
This repository has been a long time goal of mine. I went through grad school and my early career as an educator for technology. RTL has gotten a bad reputation for being hard, but honestly I've seen what software people do, and I'm not convinsed it can't be taught. It is a different language and a mentallity more akin to multi-threading and operating systems, but I think with a few examples you'll feel right at home with the code. The only thing left is to get you thinking like silicon designer and just like that you have all the control and freedom to do what is basically building your own arduino. I'm hoping this repo and the projects within give you something to run with and explore FPGAs.

Through this series I hope to cover just about everything that can be found on this development kit, and with the expansion IO on board, we can cover some new topics for myself. The hope here is that through this series, I learn some new things as I try to explain it to others.

If there ever was a prerequisit to understanding the content here I think most people who find this will meet the need to have a basic understanding of digital logic: AND gates, OR gates, basic binary and if you understand combinational vs sequential circuits that's a big plus.

## Software
[Quartus Prime Pro 26.1](https://www.altera.com/downloads/fpga-development-tools/quartus-prime-pro-edition-design-software-version-26-1-windows)
Windows 11

## Hardware
[Autom A3 Nano](https://www.terasic.com.tw/cgi-bin/page/archive.pl?Language=English&No=1373) Agilex 3 FPGA from Terasic

## Get Started
Quartus Prime Pro while not a free software for production, does offer some really nice free licenses that last 90-days and can be renewed, as well as no-cost licenses for devices like Agilex 3 -- the prodcut used in this series. 

Download the installer for Quartus Prime (link above) and make sure you grab:

The Quartus Prime Pro edition Software (The Main Software)

The Questa Altera FPGA Starter Edition (FPGA Edition is the paid version)

Agilex Common files with Agilex 3 device support (Can't do projects with Agilex 3 without these)

Drivers (These drivers are for programming and interfacing with the device)

Ashling RiscFree IDE for Altera (If you want to do work with embedded processors)

The Quartus Prime Pro Edition Help (A nice to have)

Quartus Prime Pro Edition Programmer and Tools. (The main programme and utility tools)

Next we'll need to license the software. You can do this while things are downloading.
Head to the [Self Service Licensing Center](https://licensing.altera.com/sslc) and make an account there. Once done and confirmed through your email, log in and go to the "Sign up for Evaluation or No-Cost Licenses", and grab the "Quartus Prime Software 90-Day Evaluation". Register a computer by adding a new computer, give it a name, select fixed license, Select NIC ID Computer Type and put in your computers NIC id into the Primary Computer ID Field (look up on google if you need some help here). Save that computer, and generate the license. They will email it to you. 

Once all the software is installed you can open up quartus, get any no-cost licenses they offer you, and go Tools -> License Setup and select your 90-day license with the license file field. 

<img width="802" height="739" alt="image" src="https://github.com/user-attachments/assets/81fbb041-b30f-42ae-be39-eb477ae21e8b" />
