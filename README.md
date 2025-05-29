# Internship-Task-3

22/tcp	High	Deprecated SSH-1 protocol
80/tcp	High	BASE input validation vulnerabilities (SQLi, XSS, LFI)
22/tcp	Medium	Weak SSH encryption algorithms
80/tcp	Medium	HTTP TRACE method enabled
80/tcp	Medium	phpMyAdmin XSS vulnerability
80/tcp	Medium	Apache httpOnly cookie exposure
22/tcp	Low	Weak SSH MAC algorithms

Critical Vulnerabilities - 


SSH-1 Protocol Enabled – severe encryption flaws enabling session hijack.
BASE Input Validation Flaws – exploitable via SQL injection, XSS, LFI.
phpMyAdmin XSS (Old Version) – allows HTML/script injection; high phishing risk.

Mitigations that can use to counter the vulnerabilities - 


    Disable SSH-1 protocol
    Remove weak SSH ciphers and MACs
    Upgrade phpMyAdmin to the latest version
    Upgrade Apache HTTP Server to version 2.2.22 or later
    Disable HTTP TRACE and TRACK methods
    Schedule regular vulnerability scans
    Monitor server logs for suspicious activity
    Use firewalls to restrict access (e.g., UFW, iptables)
    Restrict SSH access to trusted IPs
    Use VPN for remote administration
    Apply the principle of least privilege for user accounts
    Disable unused services and ports
