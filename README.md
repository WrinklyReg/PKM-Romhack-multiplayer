# PKM-Romhack-multiplayer
# MyROMHack-Multiplayer

This project is a custom adaptation of the **GBA-PK Multiplayer** Lua scripts to support a fanmade Pokémon ROM hack based on Generation 3.

The goal is to make the ROM hack multiplayer-compatible, allowing features like:
- Player visibility on the overworld 🧍
- Trading Pokémon between players 🔄
- (Future) Multiplayer battles ⚔️
- (Future) Co-op exploration across multiple regions 🌍

## 📂 Repository Structure
```
MyROMHack-Multiplayer/
│── lua-scripts/
│   ├── client.lua       # Adapted from GBA-PK Client
│   ├── server.lua       # Adapted from GBA-PK Server
│
│── docs/
│   ├── addresses.md     # Memory addresses (vanilla vs hack)
│   ├── roadmap.md       # Development plan & milestones
│
│── README.md            # Project overview
│── LICENSE              # Open-source license (MIT recommended)
│── .gitignore           # Ignore unnecessary files
```

## 🚀 Roadmap
- [ ] Extract and document FireRed memory addresses (player position, party data, etc.)
- [ ] Test client/server scripts with a clean FireRed ROM
- [ ] Apply scripts to the ROM hack and check compatibility
- [ ] Update addresses if hack differs from FireRed
- [ ] Add support for advanced multiplayer features

## 📜 License
Recommended: **MIT License** so others can use, modify, and improve the project.

## 🤝 Contributions
Pull requests are welcome! If you’d like to collaborate, check the `docs/roadmap.md` for open tasks.
