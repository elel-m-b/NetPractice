# NetPractice Made Simple

<div align="center">
  <img src="./netpractice-image.png" alt="NetPractice Project" width="800"/>
</div>

## 📋 Table of Contents

- [Introduction](#introduction)
- [What is NetPractice?](#what-is-netpractice)
- [Project Overview](#project-overview)
- [Learning Objectives](#learning-objectives)
- [Key Concepts](#key-concepts)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Levels Overview](#levels-overview)
- [Tips and Tricks](#tips-and-tricks)
- [Common Mistakes](#common-mistakes)
- [Resources](#resources)
- [Contributing](#contributing)
- [Author](#author)

## 🌟 Introduction

**NetPractice Made Simple** is your comprehensive guide to mastering network concepts through the 42 School NetPractice project. This project demystifies TCP/IP addressing, subnetting, and routing in an interactive and practical way.

Whether you're a beginner looking to understand network fundamentals or someone preparing for the NetPractice evaluation, this repository provides clear explanations, practical examples, and step-by-step solutions.

## 🔗 What is NetPractice?

NetPractice is a 42 School project designed to teach students about:
- **IP addressing** and subnet masks
- **Network routing** and switch configuration
- **TCP/IP protocol** fundamentals
- **Subnetting** and network segmentation
- **Network troubleshooting** skills

The project consists of 10 levels, each presenting increasingly complex network scenarios that require proper configuration to achieve connectivity.

## 🎯 Project Overview

This project teaches practical networking through hands-on configuration exercises. You'll learn to:

- Configure IP addresses and subnet masks
- Set up routing tables
- Understand network switches and routers
- Implement proper network segmentation
- Troubleshoot connectivity issues

## 📚 Learning Objectives

By completing this project, you will understand:

- **Binary and decimal** IP address conversion
- **CIDR notation** and subnet calculations
- **Default gateways** and routing principles
- **Network Address Translation (NAT)**
- **Broadcast and network addresses**
- **Public vs Private** IP address ranges

## 🔑 Key Concepts

### IP Addresses
- **IPv4 format**: 32-bit addresses (e.g., 192.168.1.1)
- **Classes**: A, B, C networks
- **Private ranges**: 10.0.0.0/8, 172.16.0.0/12, 192.168.0.0/16

### Subnet Masks
- **Purpose**: Define network and host portions
- **CIDR notation**: /24, /16, /8
- **Calculation**: Determining available hosts

### Routing
- **Default gateway**: Path to external networks
- **Routing tables**: Network destination mapping
- **Next hop**: Router forwarding decisions

## 🚀 Installation

1. **Clone the repository**:
```bash
git clone https://github.com/elel-m-b/NetPractice.git
cd NetPractice
```

2. **Open in browser**:
```bash
# Navigate to the project directory and open index.html
open index.html
# or
firefox index.html
```

3. **Start practicing**:
   - Begin with Level 1
   - Progress through each level
   - Use the provided solutions as reference

## 💻 Usage

### Basic Workflow

1. **Analyze the network topology**
2. **Identify missing configurations**
3. **Calculate required IP ranges**
4. **Configure interfaces and routes**
5. **Test connectivity**
6. **Validate solution**

### Example Configuration

```
Interface A1: 192.168.1.1/24
Interface B1: 192.168.1.2/24
Route: 0.0.0.0/0 via 192.168.1.1
```

## 📁 Project Structure

```
NetPractice/
├── README.md
├── netpractice-image.png
├── levels/
│   ├── level1/
│   ├── level2/
│   ├── ...
│   └── level10/
├── solutions/
│   ├── level1-solution.md
│   ├── level2-solution.md
│   └── ...
├── docs/
│   ├── networking-basics.md
│   ├── subnetting-guide.md
│   └── troubleshooting.md
└── resources/
    ├── cheat-sheet.md
    └── useful-tools.md
```

## 🎮 Levels Overview

| Level | Difficulty | Focus Area | Key Concepts |
|-------|------------|------------|--------------|
| 1 | Beginner | Basic IP | Simple addressing |
| 2 | Beginner | Subnet masks | CIDR notation |
| 3 | Intermediate | Switches | Network segments |
| 4 | Intermediate | Routing | Default gateway |
| 5 | Intermediate | Complex routing | Multiple networks |
| 6 | Advanced | Internet connection | Public/Private IPs |
| 7 | Advanced | Complex topology | Multi-hop routing |
| 8 | Advanced | NAT configuration | Address translation |
| 9 | Expert | Full network | Complete setup |
| 10 | Expert | Challenge | All concepts |

## 💡 Tips and Tricks

### 🎯 Essential Tips

- **Start simple**: Begin with basic IP addressing
- **Use calculators**: Subnet calculators help verify your work
- **Draw diagrams**: Visualize the network topology
- **Check ranges**: Ensure IPs are in the same subnet
- **Test systematically**: Verify each connection step by step

### 📊 Subnet Calculation Quick Reference

```
/24 = 255.255.255.0   → 254 hosts
/25 = 255.255.255.128 → 126 hosts  
/26 = 255.255.255.192 → 62 hosts
/27 = 255.255.255.224 → 30 hosts
/28 = 255.255.255.240 → 14 hosts
/29 = 255.255.255.248 → 6 hosts
/30 = 255.255.255.252 → 2 hosts
```

## ⚠️ Common Mistakes

- **Wrong subnet calculations**
- **Forgetting default routes**
- **Using network/broadcast addresses**
- **Overlapping IP ranges**
- **Incorrect interface configurations**
- **Missing routing entries**

## 📖 Resources

### 🌐 Online Tools
- [Subnet Calculator](https://www.subnet-calculator.com/)
- [IP Calculator](https://jodies.de/ipcalc)
- [Network Tools](https://network-tools.com/)

### 📚 Learning Materials
- [Networking Fundamentals](https://www.cisco.com/c/en/us/support/docs/ip/routing-information-protocol-rip/13769-5.html)
- [Subnetting Tutorial](https://www.professormesser.com/network-plus/n10-007/subnetting/)
- [TCP/IP Guide](https://www.tcpipguide.com/)

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes:

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 👨‍💻 Author

**elel-m-b** - *1337-Rabat*

- GitHub: [@elel-m-b](https://github.com/elel-m-b)
- 42 Profile: elel-m-b
- Campus: 1337 Rabat

---

<div align="center">
  
**Made with ❤️ for the 42 community**

*Happy networking! 🌐*

</div>
