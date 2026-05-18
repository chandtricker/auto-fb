# CHAND TOOL - Facebook Account Creator & UID Checker

## 📌 Requirements
- Python 3.8+
- Internet connection
- Termux (Android) / Linux / Windows

## 🚀 Installation & Run

### Termux (Android)
```bash
pkg update -y
pkg install python git -y
git clone https://github.com/chandtricker/auto-fb
cd auto-fb
python auto.py
```
> Modules auto-install hojayenge pehli baar run karte hi.

### Linux / Windows
```bash
git clone https://github.com/chandtricker/auto-fb
cd auto-fb
python auto.py
```

## 📋 Features

| Option | Feature | Description |
|--------|---------|-------------|
| **1** | **AUTO CREATE FB** | Facebook account creation (2 methods) |
| **2** | **UID CHECKER** | Check UIDs live/death from TXT file |
| **3** | **SPREAD UID** | Extract clean UIDs from messy files |

### 1️⃣ AUTO CREATE FB
- **METHOD 1** - Web form based Facebook account creation
- **METHOD 2** - API based Facebook account creation
- Auto-generates names (Philippines, Indonesia, Vietnam)
- Results saved in `/sdcard/AUTO_CREATE_CHAND/`

### 2️⃣ UID CHECKER
- Input: TXT file with UIDs (one per line)
- Checks each UID via Facebook Graph API
- ✅ **LIVE UIDs** → Green color, saved to `ALIVE-UID-CHAND/LIVE-UID.txt`
- ❌ **DEATH UIDs** → Red color, saved to `ALIVE-UID-CHAND/DEATH-UID.txt`

### 3️⃣ SPREAD UID
- Input: TXT file with messy UID data (e.g. `61578884861227 | NAME`)
- Extracts only UIDs
- Saves clean UIDs to `SPREAD-UID-CHAND/SPREAD-UID.txt`

## 📁 Output Folders

| Folder | Contents |
|--------|----------|
| `AUTO_CREATE_CHAND/` | Created FB accounts (UID + password + cookie) |
| `ALIVE-UID-CHAND/` | Live & Death UID lists |
| `SPREAD-UID-CHAND/` | Extracted clean UIDs |

## 🔗 Channels
- **YouTube**: https://www.youtube.com/@chandtricker
- **WhatsApp**: https://whatsapp.com/channel/0029VaZrEGYIN9ih4PxcFQ33

## ⚠️ Note
- Tool is encrypted with PyArmor for security
- Internet required for all operations
- Auto-installs required Python packages on first run
