# HWID-shifter
Spoofing the Windows 10 HDD/diskdrive serialnumber from kernel
Tested on x64 Windows 10 20H2.

## Motivation 
The initial motivation is bypassing HWID detection methods used by intrusive software like anti-cheats, etc. or licensing restrictions implemented in software.

![HWID-shifter](https://i.imgur.com/7BDzLVm.png)
![HWID-shifter](https://i.imgur.com/x5OuS6g.png)
![HWID-shifter](https://i.imgur.com/fDd9Kjt.png)
![HWID-shifter](https://i.imgur.com/MHSgIfZ.png)

## How To Run
1 Open the ```Release```
2 Run the ```Run_Me.bat``` as administrator (Otherwise, it can't run the Spoofer)
3 Choose your an option and done

## Usage Ideas
 Fakes the serial number for HDDs/disk drives
- It's tricky but can be used on EAC or BattlEye
- Protect Hardware Identifications
- Staying anonymous
- It's more like a PoC, there are many things to optimize
- It generates a random serial with a fixed length that can be changed
- It also changes the registry entries to the faked serial via an internal kernel function

## Note
- Its for educational purposes only and I'm not responsible for your usage.
