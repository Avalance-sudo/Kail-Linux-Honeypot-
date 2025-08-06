# Kail-Linux-Honeypot-
Using Kali Linux to build a honeypot—a decoy system or network designed to attract attackers—allows security teams to monitor and analyze attack techniques while safeguarding the actual infrastructure. A honeypot is a decoy, or a trap to attract hackers into a compture system.The main object of useing honeypt is to monitor the hacker's exploit of the system's vulnerabilites.It alloes the systems weakness and apply neccessary security measures to strengthen it from future attacks.

# Lab Setup

-VirtualBox

-Kail Linux 

-Runy interpreter 

-Parrot OS

-Pentbox Tools

# HoneyPot Setup 


Setup Process:

1.Install Ruby (if not already installed) 
Pentbox is written in Ruby, so we need Ruby to run it.

sudo apt update

sudo apt install ruby -y

2.Clone the Pentbox Repository
'''git clone https://github.com/technicaldada/pentbox.git'''

3. Change into the Pentbox Directory 
''' cd pentbox'''

4. Extract Files (if useing the .tar.gz version)
If you download Pentbox as a compressed file:
'''tar -zxvf pentbox.tar.gz
cd pentbox-1.8'''

5. Run Pentbox 
'''./pentbox.rb'''

Setting up the Honeypot
1. Seclect 2 Network tools section from the Pentbox mennu
2. Then chose 3 Honeypot 
3.Follow the prompts:
   - It may ask for a port number (you can use default 23 or another port like 88 if 23 is blocked).
    -You’ll be notified that the honeypot is listening on the port.
