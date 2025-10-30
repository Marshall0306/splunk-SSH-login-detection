# SSH Brute-Force Detection with Splunk

This project demonstrates real-time SSH brute-force attack detection using Splunk Enterprise and Kali Linux.

## 🧩 Components
- Kali Linux (attacker)
- Splunk (SIEM)
- Syslog over UDP 514

## ⚙️ Setup Steps
1. Configure rsyslog on Kali to forward logs to Splunk.
2. Add a UDP 514 input in Splunk.
3. Generate fake SSH login attempts.
4. Build Splunk dashboards to visualize failed SSH logins.

## 📊 Dashboard Example
- Failed SSH logins by IP
- Attempts over time
- Top attacking IPs

## 🔒 Skills Demonstrated
- SIEM log ingestion
- Syslog configuration
- SOC analysis
- Splunk dashboarding
