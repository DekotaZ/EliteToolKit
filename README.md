# Python DDOS V1.0 - IP Stresser & IP Booter Tool 🚀

**Made by https://elitestresser.club 🌟**

Welcome to **Python DDOS V1.0!** 🎉 This is your ultimate IP stresser and IP booter, packed with power as a DDOS tool for testing your own servers. Whether you’re unleashing a **UDP DDOS tool**, a **TCP DDOS tool**, or hitting web servers with **HTTP floods**, this Python-built gem has you covered! 🛠️

⚠️ **Disclaimer**: For educational and authorized testing only! Use this on servers you own or have permission to test. **Unauthorized attacks are illegal!** 🚨

## ✨ Features

### 🔧 Multiple Protocols:
#### **UDP Flood 🌊 (UDP DDOS Tool):**
- **UDP Plain:** Fixed payloads for steady streams. 📦
- **UDP Random:** Random payloads for chaotic fun. 🎲

#### **TCP Flood ⚡ (TCP DDOS Tool):**
- **TCP SYN Flood:** SYN packets to overwhelm targets (Single or Multi-threaded). 🎯
- **TCP Data Flood:** Data blasts after connecting (Single or Multi-threaded). 💾

#### **HTTP Flood 🌐 (IP Stresser):**
- **GET request barrage** for web server stress testing. 📡

### 🎨 Customizable Options:
- **Target IP & port (1-65535)** for pinpoint IP booter action. 🎯
- **Flood duration** in seconds—go as long as you want! ⏱️
- **Packet size (1-65500 bytes)** for UDP & TCP Data floods. 📏
- **TCP styles:** Single socket or 10-thread multi-threaded chaos! 🧵

### 🖥️ User-Friendly Interface:
- **Colorful output** with Colorama. 🌈
- **Input validation** to keep you on track. ✅
- **Packet/request counts** after every flood. 📊
- **🏷️ Window Title:** Sets your console to *"Python DDOS V1.0 By elitestresser.club"*. 😎

## 🛠️ Installation

### 📋 Prerequisites
- **Python 3.x**: Grab it from [python.org](https://www.python.org) if you don’t have it! 🐍
- A terminal (**Command Prompt, PowerShell, or Linux Terminal**). 💻

### 🚀 Steps

#### Clone the Repo:
```bash
git clone https://github.com/yourusername/python-ddos-v1.0.git
cd python-ddos-v1.0
```
_Replace `yourusername` with your GitHub username after uploading! 😉_

#### Install Dependencies: Run this to get the goodies:
```bash
pip install colorama requests
```
- **colorama**: For that rainbow vibe. 🌈
- **requests**: For HTTP flood magic. 🌐

#### Launch It: Fire it up with:
```bash
python ddos_tool.py
```
_Rename `ddos_tool.py` to whatever you save the script as! 📜_

## 🎮 Usage

### Start the Tool:
Run it, and watch the title switch to *"Python DDOS V1.0 By elitestresser.club"*! You’ll see:
```text
Made by elitestresser.club 🌟
=== Network Flood Tool ===
Protocols:
1. UDP
2. TCP
3. HTTP
Select protocol (1-3):
```

### Pick Your Poison:
- **1 for UDP 🌊**, **2 for TCP ⚡**, **3 for HTTP 🌐**.

### Set Up the Flood:
#### **UDP:**
- Method: **1 (Plain)** or **2 (Random)**.
- Enter **IP, port, duration, packet size**.

#### **TCP:**
- Method: **1 (SYN Flood)** or **2 (Data Flood)**.
- Enter **IP, port, duration**.
- Style: **1 (Single)** or **2 (Multi-threaded)**.
- Data Flood needs **packet size** too!

#### **HTTP:**
- Enter **URL and duration**.

### Example Runs:
#### **UDP Random Flood:**
```text
Select protocol (1-3): 1
UDP Methods:
1. UDP Plain (Fixed payload)
2. UDP Random (Random payload)
Select method (1-2): 2
Enter server IP: 192.168.1.100
Enter port (1-65535): 12345
Enter flood duration in seconds: 10
Enter packet size in bytes (1-65500): 1024
[*] Starting UDP Random flood on 192.168.1.100:12345 with 1024-byte packets for 10 seconds...
[+] UDP Random flood complete! Sent 5432 packets.
```

#### **TCP SYN Flood (Multi-threaded):**
```text
Select protocol (1-3): 2
TCP Methods:
1. TCP SYN Flood (Sends SYN packets)
2. TCP Data Flood (Sends data after connection)
Select method (1-2): 1
Enter server IP: 192.168.1.100
Enter port (1-65535): 80
Enter flood duration in seconds: 5
Execution Style:
1. Single (One socket)
2. Multi-threaded (10 threads)
Select style (1-2): 2
[*] Starting TCP SYN flood (Multi-threaded) on 192.168.1.100:80 for 5 seconds...
[+] TCP SYN flood (Multi-threaded) complete! Sent 12345 SYN packets.
```

#### **HTTP Flood:**
```text
Select protocol (1-3): 3
Enter URL (e.g., http://example.com): http://192.168.1.100
Enter flood duration in seconds: 5
[*] Starting HTTP flood on http://192.168.1.100 for 5 seconds...
[+] HTTP flood complete! Sent 234 requests.
```

## 🧠 How It Works
- **UDP DDOS Tool 🌊**: Blasts UDP packets to swamp ports.
- **TCP DDOS Tool ⚡**: SYN floods clog connections; Data floods eat bandwidth.
- **IP Stresser 🌐**: HTTP floods hammer web servers with requests.
- **IP Booter 🎯**: Pinpoint IPs and ports for ultimate control.
- **Track your flood’s impact** with packet/request counts! 📈

## 🙌 Credits
**Made by https://elitestresser.club 🌟**

Crafted by the network testing wizards at [elitestresser.club](https://elitestresser.club), your go-to for IP stresser and IP booter solutions. Check us out for more epic tools! 🚀

## 📜 License
For **educational and legal testing only**. No formal license—use responsibly and **respect the law!** ⚖️

## 🔑 Keywords
🌐 IP Stresser | 🎯 IP Booter | 💥 DDOS Tool | 🌊 UDP DDOS Tool | ⚡ TCP DDOS Tool
