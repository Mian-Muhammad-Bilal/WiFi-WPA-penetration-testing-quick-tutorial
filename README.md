# WiFi WPA Penetration Testing Tutorial

This repository contains a comprehensive guide on how to perform WiFi WPA penetration testing using various tools on Kali Linux, including Airgeddon, Wifite, Aircrack-ng, and Fern Wifi Cracker.

## Table of Contents

- [Introduction](#introduction)
- [Software Requirements](#software-requirements)
- [Hardware Requirements](#hardware-requirements)
- [Step-by-Step Tutorial](#step-by-step-tutorial)
- [Disclaimer](#disclaimer)

## Introduction

WiFi penetration testing is a method used to evaluate the security of wireless networks. This tutorial focuses on testing WPA-protected networks using tools available on Kali Linux. **Airgeddon** is the primary tool used in this guide, alongside other useful utilities.

## Software Requirements

To follow this tutorial, you will need the following software installed on your Kali Linux machine:

- **Wifite**
- **Airgeddon**
- **Aircrack-ng**

## Hardware Requirements

You'll need a wireless network adapter that supports monitor mode, such as:

- **Alfa WLAN USB Adapter** 
- Or any other WiFi adapter that supports monitor mode.

## Step-by-Step Tutorial

1. **Open Terminal**: Launch a terminal on your Kali Linux machine.
2. **Run Airgeddon**: Type `sudo Airgeddon` to start the tool.
3. **Check Setup**: Ensure all prerequisites are configured correctly.
4. **Select Target Network**: Scan for WiFi networks and select your target.
5. **Send Deauthentication Packets**: Use Airgeddon to send deauth packets to the target network.
6. **Capture Handshake**: Wait for Airgeddon to capture the WPA handshake.
7. **Decrypt Handshake**: Use the decrypt menu to attempt cracking the WPA key using dictionary attacks or other methods.

For a detailed step-by-step guide with screenshots, refer to the full tutorial in the document.

## Disclaimer

This tutorial is intended for educational purposes only. Unauthorized penetration testing of networks without explicit permission is illegal and unethical. Always ensure you have authorization before testing any network.

---

Feel free to contribute or report any issues!

