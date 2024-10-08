# Cybersecurity Tools and Resources

This repository contains a curated collection of tools, scripts, and cheat sheets designed for penetration testing, exploit development, and security research. It includes both offensive and defensive tools, Proof-of-Concepts (POCs) for various vulnerabilities, and resources to aid security professionals in their work.

## Table of Contents

1. [Active Directory](#active-directory)
2. [Exploits](#exploits)
3. [Pentesting Tools](#pentesting-tools)
4. [Cheat Sheets](#cheat-sheets)
5. [Web and Cloud Recon](#web-and-cloud-recon)
6. [Hash Cracking](#hash-cracking)
7. [Miscellaneous](#miscellaneous)
8. [Files and Tools](#files-and-tools)
9. [Contributing](#contributing)
10. [License](#license)

## Active Directory

- [**ADModule**](https://github.com/hashtaginfosec/ADModule) - PowerShell module for Active Directory exploitation.
- [**NTLM Relaying**](https://byt3bl33d3r.github.io/practical-guide-to-ntlm-relaying-in-2017-aka-getting-a-foothold-in-under-5-minutes.html) - Guide on NTLM relaying techniques.
- [**Active Directory Attack**](https://github.com/swisskyrepo/PayloadsAllTheThings/blob/master/Methodology%20and%20Resources/Active%20Directory%20Attack.md#pass-the-ticket-golden-tickets) - Methods and tactics for attacking Active Directory.
- [**Active Directory Security**](https://adsecurity.org/) - Resource for AD attack and defense strategies.
- [**BloodHound.py**](https://github.com/fox-it/BloodHound.py) - Python tool for analyzing Active Directory trust relationships.
- [**BloodHound Custom Queries**](https://github.com/hausec/Bloodhound-Custom-Queries/blob/master/customqueries.json) - Custom queries for BloodHound.
- [**Active Directory Exploitation Cheat Sheet**](https://github.com/S1ckB0y1337/Active-Directory-Exploitation-Cheat-Sheet) - Cheat sheet for AD enumeration and attacks.
- [**AMSI Bypass (PowerShell)**](https://github.com/S3cur3Th1sSh1t/Amsi-Bypass-Powershell) - Techniques for bypassing AMSI using PowerShell.

## Exploits

- [**SMB Ghost POC (CVE-2020-0796)**](https://github.com/joxeankoret/CVE-2020-7494) - POC for SMB Ghost (CVE-2020-0796).
- [**SAMBA CVE-2017-7494**](https://github.com/joxeankoret/CVE-2017-7494) - Remote code execution exploit for SAMBA CVE-2017-7494.
- [**Evil-WINRM**](https://github.com/Hackplayers/evil-winrm) - PowerShell remoting framework for pentesting.
- [**MitM6**](https://github.com/dirkjanm/mitm6) - Tool for exploiting IPv6 attacks within IPv4 networks.
- [**Maximizing BloodHound**](https://github.com/knavesec/Max) - Guide for advanced BloodHound features.

## Pentesting Tools

- [**PayloadsAllTheThings**](https://github.com/swisskyrepo/PayloadsAllTheThings) - Payloads for various vulnerabilities.
- [**MANSPIDER**](https://github.com/blacklanternsecurity/MANSPIDER) - SMB crawler for finding sensitive files.
- [**CrackMapExec**](https://wiki.porchetta.industries/) - Tool for pentesting Windows/Active Directory.
- [**Big List of Naughty Strings**](https://github.com/minimaxir/big-list-of-naughty-strings) - Test strings for input validation.
- [**PHP Reverse Shell**](https://github.com/pentestmonkey/php-reverse-shell) - PHP script for reverse shells.

## Cheat Sheets

- [**OSCP Cheat Sheet**](https://github.com/pentestmonkey/php-reverse-shell) - Cheat sheet for OSCP certification.
- [**Bug Bounty Cheat Sheet**](https://bugtraq.securityfocus.com/archive) - Guide for bug bounty hunters.
- [**Active Directory Cheat Sheet**](https://github.com/drak3hft7/Cheat-Sheet---Active-Directory) - AD enumeration and exploitation commands.

## Web and Cloud Recon

- [**Subfinder**](https://github.com/projectdiscovery/subfinder) - Subdomain enumeration tool.
- [**crt.sh**](https://crt.sh/) - Certificate Transparency logs for finding subdomains.

## Hash Cracking

- [**Hashcat Example Hashes**](https://hashcat.net/wiki/doku.php?id=example_hashes) - Example hashes supported by Hashcat.
- [**CrackStation**](https://crackstation.net/) - Tool for cracking hashes with large dictionaries.

## Miscellaneous

- [**Nmap**](https://github.com/nmap/nmap) - Network scanner and vulnerability detection tool.
- [**Email Bomber**](http://thinkvaughn.com/tools/email-bomber.html) - Tool for bulk email testing.
- [**Exploit DB**](https://www.exploit-db.com/) - Archive of public exploits and vulnerabilities.

## Files and Tools

- **Accesschk.zip**: Utility for viewing effective permissions.
- **Active-Directory - Cheat-Sheet**: Commands and tips for Active Directory.
- **CVE-2020-0796-POC.zip**: POC for SMB Ghost vulnerability.
- **JuicyPotato.exe**: Privilege escalation tool.
- **LICENSE**: Repository license file.
- **Nishang**: Collection of PowerShell scripts and payloads.
- **OSCP Cheat Sheet**: Tips for OSCP exam.
- **Pentestmonkey**: Tools and scripts for penetration testing.
- **RCE SAMBA CVE-2017-7494**: Remote code execution exploit for SAMBA.
- **Rubeus.exe**: Tool for interacting with Kerberos tickets.
- **Seatbelt.exe**: Post-exploitation enumeration tool.
- **VC_redist.x64.exe**: Microsoft Visual C++ Redistributable package.
- **amsibypass.txt**: AMSI bypass techniques.
- **bugbounty-onliners.md**: Bug bounty tips and tricks.
- **evil-winrm**: PowerShell-based WinRM client.
- **kaliupdatescript**: Script for updating Kali Linux.
- **python_rev_shell.py**: Python reverse shell script.
- **test.php**: PHP script for web application testing.
- **tools.sh**: Bash script with useful commands.
- **windows_rev_shell_working.php**: PHP script for reverse shell on Windows.

## Contributing

Contributions are welcome! If you have additional tools, scripts, or resources to add, please submit a pull request.

## License

This repository is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
