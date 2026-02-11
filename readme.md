# 🧱 Minecraft Bedrock Server (MBSW)

This repository contains configuration files and world data for a Minecraft Bedrock Dedicated Server.

⚠ The server executable (`bedrock_server.exe`) is **NOT included** in this repository because GitHub does not allow files larger than 100MB.

---

## 📥 Download Server Executable

Download the official Bedrock server executable from:

Official Mojang Download Page:  
https://www.minecraft.net/en-us/download/server/bedrock

OR download from this project release page:

https://github.com/HexaGhost-09/MBSW/releases

---

## 📂 Repository Structure

```
behavior_packs/
resource_packs/
worlds/
server.properties
permissions.json
allowlist.json
```

### Included:
- ✅ World data
- ✅ Server configuration
- ✅ Custom behavior/resource packs

### Not Included:
- ❌ bedrock_server.exe
- ❌ Large vanilla binaries

---

## 🚀 Setup Instructions

1. Download `bedrock_server.exe`
2. Place it inside the project root folder
3. Run:

```
bedrock_server.exe
```

The server will start using the included world and configuration files.

---

## 🛠 Requirements

- Windows 64-bit
- Latest Minecraft Bedrock Server version

---

## 🔄 Updating Server

When updating:
- Replace only `bedrock_server.exe`
- Do NOT delete `worlds/` or configuration files
