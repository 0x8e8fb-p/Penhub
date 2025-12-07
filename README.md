# PenHub - Pentesting Commands & Toolkit

![PenHub - Pentesting Toolkit](https://img.shields.io/badge/PenHub-Pentesting_Toolkit-red)
![License: MIT](https://img.shields.io/badge/License-MIT-blue)
![Platform: Web](https://img.shields.io/badge/Platform-Web-brightgreen)

PenHub is a comprehensive, web-based pentesting toolkit designed for penetration testers, security researchers, and CTF players. This all-in-one interface provides quick access to commonly used commands, post-exploitation techniques, payload generation, and network pivoting tools - all from a single, intuitive dashboard.
🌟 Features
1. Commands Generator

    Live Command Templates: Dynamic generation of pentesting commands with customizable parameters

    Tool Coverage:

        Nmap scanning techniques

        Directory busting (Gobuster, Feroxbuster)

        Vulnerability scanning (Nuclei, Nikto)

        Password attacks (Hydra, John, Hashcat)

        SQL injection (SQLMap)

        Reverse shells (multiple languages)

        File transfer methods

    Smart Parameter System: Fill once, update all commands automatically

    One-click Copy: Copy commands directly to clipboard

2. Post-Exploitation Cheatsheet

    Dual-Platform Coverage: Extensive Linux & Windows post-exploitation techniques

    Systematic Enumeration: Step-by-step system reconnaissance

    Privilege Escalation: SUID/SGID, sudo exploits, kernel vulnerabilities, Windows privilege abuses

    Credential Hunting: Password extraction, hash dumping, credential discovery

    File Transfer Methods: Multiple upload/download techniques for both platforms

    Persistence Techniques: Maintaining access after compromise

    Search Functionality: Quick search across all commands and techniques

3. Image Payload Generator

    Stealthy Payloads: Embed malicious code within image files

    Multiple Payload Types:

        Reverse shells (PHP, Python, Bash)

        Command execution

        Web shells

        Custom payloads

    File Format Support: JPG, PNG, GIF, BMP

    Technique Documentation: File extension bypass, magic bytes, polyglot files

4. Port Forwarding & Pivoting Toolkit

    Multi-Tool Support: Ligolo-ng, Chisel, SSH tunneling, Socat

    Visual Configuration: Interactive parameter setup

    Step-by-Step Guides: Complete setup instructions for each tool

    Network Diagrams: Visual representation of pivoting flows

    Real-time Command Generation: Commands update as you configure parameters

🚀 Quick Start
Option 1: Local Deployment
bash

# Clone the repository
git clone https://github.com/yourusername/penhub.git

# Navigate to directory
cd penhub

# Open in browser (any modern web browser)
# Simply open index.html in your preferred browser

Option 2: Direct File Access

Since PenHub is built with pure HTML, CSS, and JavaScript, you can:

    Download the ZIP file and extract

    Open index.html directly in any modern web browser

    No server or dependencies required!

Option 3: Hosted Version

Visit https://0x8e8fb.github.io/penhub for the live version (if hosted).
🛠️ Tool Structure
text

penhub/
│
├── index.html              # Main application interface
├── notes.html             # Private notes system
├── payload.html           # Image payload generator
├── pivot.html            # Port forwarding & pivoting toolkit
│
├── (All functionality is contained in single HTML files)
│
└── README.md              # This documentation

📋 Usage Guide
Commands Page

    Configure Parameters: Enter target IP, ports, usernames, etc. in the sidebar

    Browse Categories: Expand different tool sections (Nmap, Gobuster, Hydra, etc.)

    Copy Commands: Click the "copy" button on any command to copy to clipboard

    Customize Tools: Adjust advanced parameters for tools like Nuclei, SQLMap, Feroxbuster

Post-Exploitation Cheatsheet

    Search Function: Use the search bar to find specific techniques

    Quick Links: Jump to common sections (PrivEsc, Enum, File Transfer)

    Platform Toggle: Switch between Linux and Windows techniques

    Expand/Collapse: Toggle sections for focused reading

Image Payload Generator

    Select Payload Type: Choose reverse shell, command execution, or custom

    Configure Parameters: Set LHOST, LPORT, or custom commands

    Generate Payload: Create malicious image with embedded PHP code

    Download: Get the malicious image or standalone PHP payload

Pivoting Toolkit

    Configure Network: Set attacker IP, target IP, ports

    Choose Tool: Select between Ligolo-ng, Chisel, SSH, or Socat

    Follow Steps: Use the step-by-step guides for each tool

    Copy Commands: Get ready-to-use commands for your scenario

🎯 Target Audience

    Penetration Testers: Quick reference for common commands during engagements

    CTF Players: Fast access to enumeration and exploitation techniques

    Security Researchers: Template for building custom payloads and pivots

    OSCP/PNPT Students: Comprehensive cheatsheet for exam preparation

    Red Teamers: All-in-one toolkit for operational workflows

🔒 Legal & Ethical Use

IMPORTANT: PenHub is designed for:

    Authorized security assessments

    CTF competitions and hacking challenges

    Educational purposes in controlled environments

    Security research with proper authorization

DO NOT USE for:

    Unauthorized penetration testing

    Illegal hacking activities

    Malicious attacks against systems you don't own

    Violating laws or terms of service

The author assumes no responsibility for misuse of this tool. Always obtain proper authorization before testing any system.
🧩 Integration with Existing Workflows
With Your Kali/Parrot OS
bash

# Bookmark PenHub in your browser for quick access
# Use alongside tools like Burp Suite, Metasploit, CrackMapExec
# Reference during engagements without leaving your workflow

With Note-taking Tools

    Export commands to tools like CherryTree, Obsidian, or OneNote

    Use as a quick reference while taking screenshots and notes

    Template for standardized engagement reporting

📚 Learning Resources
For Beginners

    Start with the Commands Generator to learn basic tool syntax

    Study the Post-Exploitation Cheatsheet for methodology

    Practice with the Image Payload Generator in lab environments

    Understand Pivoting concepts before attempting complex networks

For Advanced Users

    Customize the tool by modifying the HTML/JS for your workflow

    Add your own command templates and techniques

    Integrate with your existing toolset and scripts

    Use as a teaching tool for junior team members

🐛 Common Issues & Troubleshooting
JavaScript Not Working

    Ensure JavaScript is enabled in your browser

    Check browser console for errors (F12 → Console)

    Try a different browser (Chrome/Firefox recommended)

Commands Not Updating

    Refresh the page to reset all parameters

    Check that all required fields are filled

    Ensure no ad-blockers are interfering with scripts

Layout Issues

    Browser zoom should be at 100% for optimal display

    Use recommended browsers: Chrome 80+, Firefox 75+, Edge 80+

    Mobile devices have limited support (use desktop for full features)

🔄 Updates & Maintenance
Version History

    v1.0 (Current): Initial release with core functionality

    Planned: More tools, export features, dark/light mode toggle

Contributing

Contributions are welcome! Please:

    Fork the repository

    Create a feature branch

    Submit a pull request with clear description

    Follow the existing code style

Reporting Issues

Use GitHub Issues to report:

    Bugs or unexpected behavior

    Missing tools or techniques

    Security vulnerabilities (responsibly)

    Feature requests

📞 Support & Community

    GitHub Issues: For technical problems and feature requests

    Buy Me a Coffee: Support development at buymeacoffee.com/0x8e8fb

    Twitter: Follow @0x8e8fb for updates

🙏 Acknowledgments

    Inspired by various pentesting cheatsheets and tools

    Community contributions from security researchers worldwide

    Special thanks to tool developers (Nmap, Gobuster, Nuclei, etc.)

    OSCP/PNPT community for methodology and techniques

📄 License

MIT License - See LICENSE file for details.

Disclaimer: This tool is for educational and authorized testing purposes only. The author is not responsible for any misuse or damage caused by this tool. Always follow ethical guidelines and obtain proper authorization before penetration testing.

Built with ❤️ by 0x8e8fb for the security community