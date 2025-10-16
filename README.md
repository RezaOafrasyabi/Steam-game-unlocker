# Steam Game Installer

**Steam Game Installer** is a desktop application that allows users to manage, download, and install Steam games easily. It features a modern GUI built with **PyWebView** and supports license management, subscription plans, automated deployment from encoded source files, and Steam integration.

---

## Features

### User Management & Licensing
- Login with `username` and `license_key`.
- License validation and decryption.
- Automatic expiration date calculation.
- Supports account types: `standard`, `vip`, and `gift`.
- Gift accounts have limited game access (only select games).

### Game Library Management
- View your game library.
- Add new games to your library.
- Track download and installation status.

### Download & Installation
- Download games from a URL.
- Extract ZIP files and deploy Lua and manifest files to Steam.
- Track progress of downloads and installations with unique worker IDs.
- Deploy files from encoded source files (`src.txt` or `srcgift.txt`).

### Steam Integration
- Detect installed Steam paths automatically.
- Deploy files to Steam config and depotcache directories.
- Restart Steam from the application.

### GUI & User Interface
- Modern GUI window.
- Folder selection dialog.
- List images from the `img` directory.
- Shows download and installation progress in real-time.

### Updates & Internet Check
- Checks for internet connectivity.
- Checks for updates and prompts the user to update if a new version is available.

---

## Running the Application

1. Download the `SteamGameInstaller.exe` file.

2. Double-click the `SteamGameInstaller.exe` to launch the application.

3. The GUI window will open automatically.  

4. Login using your username and license key.

5. After login, you can browse your library, download and install games, or deploy source files.

---

## Available Games for Gift Accounts

Gift accounts have restricted access and can only access the following games:

- Assetto Corsa  
- Atomic Hearts  
- BeamNG Drive  

---

## Notes

- Ensure Steam is installed on your system before using this application.
- Gift accounts have limited access to games.
- Downloaded and deployed files are stored temporarily and cleaned automatically.
- An active internet connection is required for license validation and update checks.

---

## Troubleshooting

- **Cannot detect Steam:** Make sure Steam is installed in the default locations (`C:\Program Files (x86)\Steam` or `C:\Program Files\Steam`).
- **License expired:** Contact support to renew your license.
- **No internet connection:** Check your network connection; the app requires internet to validate licenses and check for updates.

---

## License

This project is for **educational purposes only**. Do **not** use for piracy or unauthorized distribution.

---

## Author

**Reza Afrasyabi**  
Telegram: [@RxA66](https://t.me/RxA66)
