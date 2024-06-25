# Kali_linux
Get Hands on Linux

# JPS Virus Maker

[JPS Virus Maker](https://github.com/20MH1A04H9/Kali_linux/blob/main/JPS%20Virus%20Maker%203.0.zip) is a tool that can create personalized viruses and convert them into worms. It can manipulate Windows functions, such as disabling the Registry Editor, Task Manager, or Yahoo! Messenger. The virus can also self-install and self-replicate, which can reduce system performance and network bandwidth. However, JPS Virus Maker doesn't harm data, compromise personal information, or cause harm. 



# DDoS attack using HOIC

A system-wide denial of service (DDoS) assault consists of a group of hacked systems, typically infected with Trojans, that are used to launch a DoS attack on a target system or network.
# Configure HOIC

Switch to the Windows 10 and open the HOIC ([hoic.exe](https://github.com/20MH1A04H9/Kali_linux/blob/main/Hoic.rar))

On the HOIC GUI, click '+' to add the target. 

This initiates the DDoS attack on the target (Kali Linux).

Switch to the Kali Linux and launch the Wireshark.
## On the HOIC - [Target] pop-up:

Type the target URL (IP address )

Slide the power bar to High

Select GenericBoost.hoic booster from the drop-down list

Click add
## Kali Wifi drives

Install Wifi Module
## Verify the adapters

#### Step 1: run the command and then Terminal

```
  ifconfig
```

#### Step 2: check the Drivers whether they install or  not

```
  airmon-ng
```

#### Step 3: Download Link

- [WifiDrive](http://linuxwireless.sipsolutions.net/download/compat-wireless-2.6/compat-wireless-2010-06-26-p.tar.bz2)

#### Step 4: Extract the file

```
  tar -jxvf compat-wireless-2010-06-26-p.tar.bz2
```

#### Step 5: Change the floder and Uninstall and reinstalling the drivers 

```
  cd file name 
  make unload
  make load
```
