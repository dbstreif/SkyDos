//SkyDos, written by Dominic Streif
//https://github.com/Dom13377/SkyDos.git

I AM NOT RESPONSIBLE FOR THE MISUSE OF THIS PROGRAM!

Make sure to run with root or adminastrative permissions

Usage:
(D)enial (o)f (S)ervice toolkit for stress testing purposes

Modules:

http, icmp, udp, tcp(synflood)

Options:

target, port, count

ex. target 192.168.0.1
ex. target www.google.com
ex. port 80
ex. count 1000
ex. count 0 (This sends an infinite amount of packets CTRL + C to quit)

INSTALLATION:

sudo pip3 install -r requirements.txt

or on windows:
Open the cmd in aministrative mode then type: pip3 install -r requirements.txt

then:
sudo python3 skydos.py

or on windows:
Open the cmd in aministrative mode then type: python3 skydos.py