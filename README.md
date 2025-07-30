# Valorant Cheats - Ultimate Aimbot, ESP, and Wallhack Tool
![valorant-cheat](https://github.com/user-attachments/assets/ff42e8b3-7c8b-4154-9c16-de8d0a8cc791)

  

## Overview
Welcome to the **Valorant Cheats** repository! This project provides advanced tools for Valorant, including a powerful **Valorant aimbot**, **Valorant ESP**, **Valorant wallhack**, and other hacks. Built with C++ and memory manipulation techniques.

## Features
- **Valorant Aimbot**: Smooth aiming with customizable FOV, bone targeting (head, body), and prediction for moving targets. Undetected against Vanguard.
- **Valorant Wallhack**: See enemies through walls with color-coded outlines (red for enemies, green for teammates).
- **Valorant ESP**: Displays player info like health, distance, weapons, and abilities in real-time overlays.
- **Valorant Triggerbot**: Auto-fires when crosshair is on an enemy.
- **Recoil Control & No-Spread**: Eliminates weapon recoil and bullet spread.
- **Skin Changer & Radar Hack**: Customize agent skins and get a mini-map radar for enemy positions.
- **Bypass Vanguard**: Methods to evade Riot's anti-cheat (e.g., kernel-level injection).

All features configurable via an in-game menu. Optimized for Windows 10/11.

## Installation
1. **Clone the Repo**:
   ```
   git clone https://github.com/playerbay/valorant-cheats.git
   ```
2. **Install Dependencies**:
   - Visual Studio 2022 with C++ Desktop Development.
   - External libs: ImGui for UI, MinHook for detours.
   ```
   vcpkg install imgui minhook
   ```
3. **Build the Project**:
   - Open `ValorantCheats.sln` in Visual Studio.
   - Build in Release mode for x64.
4. **Inject the DLL**:
   - Use Cheat Engine or Extreme Injector to load `ValorantAimbot.dll` into the game process.
   - Run Valorant and press `INSERT` to toggle the menu.

## Usage
- Launch Valorant.
- Inject the DLL.
- Customize settings in the overlay menu:
  - Aimbot Strength: 0-100 (best Valorant aimbot settings).
  - ESP Visibility: Toggle walls, names, health bars.
- Use features like Valorant wallhack and triggerbot.

For undetected Valorant cheats, rotate VPNs and avoid suspicious behavior.

## Configuration Example
Sample `config.ini`:

```ini
[Aimbot]
Enabled = true
FOV = 90
Smoothness = 5.0
TargetBone = head

[ESP]
Enabled = true
EnemyColor = red
TeamColor = green
MaxDistance = 500

[Wallhack]
Enabled = true
GlowIntensity = 2.0
```

## Contributing
Open-source (MIT License)—fork and contribute features like Valorant speedhack or bunnyhop script.

## License
MIT License. See [LICENSE](LICENSE).

## Support & Community
- Discord: discord.gg/playerbay
- Issues: Open with tags like "valorant esp not working."
- For More cheats, visit [PlayerBay](https://playerbay.net/).
