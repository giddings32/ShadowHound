![Logo](./ShadowHound.jpg)

# ShadowHound: A CLI-Based Active Directory Enumeration and Analysis Tool

ShadowHound is a lightweight Bash script designed to parse and analyze Active Directory data extracted from BloodHound JSON files. It provides an intuitive, step-by-step CLI interface to identify users, computers, groups, and their relationships, helping penetration testers and system administrators find potential attack paths and misconfigurations.

## 🎯 Key Features
- **Interactive CLI Interface**  
  Step-by-step options for parsing and analyzing user, computer, and group data.
  
- **User Data Analysis**  
  Extract details about enabled/disabled users, Kerberoastable accounts, last login times, and more.

- **Computer Data Analysis**  
  Identify operating systems, check for unsupported OS versions, and analyze last login data.

- **Group Data Analysis**  
  Investigate permissions, DCSync rights, and memberships.

- **Colorized Output**  
  Results are displayed in an easy-to-read, colorized format for quick insights.

- **No Dependencies Beyond Bash & jq**  
  The script relies only on the `jq` utility for JSON parsing.

## 🚀 Getting Started
To use ShadowHound, follow these steps:

### Prerequisites
- Bash (Linux or macOS) or a compatible shell on Windows (e.g., Git Bash).
- The `jq` utility for parsing JSON files:
  ```bash
  sudo apt install jq  # Ubuntu/Debian
  brew install jq      # macOS
  ```

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/giddings32/ShadowHound.git
   cd ShadowHound
   ```
2. Make the script executable:
   ```bash
   chmod +x shadowhound.sh
   ```

3. Place your BloodHound JSON files in the same directory as the script.

### Usage
Run the script with:
```bash
./shadowhound.sh
```

### Script Walkthrough
- Select the category of data to analyze:
  1. Users
  2. Computers
  3. Groups
- Follow the interactive prompts to perform specific analyses, such as:
  - Listing enabled users.
  - Finding computers running unsupported operating systems.
  - Investigating group memberships and permissions.


![image](https://user-images.githubusercontent.com/75488156/233803442-85148459-6a3c-41f9-ac49-ebaa191b5772.png)

