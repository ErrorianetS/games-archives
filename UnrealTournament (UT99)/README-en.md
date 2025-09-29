# Unreal Tournament (UT99) - Network Setup Guide

Archive by ErrorianetS

This archive contains everything needed to play Unreal Tournament 1999 over network using Radmin VPN.

## Contents

- `UnrealTournament/` - Game folder (portable version)
- `Radmin_VPN_1.4.4642.1.exe` - Radmin VPN installer
- `SteamSetup.exe` - Steam installer (required for some users)
- `Unreal Tournament.lnk` - Desktop shortcut for the game

## Installation & Setup

### 1. Install Required Software

- Install Steam using `SteamSetup.exe` (follow installer instructions)
- Install Radmin VPN using `Radmin_VPN_1.4.4642.1.exe` (required for network play)

### 2. Extract the Game

- Copy the `UnrealTournament` folder to: `C:\Games\UnrealTournament\`
- Important: If `C:\Games` doesn't exist, create it first
- This path is required for the desktop shortcut to work properly

### 3. Configure Radmin VPN

1. Launch Radmin VPN
2. Press `Shift + =` on your keyboard
3. Switch to the "Private Network" tab
4. Join network with these details:
   - Network name: `LolmanVova`
   - Password: `123456`

### 4. Connect to Game Network

- Ensure Radmin VPN is enabled (button next to your IP should be BLUE)
- If the button is red, click it to enable the connection
- Left-click on the `LolmanVova` network in the networks list
- You should now see other players in this network

### 5. Launch the Game

- Use the desktop shortcut `Unreal Tournament.lnk`
- Or run directly: `C:\Games\UnrealTournament\System\UnrealTournament.exe`

### 6. Find LAN Games

- In the game main menu, hover over `Multiplayer`
- Click `Find LAN Games`
- Available servers should appear in the list
- Select a server and click `Join`

## How to Quit the Game

- In main menu: Hover over `Game` and click `Quit`
- During match: Press `ESC` and use the menu tabs at the top
- Any time: Use `Alt + F4`

## Troubleshooting

- Game doesn't see LAN games:
  - Verify Radmin VPN is enabled (blue button)
  - Confirm you joined `LolmanVova` network
  - Check Windows firewall isn't blocking the game

- Desktop shortcut doesn't work:
  - Verify game is extracted to `C:\Games\UnrealTournament\`
  - Run the game directly from `System\UnrealTournament.exe`

- Game crashes on launch:
  - Try running `UnrealTournament.exe` as Administrator
  - Set compatibility mode to Windows XP (SP3) in file properties

## System Requirements

- Windows 7, 10, or 11
- 512MB RAM minimum
- DirectX compatible graphics card
- Internet connection for Radmin VPN

---
For Windows 7/10/11 users (idk abt other devices compatibility). Enjoy the game!
