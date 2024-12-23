# 🚀 HIVERA Auto Mining Bot

## 🚀 Quick Start

### Prerequisites
- Node.js (Latest LTS version)
- npm package manager
- Hivera Account ([Register Here](https://t.me/Hiverabot/app?startapp=2597c1372))

### Installation
1. Clone and install dependencies:
   ```bash
   git clone https://github.com/zainarain279/hivera-auto-new.git
   cd hivera-auto-new
   npm install
   ```

2. Get your Hivera JWT:
   - Open [Hivera Bot](https://t.me/Hiverabot/app?startapp=2597c1372)
   - Press F12 for Developer Tools
   - Navigate to Application > Local Storage
   - Copy your Hivera_jwt token

3. Configure your setup:
   - Place JWT token(s) in `users.txt` (one per line)
   - Add proxies in `proxies.txt` (format: http://user:pass@ip:port)
   - Adjust `config.json` settings:
     ```json
     {
       "minPower": 1000,
       "useProxy": true,
       "maxThreads": 5,
       "timeSleep": 5
     }
     ```

### Start Mining
```bash
npm run start
```

##  Tips for Best Performance

- Use reliable proxies
- Monitor power levels
- Keep JWT tokens secure
- Ensure stable internet connection


## 🔗 Links

- [Register Hivera Account](https://t.me/Hiverabot/app?startapp=2597c1372)
