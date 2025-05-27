# CybersecurityPortfolio
Matt's Cybersecurity Portfolio

Penetration Testing Using Home Lab/Equipment:

1.) Planning and Reconnaissance

Passive Reconnaissance:

  -OSINT Information Gathering: (TODO:photos of: Add more precise output from scan and info on how to get the third party APIs up and running)
  
  -Using tools such as Kali Linux's spiderfoot, I gathered details on myself, the only occupant of the apartment. I found and accessed online social media profiles, gathered emails and usernames. Found relevant personal information such as past addresses and known associates.

  I've already set up most of the APIs to give spiderfoot more access to OSINT information, so this is how you start Spiderfoot in Kali:

  ![Step 1](https://github.com/mmangus1/CybersecurityPortfolio/blob/main/Screenshot_2025-05-27_10_38_42.png)

  Accessing the local website to initiate a scan:

  ![Step 2](https://github.com/mmangus1/CybersecurityPortfolio/blob/main/Screenshot_2025-05-27_10_40_13.png)

  Choosing options for the scan:

  ![Step 3](https://github.com/mmangus1/CybersecurityPortfolio/blob/main/Screenshot_2025-05-27_10_40_23.png)

  Output of the scan (Still Running):

  ![Step 4](https://github.com/mmangus1/CybersecurityPortfolio/blob/main/Screenshot_2025-05-27_10_41_29.png)

  A graph describing the output:

  ![Step 5](https://github.com/mmangus1/CybersecurityPortfolio/blob/main/Screenshot_2025-05-27_10_41_32.png)

Active Reconnaissance:

 -Can't do dumpster diving, lockpicking or B & E due to legal concerns.

2.) Scanning and Discovery

  -Discover Open Ports/Services
  use nmap to

3.) Vulnerability Assessment

  -Determine Network Vulnerabilies
  use nessus to

  -Use eyes and ears to determine possible opportunistic scenarios

4.) Explotation

  -Gain Access
  use aircrack-ng to gain Wi-Fi access, use social engineering toolkit, use metasploit, maybe a third party RAT (Remote Attached Trojan)

  -Use USB Drop Key or Bluejacking/Bluesnarfing

5.) Maintaining Access & Persistence Testing

  - Keep persistant access using a RAT, Terminal Session, Remote Desktop, VPN or other means to access the network.
  - Try to "jump" around the network to find more vulnerabilities or data.

6.) Final Analysis and Reporting

  - Report vulnerabilities, using CVE or other relevent codes.
  - Write a report regarding physical security flaws that are easily eploited to gain access

7.) Post-Testing Remediation & Continuous Monitoring

  - Implement fixes, hopefully permanent ones
  - Keep software updated
  - Lower number of programs
  - Possible survelliance increase (cameras, security guards)
  - Possible hardware improvements (physical doors, alternative locks, etc...)
  - Lower wireless device power (reduces risk of outside attacks)
  - other remediations
