# WiFi Hacking Tool

A powerful WiFi penetration testing tool with a sleek red/black GUI interface, designed for security testing and educational purposes.

---

## Features

### Network Scanner
- Scan and display all nearby WiFi networks
- View SSID, BSSID, signal strength, and security type
- Click any network to auto-fill attack targets

### Brute Force Attack
- Multi-threaded password cracking (up to 10 threads)
- Auto-generate passwords if no wordlist provided
- Real-time progress bar with speed indicator
- Stop button to halt attack instantly
- Support for custom wordlists

### Deauth Attack
- Disconnect clients from target network
- Broadcast or targeted client attacks
- Configurable packet count
- Real-time packet counter

### Password Generator
- Generate random passwords with custom length
- Include/exclude lowercase, uppercase, numbers, symbols
- Generate up to 1000 passwords at once
- Save generated passwords to file
- Common password patterns (names + years, phone numbers, etc.)

### Password Extractor
- Extract all saved WiFi passwords from Windows
- Display SSID and password in organized table
- Export passwords to text file

### Discord Webhook Integration
- Send notifications to Discord server
- Alert when password is found
- Attack status updates
- Test webhook connection
- Enable/disable toggle

### Connection Manager
- Connect to WiFi networks
- Disconnect from current network
- Show/hide password toggle

### Live Console
- Real-time log output
- Color-coded messages
- Clear console button
- Stop all attacks button

---

## Attack Types

| Attack | Target | Requirement | Speed |
|--------|--------|-------------|-------|
| Brute Force | SSID (name) | Wordlist | Fast |
| Deauth | BSSID (MAC) | Monitor mode | Instant |

---

## Password Generator Types

| Type | Example | Best For |
|------|---------|----------|
| Name + Year | mike990 | Personal networks |
| Name + Symbol | mohammed@123 | Common patterns |
| Phone Number | 01012345678 | Egyptian networks |
| Random | Kx7#mP2$ | Strong passwords |

---

## Discord Notifications

When password is found:
```
🔓 WIFI PASSWORD FOUND!
📡 Network: MyWiFi
🔑 Password: 123135@f3135
🔢 Attempts: 42
⏰ Time: 3.5 seconds
```

---

## System Requirements

- Windows 7/8/10/11
- Python 3.7+ (or standalone EXE)
- 2GB RAM minimum
- WiFi adapter
- Administrator privileges

---

## Quick Start

1. Launch the tool as Administrator
2. Go to Scanner tab and click "Scan Networks"
3. Click on target network
4. Go to Brute Force tab
5. Click "Generate Passwords" or browse wordlist
6. Click "Start Brute Force"
7. Monitor progress in Console

---

## Security Features

- Stop button for instant halt
- Stop all attacks button
- Window close protection
- Attack status indicators
- Thread-safe operations
- Graceful shutdown

---

## GUI Tabs

| Tab | Function |
|-----|----------|
| 📡 Scanner | Find networks |
| 💣 Brute Force | Crack passwords |
| 📡 Deauth | Disconnect clients |
| 🎲 Generator | Create passwords |
| 🔑 Passwords | Extract saved |
| 🔗 Connect | Manual connection |
| 🔔 Webhook | Discord alerts |
| 💻 Console | View logs |

Success Rates
|Attack Type	Windows	Linux	Requirements
|Brute Force	|70-85%|	85-95%	Wordlist
|Deauth	5-15%	90-95%| Monitor Mode Adapter
|Password Extract	|100%	N/A	Windows Only
|Network Scan	|100%	100%	WiFi Adapter
|Password Success Rates
|Password Type	Example	Success Rate	Time Required
|Weak	12345678	95%	Seconds
|Common	ahmed123	80%	Minutes
|Name + Year	ahmed1990	70%	Minutes
|Phone Number	01012345678	65%	Minutes
|Random 8-char	Kx7#mP2$	15%	Hours
|Strong 12+ char	X9#mK2$pL4@v	5%	Days/Years
|Deauth Success Rates
|Setup	Success Rate
|Linux + Monitor Mode Adapter	90-95%
|Windows + Npcap + Scapy	20-40%
|Windows Basic Adapter	5-10%
|No Monitor Mode Support	0%

## Warning

⚠️ **For educational purposes only**

- Only use on networks you own
- Get permission before testing
- Unauthorized access is illegal
- Use responsibly and ethically
