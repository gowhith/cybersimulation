# About Interactive Cyber Attack Simulation Website

An interactive web application that demonstrates a complete cyber attack lifecycle, from initial reconnaissance to detection and analysis. This project serves as both an educational tool and a practical demonstration of modern security tools and techniques.

## 🌟 Features

### 1. Interactive Overview
- **Scenario Walkthrough**: Step-by-step demonstration of a cyber attack scenario
- **Core Toolchain**: Visual representation of essential security tools
- **Role-based Visualization**: Clear separation of Attacker, Victim, and Analyst perspectives

### 2. Tool Deep Dive
- **Comprehensive Tool Information**: Detailed documentation for each security tool
- **Interactive Bubbles**: Modern, space-efficient visualization of tools
- **Use Cases & Conditions**: Practical applications and best-use scenarios
- **Direct Documentation Links**: Quick access to official tool documentation

### 3. Attack & Defense Playbook
- **Step-by-Step Timeline**: Chronological progression of the attack
- **Interactive Navigation**: Easy movement between attack stages
- **Command Demonstrations**: Real-world command examples with outputs
- **Role-based Context**: Clear indication of which actor performs each action

### 4. Detection Dashboard
- **Real-time Event Visualization**: Interactive chart of Sysmon events
- **Log Analysis**: Simulated SIEM (Splunk) interface
- **Event Correlation**: Detailed view of security events
- **Interactive Filtering**: Click-to-filter functionality for event types

## 🛠️ Tools Covered

1. **Nmap**
   - Role: Reconnaissance
   - Use: Network discovery and security auditing
   - Documentation: [Nmap Official Docs](https://nmap.org/docs.html)

2. **MSFvenom**
   - Role: Weaponization
   - Use: Payload generation for penetration testing
   - Documentation: [MSFvenom Docs](https://docs.rapid7.com/metasploit/msfvenom/)

3. **Python HTTP Server**
   - Role: Delivery
   - Use: Simple file hosting for payload delivery
   - Documentation: [Python HTTP Server Docs](https://docs.python.org/3/library/http.server.html)

4. **Metasploit**
   - Role: Command & Control
   - Use: Exploitation and post-exploitation framework
   - Documentation: [Metasploit Docs](https://docs.rapid7.com/metasploit/)

5. **Sysmon**
   - Role: Detection
   - Use: Advanced Windows system monitoring
   - Documentation: [Sysmon Docs](https://learn.microsoft.com/en-us/sysinternals/downloads/sysmon)

6. **Splunk**
   - Role: Analysis
   - Use: SIEM for log analysis and correlation
   - Documentation: [Splunk Docs](https://docs.splunk.com/Documentation/Splunk)

7. **Netstat**
   - Role: Verification
   - Use: Network connection monitoring
   - Documentation: [Netstat Docs](https://learn.microsoft.com/en-us/windows-server/administration/windows-commands/netstat)

## 🚀 Getting Started

### Prerequisites
- Python 3.x
- Modern web browser (Chrome, Firefox, Edge recommended)

### Running Locally
1. Clone this repository
2. Navigate to the project directory
3. Start a local server:
   ```bash
   python -m http.server 8000
   ```
4. Open your browser and visit: `http://localhost:8000`

## 🎯 Use Cases

This website is particularly useful for:
- Security professionals learning about attack detection
- Students studying cybersecurity
- Security teams demonstrating attack patterns
- Recruiters evaluating security knowledge
- Anyone interested in understanding cyber attack lifecycles

## 🔒 Security Note

This website is for educational purposes only. All demonstrations are simulated in controlled environments. The tools and techniques shown should only be used in authorized security testing scenarios.

## 🎨 Technical Implementation

- Built with vanilla JavaScript, HTML5, and CSS3
- Uses Tailwind CSS for styling
- Chart.js for data visualization
- Responsive design for all device sizes
- No external dependencies except for CDN-hosted libraries

## 📝 License

This project is open source and available under the MIT License.

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📧 Contact

For questions or suggestions, please open an issue in the repository.

---

*Note: This is a demonstration project. Always practice security testing in controlled, authorized environments.*
