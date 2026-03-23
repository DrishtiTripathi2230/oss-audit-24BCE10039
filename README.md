# Open Source Audit Project

###Name: Drishti Tripathi
###Roll Number: [24BCE10039]
###Software Chosen: VLC Media Player  

## Project Description
This project is an audit of the open-source software VLC Media Player. It covers its origin, license, Linux usage, ecosystem, and comparison with proprietary software.

## Scripts

### Script 1: System Identity Report
Displays system details like kernel version, user, uptime, and date.

### Script 2: FOSS Package Inspector
Checks if VLC is installed and shows version and description.

### Script 3: Disk and Permission Auditor
Displays disk usage and permissions of important directories.

### Script 4: Log File Analyzer
Reads a log file and counts occurrences of a keyword like "error".

### Script 5: Open Source Manifesto Generator
Takes user input and generates a personalized manifesto saved to a file.

## How to Run Scripts

Step 1: Open terminal in project folder

Step 2: Give execution permission
chmod +x script1.sh script2.sh script3.sh script4.sh script5.sh

Step 3: Run scripts

./script1.sh  
./script2.sh  
./script3.sh  
./script4.sh /var/log/syslog error  
./script5.sh  

## Requirements / Dependencies

- Linux environment (Ubuntu via WSL)
- VLC Media Player installed
- Basic Linux commands (dpkg, grep, awk, etc.)
