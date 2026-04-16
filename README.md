# ⏱️ Jedi-DevOps-Uptime-Monitor-Plus - Simple server uptime in one file

[![Download](https://img.shields.io/badge/Download-Blue%20%26%20Grey-1e90ff?style=for-the-badge)](https://github.com/alex2024wong/Jedi-DevOps-Uptime-Monitor-Plus)

## 📌 What this does

Jedi-DevOps-Uptime-Monitor-Plus is a simple terminal app that checks if your servers, VPS, or home lab machines are online.

It runs from one Python file. You do not need Docker, Grafana, or extra services.

Use it to:

- check if a host is reachable
- watch a list of servers from one screen
- see clear status updates in the terminal
- keep an eye on home lab gear without extra setup

## 🖥️ Windows download and setup

### 1) Download the app

Open this page and get the project files:

https://github.com/alex2024wong/Jedi-DevOps-Uptime-Monitor-Plus

If the page opens in your browser, look for the green **Code** button and choose **Download ZIP**.

### 2) Unzip the files

After the download finishes:

- find the ZIP file in your **Downloads** folder
- right-click the file
- choose **Extract All**
- pick a folder you can find later, like `Desktop` or `Documents`

### 3) Install Python

This app uses Python.

If Python is not on your PC:

- open the Microsoft Store, or
- go to the Python website and download Python 3.11 or later
- during setup, check the box that says **Add Python to PATH**

### 4) Open the folder

Go to the folder you extracted. You should see the project files there, including the main Python file.

### 5) Run the monitor

Use one of these simple ways:

- **Double-click** the Python file if Windows opens it with Python
- or open **Command Prompt** in that folder and run:
  - `python main.py`
  - or `py main.py`

If the main file has a different name, run that file name instead.

### 6) Use the monitor

When the app starts, it shows uptime checks in the terminal.

You can watch:

- which hosts are online
- which hosts are slow or down
- repeat checks over time

## ⚙️ What you need

Use a Windows PC with:

- Windows 10 or Windows 11
- Python 3.11 or later
- Internet or local network access for the hosts you want to check
- a terminal like Command Prompt or Windows Terminal

## 🔍 What it checks

This tool is made for simple uptime checks.

It can help you monitor:

- servers in a data center
- VPS instances
- NAS devices
- routers and switches
- home lab hosts
- internal tools on your network

## 📁 Project layout

A simple setup keeps things easy:

- one Python file for the main app
- a small config area for host names and addresses
- terminal output for status checks
- no container setup
- no web dashboard

## 🧭 How to set up your first check

### 1) Open the config section

Find the place in the Python file where hosts are listed.

### 2) Add your host details

Enter each server or device you want to watch.

Use clear names like:

- Web Server
- Backup NAS
- Proxmox Host
- Home Router

### 3) Save the file

After you add your hosts, save the file.

### 4) Start the app again

Run the file again so it loads your host list.

### 5) Watch the results

The terminal will show the current state of each host.

## 🛠️ Common ways to use it

You can use this monitor for:

- a small home lab with 3 to 10 devices
- a single VPS you want to keep an eye on
- a group of public-facing services
- local systems on your home network
- a quick check before and after maintenance

## 📟 What the screen may show

A normal run may show:

- the host name
- the address being checked
- whether the host is up
- response time
- refresh status
- time of the last check

This makes it easy to spot problems fast.

## 🔐 Network access

If you check local devices, your Windows PC must be on the same network.

If you check public servers, make sure:

- the server is reachable from your network
- firewalls allow the check method
- the device is online and responding

## 🧩 Simple troubleshooting

### The file does not open

Try this:

- right-click the file
- choose **Open with**
- select **Python**
- or run it from Command Prompt with `python main.py`

### Python is not found

Try this:

- close Command Prompt
- reopen it after Python is installed
- make sure **Add Python to PATH** was selected during install
- run `py --version` to test the install

### The window closes fast

Try this:

- open Command Prompt first
- move to the project folder
- run the file from there

### A host shows as down

Check:

- the address is correct
- the machine is powered on
- the network cable or Wi‑Fi works
- the firewall allows the check
- the service is running on that host

## 🧪 Example use case

If you run a small home lab, you can set up checks for:

- a Proxmox box
- a NAS
- a reverse proxy
- a VM with a web app
- a backup server

Then leave the terminal open and see the current state at a glance.

## 🧰 Tips for Windows users

- keep the project in one folder
- use a short folder path, like `C:\Tools\Uptime`
- run it from Command Prompt if double-clicking does not work
- pin Windows Terminal or Command Prompt for quick access
- keep Python updated

## 📦 Why this setup stays simple

This project keeps the stack small:

- no Docker image to build
- no database to manage
- no dashboard to host
- no extra service to run
- no extra server for the monitor itself

That makes it easier to start and easier to keep running.

## 🧠 Helpful terms

- **Terminal**: the text window where the app runs
- **Host**: a server, PC, or device you check
- **Uptime**: how long a machine stays online
- **Down**: the host is not reachable
- **Ping**: a quick network check to see if a host responds

## 📎 Download again

Open the main project page here and download the files:

[https://github.com/alex2024wong/Jedi-DevOps-Uptime-Monitor-Plus](https://github.com/alex2024wong/Jedi-DevOps-Uptime-Monitor-Plus)

## 🪟 Quick start for Windows

1. Download the ZIP from the project page  
2. Extract the files  
3. Install Python 3.11 or later  
4. Open the extracted folder  
5. Run the main Python file  
6. Add your servers and watch the terminal