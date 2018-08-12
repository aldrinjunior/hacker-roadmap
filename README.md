~~~
    __  __           __                                        __                    
   / / / /___ ______/ /_____  _____      _________  ____ _____/ /___ ___  ____ _____ 
  / /_/ / __ `/ ___/ //_/ _ \/ ___/_____/ ___/ __ \/ __ `/ __  / __ `__ \/ __ `/ __ \
 / __  / /_/ / /__/ ,< /  __/ /  /_____/ /  / /_/ / /_/ / /_/ / / / / / / /_/ / /_/ /
/_/ /_/\__,_/\___/_/|_|\___/_/        /_/   \____/\__,_/\__,_/_/ /_/ /_/\__,_/ .___/ 
                                                                            /_/      
~~~


![GitHub issues](https://img.shields.io/github/issues/Sundowndev/hacker-roadmap.svg)
![stars](https://img.shields.io/github/stars/SundownDEV/hacker-roadmap.svg)
![forks](https://img.shields.io/github/forks/SundownDEV/hacker-roadmap.svg)
![license](https://img.shields.io/badge/license-MIT-brightgreen.svg)

This repository is a guide for amateurs pen testers and a summary of hacking tools, resources and references to practice ethical hacking, pen testing and web security. Most of these tools are UNIX compatible and MIT licensed. *Note that Linux is the best operating system to practice ethical hacking.*

# Summary

* [Introduction](#introduction)
    * [What is penetration testing ?](#what-is-penetration-testing-)
    * [Want to become a penetration tester ?](#want-to-become-a-penetration-tester-)
    * [Some vocabulary](#some-vocabulary)
    * [Languages](#languages)
    * [Content Management Systems](#content-management-systems)
    * [Basic steps of pen testing](#basic-steps-of-pen-testing)
* [Tools by category](#tools-by-category)
    * [Information Gathering](#male_detective-information-gathering)
    * [Password Attacks](#lock-password-attacks)
    * [Wireless Testing](#globe_with_meridians-wireless-testing)
    * [Exploitation Tools](#wrench-exploitation-tools)
    * [Sniffing & Spoofing](#busts_in_silhouette-sniffing--spoofing)
    * [Web Hacking](#rocket-web-hacking)
    * [Post Exploitation](#tada-post-exploitation)
    * [Frameworks](#package-frameworks)
* [Additional resources](#additional-resources)
    * [Books / Manuals](#books--manuals)
    * [Discussions](#discussions)
    * [Security Advisories](#security-advisories)
    * [Challenges](#challenges)
* [License](#license)

# Introduction

## What is penetration testing ?

Penetration testing is a type of security testing that is used to test the insecurity of an application. It is conducted to find the security risk which might be present in the system.

If a system is not secured, then any attacker can disrupt or take authorized access to that system. Security risk is normally an accidental error that occurs while developing and implementing the software. For example, configuration errors, design errors, and software bugs, etc. [Learn more](https://www.tutorialspoint.com/penetration_testing/penetration_testing_quick_guide.htm)

## Want to become a penetration tester ?

Know about risks on the internet and how they can be prevented is very useful. Especially as a developer. Web hacking and penetration testing is the v2.0 of self-defense! But does know about tools and how to use them is really all you need to become a pen tester? Surely not. A real penetration tester must be able to proceed rigorously and detect the weaknesses of an application. He must be able to identify the technology behind and test every single door that might be open to hackers.

This repository aim first to establish a reflection method on penetration testing and explain how to proceed to secure an application. And secondly, to regroup all kind of tools or resources pen testers need. **Be sure to know basics of programming languages and Internet security before learning pen testing.**

## Some vocabulary

**Black/grey/white hat hacker** : Someone who uses bugs or exploits to break into systems or applications. The goal and the method differs depending if he's a black, grey or white hat hacker. A black hat is just someone malicious that does not wait permission to break into a system or application. A white hat is *usually* a security researcher who practice ethical hacking. A grey hat is just in the middle of these two kind of hackers, he might want to be malicious if it can be benefit (data breach, money, whistleblowing ...).

**Penetration tester** : Most likely a white hacker who test applications and systems to secure them or find vulnerabilities.

**Security researcher** : Someone who practice pen testing and browse the web everyday to find phishing/fake websites, infected servers, bugs or vulnerabilities. He can work for a company so he's responsible for the security of systems.

### Difference between hacking and ethical hacking

A black hat is practicing penetration testing, but unlike a white hat, this is not ethical hacking. Ethical hacking is about find vulnerabilities and improve the security of a system. An ethical hacker is the ultimate security professional. Ethical hackers know how to find and exploit vulnerabilities and weaknesses in various systems, just like a malicious hacker (a black hat hacker). In fact, they both use the same skills; however, an ethical hacker uses those skills in a legitimate, lawful manner to try to find vulnerabilities and fix them before the bad guys can get there and try to break in. An ethical hacker is basically a white hat hacker.

## Languages

- Python
- Ruby
- C / C++ / C#
- Perl
- Go
- Java

## Content Management Systems

- Wordpress
- Joomla
- Drupal
- SPIP

## Basic steps of pen testing

<p align="center">
    <img src="https://www.tutorialspoint.com/penetration_testing/images/penetration_testing_method.jpg">
</p>

## Tools by category

#### :male_detective: Information Gathering

Information Gathering tools allows you to collect host metadata about services and users. Check informations about a domain, IP address, phone number or an email address.

| Tool        | Language           | Support  | Description    |
| ----------- |-------------------------|----------|----------------|
| [Th3inspector](https://github.com/Moham3dRiahi/Th3inspector)      | **Perl** | `Linux/Windows/macOS` | All in one tool for Information Gathering written in Perl. |
| [Crips](https://github.com/Manisso/Crips)      | **Python** | `Linux/Windows/macOS` | IP Tools To quickly get information about IP Address's, Web Pages and DNS records. |
| [theHarvester](https://github.com/laramies/theHarvester)      | **Python** | `Linux/Windows/macOS` | E-mails, subdomains and names Harvester. |
| [Scanless](https://github.com/vesche/scanless)      | **Python** | `Linux/Windows/macOS` | Online port scan scraper. |
| [CTFR](https://github.com/UnaPibaGeek/ctfr)      | **Python** | `Linux/Windows/macOS` | Abusing Certificate Transparency logs for getting HTTPS websites subdomains. |
| [Sn1per](https://github.com/1N3/Sn1per)      | **bash** | `Linux/macOS` | Automated Pentest Recon Scanner. |
| [ReconDog](https://github.com/s0md3v/ReconDog)      | **Python** | `Linux/Windows/macOS` | Recon Dog is an all in one tool for all your basic information gathering needs. |
| [RED Hawk](https://github.com/Tuhinshubhra/RED_HAWK)      | **PHP** | `Linux/Windows/macOS` | All in one tool for Information Gathering, Vulnerability Scanning and Crawling. A must have tool for all penetration testers. |
| [Infoga](https://github.com/m4ll0k/Infoga)      | **Python** | `Linux/Windows/macOS` | Email Information Gathering. |
| [KnockMail](https://github.com/4w4k3/KnockMail)      | **Python** | `Linux/Windows/macOS` | Check if email address exists. |
| [Photon](https://github.com/s0md3v/Photon)      | **Python** | `Linux/Windows/macOS` | Crawler which is incredibly fast and extracts urls, emails, files, website accounts and much more. |

#### :lock: Password Attacks

Crack passwords and create wordlists.

| Tool        | Language           | Support  | Description    |
| ----------- |-------------------------|----------|----------------|
| [John the Ripper](https://github.com/magnumripper/JohnTheRipper)      | **C** | `Linux/Windows/macOS` | John the Ripper is a fast password cracker. |
| [hashcat](https://github.com/hashcat/hashcat)      | **C** | `Linux/Windows/macOS` | World's fastest and most advanced password recovery utility. |
| [Hydra](https://github.com/vanhauser-thc/thc-hydra)      | **C** | `Linux/Windows/macOS` | Parallelized login cracker which supports numerous protocols to attack.￼ |
| [ophcrack](https://gitlab.com/objectifsecurite/ophcrack)      | **C++** | `Linux/Windows/macOS` | Windows password cracker based on rainbow tables. |
| [Ncrack](https://github.com/nmap/ncrack)      | **C** | `Linux/Windows/macOS` | High-speed network authentication cracking tool. |
| [WGen](https://github.com/agusmakmun/Python-Wordlist-Generator)      | **Python** | `Linux/Windows/macOS` | Create awesome wordlists with Python. |

###### :memo: Wordlists

| Tool        | Description    |
| ----------- |----------------|
| [Probable Worlist](https://github.com/berzerk0/Probable-Wordlists)      | Wordlists sorted by probability originally created for password generation and testing. |

#### :globe_with_meridians: Wireless Testing

Used for intrusion detection and wifi attacks.

| Tool        | Language           | Support  | Description    |
| ----------- |-------------------------|----------|----------------|
| [Aircrack](https://github.com/aircrack-ng/aircrack-ng)      | **C** | `Linux/Windows/macOS` | WiFi security auditing tools suite. |
| [bettercap](https://github.com/bettercap/bettercap)      | **Go** | `Linux/Windows/macOS/Android` | bettercap is the Swiss army knife for network attacks and monitoring. |
| [WiFi Pumpkin](https://github.com/P0cL4bs/WiFi-Pumpkin)      | **Python** | `Linux/Windows/macOS/Android` | Framework for Rogue Wi-Fi Access Point Attack.￼ |
| [Airgeddon](https://github.com/v1s1t0r1sh3r3/airgeddon)      | **Shell** | `Linux/Windows/macOS` | This is a multi-use bash script for Linux systems to audit wireless networks. |
| [Airbash](https://github.com/tehw0lf/airbash)      | **C** | `Linux/Windows/macOS` | A POSIX-compliant, fully automated WPA PSK handshake capture script aimed at penetration testing. |

#### :wrench: Exploitation Tools

Acesss systems and data with service-oriented exploits.

| Tool        | Language           | Support  | Description    |
| ----------- |-------------------------|----------|----------------|
| [SQLmap](https://github.com/sqlmapproject/sqlmap)      | **Python** | `Linux/Windows/macOS` | Automatic SQL injection and database takeover tool. |
| [XSStrike](https://github.com/UltimateHackers/XSStrike)      | **Python** | `Linux/Windows/macOS` | Advanced XSS detection and exploitation suite. |
| [Commix](https://github.com/commixproject/commix)      | **Python** | `Linux/Windows/macOS` | Automated All-in-One OS command injection and exploitation tool.￼ |

#### :busts_in_silhouette: Sniffing & Spoofing

Listen to network traffic or fake a network entity.

| Tool        | Language           | Support  | Description    |
| ----------- |-------------------------|----------|----------------|
| [Wireshark](https://www.wireshark.org)      | **C/C++** | `Linux/Windows/macOS` | Wireshark is a network protocol analyzer. |
| [WiFi Pumpkin](https://github.com/P0cL4bs/WiFi-Pumpkin)      | **Python** | `Linux/Windows/macOS/Android` | Framework for Rogue Wi-Fi Access Point Attack. |
| [Zarp](https://github.com/hatRiot/zarp)      | **Python** | `Linux/Windows/macOS` | A free network attack framework. |

#### :rocket: Web Hacking

Exploit popular CMSs that are hosted online.

| Tool        | Language           | Support  | Description    |
| ----------- |-------------------------|----------|----------------|
| [WPScan](https://github.com/wpscanteam/wpscan)      | **Ruby** | `Linux/Windows/macOS` | WPScan is a black box WordPress vulnerability scanner. |
| [Droopescan](https://github.com/droope/droopescan)      | **Python** | `Linux/Windows/macOS` | A plugin-based scanner to identify issues with several CMSs, mainly Drupal & Silverstripe. |
| [Joomscan](https://github.com/rezasp/joomscan)      | **Perl** | `Linux/Windows/macOS` | Joomla Vulnerability Scanner. |
| [Drupwn](https://github.com/immunIT/drupwn)      | **Python** | `Linux/Windows/macOS` | Drupal Security Scanner to perform enumerations on Drupal-based web applications. |
| [Webpwn3r](https://github.com/zigoo0/webpwn3r)      | **Python** | `Linux/Windows/macOS` | Web Applications Security Scanner. |

#### :tada: Post Exploitation

Exploits for after you have already gained access.

| Tool        | Language           | Support  | Description    |
| ----------- |-------------------------|----------|----------------|
| [TheFatRat](https://github.com/Screetsec/TheFatRat)      | **Java** | `Linux/Windows/macOS` | Easy tool to generate backdoor and easy tool to post exploitation attack like browser attack, dll. |
| [Microsploit](https://github.com/Screetsec/Microsploit)      | **Shell** | `Linux/Windows/macOS` | Fast and easy create backdoor office exploitation using module metasploit packet , Microsoft Office , Open Office , Macro attack , Buffer Overflow. |

#### :package: Frameworks

Frameworks are packs of pen testing tools with custom shell navigation and documentation.

| Tool        | Language           | Support  | Description    |
| ----------- |-------------------------|----------|----------------|
| [Operative Framework](https://github.com/graniet/operative-framework)      | **Python** | `Linux/Windows/macOS` | Framework based on fingerprint action, this tool is used for get information on a website or a enterprise target with multiple modules. |
| [Metasploit](https://github.com/rapid7/metasploit-framework)      | **Ruby** | `Linux/Windows/macOS` | A penetration testing framework for ethical hackers. |
| [fsociety](https://github.com/Manisso/fsociety)      | **Python** | `Linux/Windows/macOS` | fsociety Hacking Tools Pack – A Penetration Testing Framework. |
| [cSploit](https://github.com/cSploit/android)      | **Java** | `Android` | The most complete and advanced IT security professional toolkit on Android. |
| [radare2](https://github.com/radare/radare2)      | **C** | `Linux/Windows/macOS/Android` | Unix-like reverse engineering framework and commandline tools. |
| [Social Engineer Toolkit](https://github.com/trustedsec/social-engineer-toolkit)      | **Python** | `Linux/macOS` | Penetration testing framework designed for social engineering. |
| [hate_crack](https://github.com/trustedsec/hate_crack)     | **Python** | `Linux/macOS` | A tool for automating cracking methodologies through Hashcat. |
| [Wifiphisher](https://github.com/wifiphisher/wifiphisher)      | **Python** | `Linux` | The Rogue Access Point Framework. |
| [Kickthemout](https://github.com/k4m4/kickthemout)      | **Python** | `Linux/macOS` | Kick devices off your network by performing an ARP Spoof attack. |

# Additional resources

- [Devbreak on Twitter](https://twitter.com/DevbreakFR)
- [The Life of a Security Researcher](https://www.alienvault.com/blogs/security-essentials/the-life-of-a-security-researcher)
- [Find an awesome hacking spots in your country](https://github.com/diasdavid/awesome-hacking-spots)
- [Awesome-Hacking Lists](https://github.com/Hack-with-Github/Awesome-Hacking/blob/master/README.md)
- [Citadel Database](https://citadel.pw/)
- [Crack Station](http://crackstation.net/)
- [Exploit Database](http://www.exploit-db.com/)
- [Hackavision](http://www.hackavision.com/)
- [Hash Generator](http://www.insidepro.com/hashes.php?lang=eng)
- [Hackmethod](https://www.hackmethod.com/)
- [Hell Bound Hackers](http://www.hellboundhackers.org/)
- [Packet Storm Security](http://packetstormsecurity.org/)
- [Phrack Ezine](http://phrack.org/)
- [SecLists](http://seclists.org/)
- [SecTools](http://sectools.org/)
- [Security Tubes](http://www.securitytube.net/)
- [Skull Security](http://www.skullsecurity.org/)
- [Smash the Stack](http://smashthestack.org/)
- [Sploit Me](http://www.sploit.me.uk/)

## Books / Manuals

**Warning :** I haven't read them all so do not consider I am recommanding as I liked them. They just seems to provide useful resources.

- [Kali Linux Revealed](https://kali.training/downloads/Kali-Linux-Revealed-1st-edition.pdf)
- [Blue Team Field Manual (BTFM)](https://www.amazon.com/Blue-Team-Field-Manual-BTFM/dp/154101636X)
- [Cybersecurity - Attack and Defense Strategies](https://www.amazon.com/Cybersecurity-Defense-Strategies-Infrastructure-security/dp/1788475291)
- [NMAP Network Scanning : Official Discovery](https://www.amazon.com/Nmap-Network-Scanning-Official-Discovery/dp/0979958717)
- [Social Engineering : The Art of Human Hacking](https://www.amazon.com/Social-Engineering-Art-Human-Hacking/dp/0470639539)
- [Incognito Toolkit: Tools, Apps, and Creative Methods for Remaining Anonymous](https://www.amazon.com/Incognito-Toolkit-Communicating-Publishing-Researching/dp/0985049146)
- [The Tangled Web: A Guide to Securing Modern Web Applications](https://www.amazon.com/Tangled-Web-Securing-Modern-Applications/dp/1593273886)

## Discussions
- [Reddit/HowToHack](https://www.reddit.com/r/HowToHack/) Learn and ask about hacking, security and pen testing.
- [Reddit/hacking](https://www.reddit.com/r/hacking) Discuss about hacking and web security.
- [ax0nes](https://ax0nes.com/) Hacking, security, and software development forum.
- [0Day.rocks on discord](https://discord.gg/WmYzJfD) Discord server about the 0day.rocks blog for technical and general InfoSec/Cyber discussions & latest news.

## Security Advisories

- [CVE](http://cve.mitre.org/)
- [CWE](http://cwe.mitre.org/)
- [NVD](http://web.nvd.nist.gov/)
- [WVE](http://www.wve.org/)

## Challenges

- [Vulnhub](https://www.vulnhub.com/) - Has a lot of VMs to play with. some are beginner friendly, some aren't.
- [Itsecgames](http://www.itsecgames.com/) - buggy web app
- [Dvwa](http://www.dvwa.co.uk/) - Damn Vulnerable Web Application
- [Hackthissite](https://www.hackthissite.org/)
- [Hackthis](https://www.hackthis.co.uk/)
- [Root-me](https://www.root-me.org/)
- [Overthewire](http://overthewire.org/wargames/)
- [Ctftime](https://ctftime.org/)

# License

This repository is under MIT license.
