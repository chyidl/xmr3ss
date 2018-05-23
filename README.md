# xmr3ss (XiaoMi Router 3 Install Shadowsocks)

XiaoMi Router 3 Turns On SHH and Install Shadowsocks

## Getting Started

These instructions will get you a copy of the project up and running on your router for successful install Shadowsocks, Complete the function of accessing Google in local LAN.

### Prerequisites

XiaoMi Router 3 Information 

```code
	Processor:			MT7620A
	ROM:				128MB SLC Nand Flash 
	RAM:				128MB DDR2
	Wi-Fi protocols:	802.11n,2.4GHz 2x2 (speed up to 300Mbps);5GHz 2x2 (speed up to 867Mbps)
	Operating system:	MiWiFi OS(Based on OpenWRT)
	ROM version number: 2.25.46 
```

Open SSH
* [Open SSH](https://d.miwifi.com/rom/ssh/) - Open SSH, login XiaoMi account,Check the root password and remember.

```text
	1. Please copy the downloaded tool bin file to the root directory of the U disk (FAT/FAT32 format) to ensure that the file name is miwifi_ssh.bin.
	2. Disconnect the Power of the xiaomi router and insert the U disk into the USB interface.
	3. Hold down the reset button and then reconnect the power. The indicator will turn yellow and the reset key will be released.
	4. Wait 3-5 seconds after the installation is complete, the xiaomi router will automatically restart, after that,enjoy it.
```

### Installing

```code
	$ ssh root@192.168.31.1 
	# Input the root password, 
	$ passwd # change root password recommanded 
	# Login to the router terminal Success 
	$ cd /tmp &&rm -rf miwifi.sh && wget https://raw.githubusercontent.com/Chyi341152/xmr3ss/master/miwifi.sh && chmod +x miwifi.sh && sh ./miwifi.sh
```
Install Screen shot:
![Install Screenshot](https://raw.githubusercontent.com/Chyi341152/xmr3ss/master/xmr3ss/imgs/10.34.52.PM.png)


## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Hat tip to anyone who's code was used
* Inspiration
* etc

