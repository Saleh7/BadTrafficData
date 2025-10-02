# BadTrafficData

This repository contains data extracted from server logs to detect and block malicious or suspicious traffic. The data includes:

- **bad_requests.txt**: A list of URLs that have been flagged for suspicious activity.
- **blacklisted_ips.txt**: A list of IP addresses that have been identified for malicious behavior.
- **suspicious_user_agents_list.txt**: A list of user agents associated with suspicious traffic patterns.


This project’s pretty much just for me and my servers. If anyone else ends up using it, well… that’s totally accidental! 😄

## Usage

These files can be used to update firewall rules, monitor traffic patterns, or analyze potential security threats. You can integrate the data into your security tools or databases to block suspicious traffic.

### Databases Totals
| Database Name       | Total Entries |
|---------------------|---------------|
| `bad_requests`      | 1147154         |
| `blacklisted_ips`      | 25260         |
| `suspicious_user_agents_list`      | 6756         |

### Last Update Reports
Report generated on: 2025-10-02 17:58:34

## License
MIT
