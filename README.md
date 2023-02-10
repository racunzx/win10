# win10

#Creating RDP
___________________

First Create Droplet

Go to Recovery Option

#Boot from Recovery Option

Now, First Turn off the droplet & Turn it back again

#Open Console
Press 6 for Interactive Shell


#Paste the gz Image link
wget -O- http://159.65.147.58/win.gz | gunzip | dd of=/dev/vda

Once the file has been downloaded

Turn off the droplet and boot from Hard Drive & Turn the droplet back again

#Launch Recovery console

#And Complete the Networking Configuration

#Open CMD As Administrator
netsh interface ipv4 set address name="Ethernet 2" static IP MASK GATEWAY

netsh interface ipv4 set dns name="Ethernet 2" static DNS

#Now Login Using Remote Desktop Protocol

IP: Provided by DigitalOcean

Login Credentials: 

Username: Hey

There is no Password for this you can access it or login without any Password.
