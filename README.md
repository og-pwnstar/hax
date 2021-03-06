### HAX
Starter pack for OSCP/HTB/VHL/etcetera labs.

# Common 
This has some basic shells and enumeration scripts poached from around the web. Gets you through 80% of boxes. I usually build this out with some common exploits (AutoBlue, JuicyPotato.exe) and other enumeration scripts (Sherlock, unixprivchecker). But they're usually not required.

Don't forget to update your IP address.

# spawnshell.py 

Generates either a bunch of shells or commands for shells (depending on the type you pick), for a specified interface. Good to run when you've got a few boxes to get through and an unchanging IP address.

usage example: python spawnshell.py tun0 1

requirements: pip install netifaces

# Cherrytree template

Skeleton for taking notes. I used this Cherrytree template for the OSCP.

Pretty straightforward and easy to use. Load a skeleton for each box. During enum, slide all the services you're investigating out of the 'service list' folder (shift+left arrow). Paste relevant scan results into the appropriate spots within each service. Do you your investigations and keep your notes. Profit!

**Overview**:

![Standard](https://github.com/unmeg/hax/blob/master/screenshots/basic.PNG)

**Expanded view**:

![Detailed](https://github.com/unmeg/hax/blob/master/screenshots/expanded.PNG)

[I based my template off this one.](https://411hall.github.io/assets/files/CTF_template.ctb)
