# MiniRack
This is the documentation on the MiniRack Project that I have been building.


![IMG_0137](https://github.com/user-attachments/assets/7810abb0-068c-4a1f-90ff-d698d25754b1)

### Rack Base

The Mini Rack project comes from Jeff Geerling's project MiniRack at https://mini-rack.jeffgeerling.com/.
The base of my Rack is the 8U 10in DeskPi Server Cabinet from GeekPi. From GeekPi there is the 12 Port patch pannel,
and ITX Motherboard Shelf. 

The Switch in the Rack is the MikroTik CRS310-8G+2S+in. This is a manged switch allowing for Vlan configuation and is running RouterOS.

### Server

The Server running on the ITX shelf containts the 
ASRock B650I Lightning WiFi 6E (Motherboard), 
AMD Ryzen 5 8500G 6-Core, 12-Thread(CPU), and 
Crucial Pro RAM 64GB Kit (2x32GB) DDR5 5600MT/s (or 5200MT/s or 4800MT/s).
There is also a WD 1TB m.2 running as the boot drive and another Samsung Evo 860 1TB for external storage.
Currently there is a 850 power supply powering the server but this will most likely be replaced by something more efficent

This server is running proxmox allowing for virtual envrioments control. With 64 GBs of Ram the server is able to run many different linux based VMs.

![IMG_0144](https://github.com/user-attachments/assets/f5823b20-a7ce-43fd-a3db-b4a50649ff12)


### Firewall
Connected to the MiniRack is a HP EliteDesk G3 with 32Gbs of RAM running OpnSense.
