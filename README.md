# Basic WiFi Troubleshooting Guide for Home Networks

## Overview

This project presents a step by step approach to diagnosing and resolving common WiFi related issues in a home environment. The process is based on logical troubleshooting from personal experience and research. The goal is to isolate the source of the issue, test possible causes, and apply clear, easy to follow solutions.

---

## Who This Guide Is For

- Home users experiencing WiFi or connectivity issues  
- Beginners learning IT support fundamentals, including myself  
- Students building an entry level tech portfolio  
- Anyone who wants a repeatable troubleshooting process  

---

## Common WiFi Problems

- No internet connection  
- Connected to WiFi but no internet access  
- Slow internet speeds  
- Frequent disconnections  
- WiFi network not visible  
- One device cannot connect while others can  

---

## Step by Step Troubleshooting

### 1. Identify the Scope of the Issue

- Test multiple devices  
- Determine whether the issue affects one device or the entire network  

---

### 2. Check Physical Connections

- Confirm your modem is powered on  
- Confirm your router is powered on  
- Ensure Ethernet cables are firmly connected  
- Verify that indicator lights show normal activity  

---

### 3. Restart Network Equipment

1. Power off your modem and router  
2. Wait 1 to 2 minutes  
3. Power the modem back on first and wait until it is fully online  
4. After the modem is fully online, power on your router  
5. Reconnect devices and test the connection  

---

### 4. Test Device Settings

- Turn WiFi off and back on  
- Forget the network and reconnect  
- Ensure airplane mode is disabled  
- Check for available or pending system updates  

---

### 5. Renew IP Address

#### Windows

1. Open Command Prompt as administrator  
2. Run the following command:
ipconfig /release

3. Then run:
ipconfig /renew

#### Mac

1. Open System Settings  
2. Click **Network**  
3. Select your active connection  
4. Click **Renew DHCP Lease**  

---

### 6. Check for ISP Issues

1. Log into your internet service provider account  
2. Check the outage map  
3. Confirm current service status  

---

## Basic Networking Concepts

### Modem
Connects your home network to your internet service provider.

### Router
Distributes internet access to devices within your home network.

### IP Address
A numerical address assigned to each device on a network.

### SSID
The name of your wireless network.

### Local vs Internet Issue
A local issue affects only your home network. An internet issue often originates from your service provider.

---

## When to Escalate

- All devices fail to connect after restarting equipment  
- Modem indicator lights show no signal  
- The ISP confirms an outage in your area  
- Hardware appears damaged or malfunctioning  
- You do not have administrator access to network settings  

If these conditions apply, contact your internet service provider or consider replacing faulty hardware.
