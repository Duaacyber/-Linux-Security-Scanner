Linux Security Scanner
A bash-based security scanner for Linux systems.

Features
User account auditing
Password policy checks
SSH configuration analysis
Firewall status detection
Open port scanning
SUID/SGID file detection
File permission auditing
Service monitoring
Update checking
Logging verification
Kernel security checks
Usage
# Make executablechmod +x security_scanner.sh# Run full scan (recommended with sudo)sudo ./security_scanner.sh# Check specific areassudo ./security_scanner.sh --sshsudo ./security_scanner.sh --networksudo ./security_scanner.sh --userssudo ./security_scanner.sh --files# Custom output filesudo ./security_scanner.sh -o my_report.txt# Help./security_scanner.sh --help
