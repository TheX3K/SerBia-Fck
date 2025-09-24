# X3KKING - Serbia Facebook Account Cracker

![X3KKING Banner](https://img.shields.io/badge/X3KKING-Serbia%20Cracker-orange)
![Python](https://img.shields.io/badge/Python-3.7%2B-blue)
![Platform](https://img.shields.io/badge/Platform-Linux%20%7C%20Termux-green)

<div align="center">

![X3KKING Logo](https://via.placeholder.com/400x100/ff6600/ffffff?text=╔━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━╗)
**⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢀⣠⣤⣤⣤⣤⣤⣄⣀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀**
**⠀⠀⠀⠀⠀⠀⠀⠀⣠⠞⠉⠉⠀⠀⠀⠀⠀⠉⠉⠙⠳⣄⠀⠀⠀⠀⠀⠀⠀**
**⠀⠀⠀⠀⠀⠀⣠⠞⠁⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠈⠳⣄⠀⠀⠀⠀⠀**
**⠀⠀⠀⠀⠀⣼⠃⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠈⢧⠀⠀⠀⠀**
**⠀⠀⠀⠀⢰⡇⠀⠀⣠⣶⣶⣶⣶⣶⣶⣶⣶⣦⣄⠀⠀⠀⠀⠀⠀⣿⠀⠀⠀**
**⠀⠀⠀⠀⢸⣇⣠⣾⡿⠛⠉⠙⠛⠛⠋⠉⠉⠛⢿⣷⣄⠀⠀⠀⠀⣿⠀⠀⠀**
**⠀⠀⠀⠀⠈⣿⣿⠋⠀⠀⠀⠀⣀⣀⠀⠀⠀⠀⠀⠙⣿⣷⣤⣤⣴⠏⠀⠀⠀**
**⠀⠀⠀⠀⠀⠘⢿⣷⣤⣤⣴⡿⠋⠉⠙⢷⣤⣤⣶⠾⠋⠉⠉⠉⠀⠀⠀⠀⠀**
**⠀⠀⠀⠀⠀⠀⠀⠈⠉⠉⠁⠀⠀⠀⠀⠀⠈⠉⠁⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀**
**⠀⠀⠀⠀⠀⠀⠀⠀⢀⣀⣀⣀⣀⣀⣀⣀⡀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀**
![X3KKING Logo](https://via.placeholder.com/400x100/ff6600/ffffff?text=╚━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━╝)

### **Advanced Serbian Facebook Account Security Testing Tool**

</div>

## 📖 Overview

X3KKING is a sophisticated security testing tool specifically designed for educational purposes and security research targeting Serbian Facebook accounts. This tool demonstrates various security vulnerabilities and helps security researchers understand common password patterns used in specific geographic regions.

## ⚠️ Disclaimer

**This tool is for educational and security research purposes only. Unauthorized use against accounts you do not own is illegal and unethical. The developers are not responsible for any misuse of this software.**

## 🚀 Features

- **🎯 Targeted Approach**: Specifically designed for Serbian Facebook accounts
- **📊 Multiple Year Ranges**: Supports accounts from 2009-2010, 2011-2012, and 2013-2014
- **🤖 Smart Password Generation**: Uses common Serbian password patterns
- **⚡ Multi-threaded**: Efficient parallel processing with configurable threads
- **🌍 Realistic User Agents**: Generates authentic Android device fingerprints
- **🛡️ Error Handling**: Robust retry mechanisms and error recovery
- **💾 Results Saving**: Automatically saves successful attempts
- **🎨 Beautiful Interface**: Color-coded terminal interface with real-time statistics

## 📋 Prerequisites

- Python 3.7+
- Linux or Termux environment
- Active internet connection
- Required Python packages

## 🔧 Installation

```bash
# Clone the repository
git clone https://github.com/TheX3K/SerBia-Fck.git
cd SerBia-Fck

# Install required dependencies
pip install requests faker urllib3

# Run the tool
python srb.py
```

## 🎯 Usage

1. **Start the tool**:
   ```bash
   python srb.py
   ```

2. **Select target year range**:
   - Option 1: 2009-2010 (Old Method)
   - Option 2: 2011-2012 (Mid Method)  
   - Option 3: 2013-2014 (New Method)

3. **Set the target limit**:
   - Enter the number of accounts to test (recommended: 1000-5000)

4. **Monitor progress**:
   - Real-time statistics showing OK/CP results
   - Progress bar and completion percentage

## 🔍 Technical Details

### Password Generation Algorithm
The tool generates passwords based on common Serbian patterns:
- Name combinations with numbers
- Common Serbian words and cities
- Sequential numbers and dates
- Regional-specific keywords

### Account Generation
- Uses Serbian names and surnames database
- Serbian email providers (sbb.rs, ptt.rs)
- Realistic Serbian phone number formats
- Year-specific UID generation

### Security Features
- Randomized delays between requests
- Retry mechanisms for failed requests
- Session management with proper headers
- SSL verification bypass for testing

## 📊 Output

Results are saved in `~/X3KKING/` directory:
- `X3KKING-SERBIA-OK.txt`: Successful attempts
- Format: `UID|Password|Name|Email`

## 🛡️ Safety Recommendations

- Use only in controlled environments
- Always have proper authorization
- Use VPN for testing
- Respect rate limits
- Follow ethical hacking guidelines

## 🤝 Contributing

We welcome contributions from security researchers:
- Report vulnerabilities responsibly
- Suggest improvements to the algorithm
- Enhance the user interface
- Add new features while maintaining ethics

## 📝 License

This project is for educational purposes only. Users are responsible for complying with local laws and regulations.

## ⭐ Acknowledgments

- Security research community
- Ethical hacking principles
- Open-source tools that inspired this project

---

<div align="center">

**🔒 Use Responsibly • 🎯 Stay Ethical • 🚀 Keep Learning**

*For educational and security research purposes only*

![Footer](https://img.shields.io/badge/Made%20with-❤️-orange?style=for-the-badge)

</div>

## 📞 Contact

For educational inquiries and security research discussions:
- GitHub Issues: [TheX3K/SerBia-Fck](https://github.com/TheX3K/SerBia-Fck)
