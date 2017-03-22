# CryptoSIEM

Small tool to detect requests to domains infected by CryptoLocker. 

Start the program as a daemon

Functions:

- Connect to ramsowaretracker and download malicious sites.
- Create snort - suricata rules with infected domains.
- Add the rules.
- Sends such alerts to syslog (normally SIEM), to later generate alerts and reports.
