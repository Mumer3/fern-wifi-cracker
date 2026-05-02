# 🔐 Fern Wifi Cracker Lab (Wireless Security Testing)

![Platform](https://img.shields.io/badge/Platform-Linux-blue)
![Tool](https://img.shields.io/badge/Tool-Fern%20WiFi%20Cracker-green)
![Type](https://img.shields.io/badge/Type-Wireless%20Security%20Lab-orange)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![License](https://img.shields.io/badge/Use-Educational%20Only-red)

---

## 📌 Overview
**Fern WiFi Cracker** is a wireless security auditing tool used to test the strength of Wi-Fi networks. It identifies vulnerabilities in **WEP, WPA, and WPA2** by attempting password cracking using known techniques.

> ⚠️ **Disclaimer:**  
> This project was performed in a **controlled lab environment** for educational purposes only.  
> Do NOT attempt this on unauthorized networks.

---

## 🛠️ Requirements
- Linux OS 
- Fern WiFi Cracker (pre-installed)
- Wireless Adapter (supports Monitor Mode)
- Wordlist (e.g., `rockyou.txt`)

---

## 🚀 Lab Steps

### 🔹 Step 1: Launch Tool
- Open Applications
- Search: **Fern WiFi Cracker**
- Launch the tool  

![home_page](screenshots/screen1.png)

---

### 🔹 Step 2: Select Interface
- Select interface: `wlan0`
- Enable Monitor Mode  

![select_interface](screenshots/screen2.png)
 
Verify using:
```bash
iwconfig
```

### 🔹 Step 3: Scan Networks
Click Scan for Access Points
Wait for results

![scan_networks](screenshots/screen3.png)

### 🔹 Step 4: Select WPA Networks
Click on WPA Tab
View available networks

![wpa_networks](screenshots/screen4.png)

### 🔹 Step 5: Choose Target

Target Network:

SSID: Test-me
BSSID: 8A:B5:FE:A3:25:AF
Channel: 5
Power: -28
Encryption: WPA
WPS: Enabled

![chosse_target](screenshots/screen5.png)

### 🔹 Step 6: Load Wordlist
Select wordlist (rockyou.txt)
Detect connected clients

![load_wordlists](screenshots/screen6.png)

### 🔹 Step 7: Perform Attack
Click WiFi Attack
🔍 Process:
Deauthenticate client
Capture 4-Way Handshake
Perform Brute Force Attack

![perform_attack](screenshots/screen7.png)

###🔹 Step 8: Retrieve Password
Go to Key Database
View cracked password

![Retrieve_Password](screenshots/screen8.png)

🔎 Key Concepts
Concept	Description
Monitor Mode	Captures wireless packets
4-Way Handshake	WPA/WPA2 authentication
Deauthentication	Forces client reconnect
Brute Force	Tries multiple passwords
📊 Conclusion

This lab shows how weak Wi-Fi security can be exploited.

✅ Recommendations:
Use strong passwords
Disable WPS
Update router firmware
🛡️ Ethical Use

This project is strictly for:

Cybersecurity learning
Penetration testing practice
Lab environments

❌ Illegal usage is strictly prohibited.

👨‍💻 Author

Umer Saqib
Cyber Security Student
