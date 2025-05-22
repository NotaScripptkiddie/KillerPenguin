# 🐧 KillerPenguin Tool

```
                      .---.
                     /     \
                    | o _ o |
                    |  \_/  |
     .----._______.-----.----.
    (___________I_I_I_I_I____)
        /      \     /      \
       /        \___/        \
      /                       \
      |     KillerPenguin     |
      \        UTILITY        /
       \      by Sumit       /
        \___________________/
```

## 📋 Overview

KillerPenguin is an all-in-one command-line utility tool designed to assist with network scanning, system monitoring, security testing, and various day-to-day tasks for Linux users. This bash-based tool brings together multiple utilities in a simple menu-driven interface.

## 🌟 Features

- **Network Scanning**: Scan networks with Nmap
- **Directory Enumeration**: Find hidden directories on websites
- **Web Browsing**: Open URLs directly from the terminal
- **IP Information**: Get your public IP and look up IP details
- **URL Redirect Checker**: Analyze short URLs for redirects
- **System Monitoring**: Check CPU, memory, and disk usage
- **Internet Speed Testing**: Test your connection speed
- **Password Generation**: Create strong random passwords
- **Weather Information**: Get current weather for any city
- **YouTube Downloading**: Download videos in various formats

## 🔧 Installation

### Prerequisites

KillerPenguin depends on the following tools:
- nmap
- curl
- wget
- speedtest-cli
- lolcat
- yt-dlp

### Quick Setup

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/KillerPenguin.git
   cd KillerPenguin
   ```

2. Make the script executable:
   ```bash
   chmod +x killerpenguin.sh
   ```

3. Run KillerPenguin:
   ```bash
   ./killerpenguin.sh
   ```

## 📝 Usage

Simply run the script and select an option from the menu by entering the corresponding number:

```
+------------------------------------------------+
|             KILLERPENGUIN TOOL                 |
+------------------------------------------------+
| 1) Nmap scan           | 7) System Monitor     |
| 2) Directory enum      | 8) Check Internet Speed|
| 3) Browse web          | 9) Password generate  |
| 4) Get IP Address      | 10) Weather Info      |
| 5) Check IP Address    | 11) YouTube Download  |
| 6) Check Short URL Info| 12) Clear Terminal    |
|                        | 13) Exit              |
+------------------------------------------------+
```

## 🤝 Contributing

We welcome contributions from the community! Here's how you can help make KillerPenguin even better:

### Ways to Contribute

1. **Add New Features**: Implement new utility functions that could benefit users
2. **Improve Existing Features**: Enhance current functionalities with better implementations
3. **Bug Fixes**: Help identify and fix any issues in the code
4. **Documentation**: Improve this README or add in-script documentation
5. **Testing**: Test the tool on different systems and report any issues

### Contribution Process

1. Fork the repository
2. Create a new branch for your feature: `git checkout -b feature-name`
3. Implement your changes
4. Add clear comments to your code
5. Test your changes thoroughly
6. Submit a pull request with a detailed description of your changes

### Coding Guidelines

- Keep the code clean and well-commented
- Follow bash best practices
- Ensure your feature works across different Linux distributions
- Maintain the existing error handling approach
- Keep the user interface consistent with the current design

### Feature Request

If you have ideas for new features but don't want to implement them yourself, feel free to open an issue with the label "feature request". Describe your idea in detail, including:

- What the feature should do
- Why it would be useful
- Any external dependencies it might require

## 🛡️ Security Notice

KillerPenguin includes tools that can be used for network scanning and security testing. Always ensure you have proper authorization before scanning networks or systems that don't belong to you. Unauthorized scanning may be illegal in many jurisdictions.

## 📜 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 👤 Author

- **Sumit** - *Initial work*

## 🙏 Acknowledgments

- Thanks to all contributors who have helped improve this tool
- Inspired by various network and system utilities in the Linux ecosystem

---

Made with ❤️ by the NotaScriptkiddie