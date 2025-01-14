# GamenessBot 🎮

A Node.js script developed by [@zsan0x](https://t.me/zsan0x) and [@wolfxd618](https://t.me/wolfxd618) to generate Gameness Points automatically.

## ⚡ Features

- Automated point generation
- User-friendly CLI interface with colorful output
- Session-based authentication
- Custom point amount selection
- Progress tracking
- Automatic browser redirect to required channels

## 📋 Prerequisites

Before running this script, make sure you have:

- [Node.js](https://nodejs.org/) (v14 or higher) installed
- Basic knowledge of using terminal/command prompt
- A valid Gameness query ID

## 🛠️ Installation

1. Clone the repository:
```bash
git clone https://github.com/zsan0x/GamenessBot.git
cd GamenessBot
```

2. Install the required dependencies:
```bash
npm install
```

Required dependencies include:
- axios
- chalk
- readline
- open
- figlet

## 🚀 Usage

1. Run the script:
```bash
node index.js
```

2. Follow the interactive prompts:
   - The script will automatically open the required Telegram channels for you to join
   - Enter your query ID when prompted
   - Specify the desired number of points to generate
   - Wait for the process to complete

## 📝 How to Get Query ID

1. Open Gameness in Telegram in PC browser or kiwi Mobile
2. Start a new game session
3. Copy the query ID from the inspecting, Go to network you will find "auth" (it should be there like a long string of characters)
4. Alternatively you can use Bypass Telegram Extension
5. Use this query ID in the script when prompted
![Copy the Value of initData](https://i.postimg.cc/zGgwGFHM/Screenshot-2025-01-14-132216.png)

## ⚠️ Important Notes

- Query IDs expire after 5 minutes
- Make sure to join both Telegram channels before running the script
- Keep your query ID private and don't share it with others
- The script sends requests in batches of 1000 points

## 🤝 Support

For support, join our Telegram channels:
- [@zsan0x](https://t.me/zsan0x)
- [@wolfxd618](https://t.me/wolfxd618)

## ⚖️ License

This project is distributed under the MIT License. See the `LICENSE` file for more information.

## 🙏 Credits

- Developed by [@zsan0x](https://t.me/zsan0x) and [@wolfxd618](https://t.me/wolfxd618)
- Thanks to all contributors and users of this script

---
⭐ Don't forget to star the repository if you find it useful!
