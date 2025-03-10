# Haha Wallet Auto Claimer

An automated tool for claiming karma and completing tasks in Haha Wallet. Built with Node.js and features a terminal-based dashboard interface.

## Features

- Automated daily check-in
- Automatic task completion (basic and social tasks)
- Karma and rank tracking
- Beautiful terminal dashboard interface
- Multi-account support
- Real-time status updates

## Prerequisites

1. Register a Haha Wallet account:

   - Download and install the Haha Wallet extension: [Chrome Web Store](https://chromewebstore.google.com/detail/haha-wallet/andhndehpcjpmneneealacgnmealilal?hl=en-US&utm_source=ext_sidebar)
   - [Register Haha Wallet](https://join.haha.me/GALKURTA-KT5ICC)
   - Complete the registration process

2. Make sure you have installed:
   - Node.js (version 14 or higher)
   - npm (normally comes with Node.js)

## Installation

1. Clone this repository:

```bash
git clone https://codeberg.org/Galkurta/HaHaWallet-BOT.git
cd HaHaWallet-BOT
```

2. Install dependencies:

```bash
npm install
```

3. Edit data.key file:

```bash
# nano data.key
# Format: email:password
# Example:
# youremail@example.com:yourpassword
# anotheremail@example.com:anotherpassword
```

## Usage

To start the bot:

```bash
npm start
```

### Dashboard Controls

- Press `q` or `ESC` to quit
- Press `r` to refresh the screen

## Features Explanation

1. **Multi-Account Support**

   - Process multiple accounts sequentially
   - Each account's progress is tracked separately
   - Secured password storage in local file

2. **Automated Tasks**

   - Daily check-in
   - Basic task completion
   - Social task claiming
   - Karma collection

3. **Dashboard Interface**

   - Real-time status updates
   - Account balance display
   - Task progress tracking
   - Clear visual organization
   - Colored sections for easy reading

4. **Auto-Retry System**
   - Automatic retry on failures
   - 12-hour cycle for daily tasks
   - Error handling and recovery

## Project Structure

```
haha-wallet-bot/
├── package.json
├── data.key               # Account credentials file
└── src/
    ├── main.js             # Main entry point
    ├── api/
    │   └── hahaApi.js       # API calls
    ├── config/
    │   └── userAgents.js    # User agent config
    ├── services/
    │   ├── accountService.js # Account management
    │   └── taskService.js    # Task processing
    └── ui/
        └── dashboard.js      # Dashboard interface
```

## Support

For support, join our Telegram channel: [Galkuta Archive](https://t.me/galkutaarchive)

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Disclaimer

This tool is for educational purposes only. Use at your own risk. The developers are not responsible for any banned accounts or lost karma points.

---
