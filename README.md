# Awesome Hacking

A curated list of awesome Hacking. Inspired by [awesome-machine-learning](https://github.com/josephmisiti/awesome-machine-learning/)

If you want to contribute to this list (please do), send me a pull request or contact me [@carpedm20](https://www.twitter.com/carpedm20)

For a list of free hacking books available for download, go [here](https://github.com/josephmisiti/awesome-machine-learning/blob/master/books.md)


## Table of Contents

<!-- MarkdownTOC depth=4 -->

- [System](#system)
    - [Tutorials](#system-tutorials)
    - [Tools](#system-tools)
    - [Wargame](#system-wargame)
- [Reverse Engineering](#reverse-engineering)
    - [Tutorials](#reverse-engineering-tutorials)
    - [Tools](#reverse-engineering-tools)
    - [Wargame](#reverse-engineering-wargame)
- [Web](#web)
    - [Tutorials](#web-tutorials)
    - [Tools](#web-tools)
    - [Wargame](#web-wargame)
- [Network](#network)
    - [Tutorials](#network-tutorials)
    - [Tools](#network-tools)
    - [Wargame](#network-wargame)
- [Forensic](#forensic)
    - [Tutorials](#forensic-tutorials)
    - [Tools](#forensic-tools)
    - [Wargame](#forensic-wargame)
- [Cryptography](#cryptography)
    - [Tutorials](#cryptography-tutorials)
    - [Tools](#cryptography-tools)
    - [Wargame](#cryptography-wargame)
- [Wargame](#wargame)
    - [System](#system-wargame)
    - [Reverse Engineering](#reverse-engineering-wargame)
    - [Web](#web-wargame)
    - [Network](#network-wargame)
    - [Forensic](#forensic-wargame)
    - [Cryptography](#cryptography-wargame)
- [CTF](#ctf)
    - [Competition](#ctf-competiton)
    - [Information](#ctf-information)

<!-- /MarkdownTOC -->

<a name="system" />
# System

<a name="system-tutorial" />
## Tutorials

Tutorials for system hacking

 * [Corelan Team's Exploit writing tutorial](https://www.corelan.be/index.php/2009/07/19/exploit-writing-tutorial-part-1-stack-based-overflows/)
 * [Exploit Writing Tutorials for Pentesters](http://www.punter-infosec.com/exploit-writing-tutorials-for-pentesters/)

<a name="system-tools" />
## Tools

Tools for system hacking

 * [Metasploit](https://github.com/rapid7/metasploit-framework) A computer security project that provides information about security vulnerabilities and aids in penetration testing and IDS signature development.
 * [mimikatz](https://github.com/gentilkiwi/mimikatz) - A little tool to play with Windows security



<a name="reverse-engineering" />
# Reverse Engineering

<a name="reverse-engineering-tutorial" />
## Tutorials

Tutorials for reverse engineering

* [Lenas Reversing for Newbies](https://tuts4you.com/download.php?list.17)
* [Malware Analysis Tutorials: a Reverse Engineering Approach](http://fumalwareanalysis.blogspot.kr/p/malware-analysis-tutorials-reverse.html)

<a name="reverse-engineering-tools" />
## Tools

Tools for reverse engineering

### Debugger
 * [IDA](https://www.hex-rays.com/products/ida/) - IDA is a Windows, Linux or Mac OS X hosted multi-processor disassembler and debugger
 * [OllyDbg](http://www.ollydbg.de/) - A 32-bit assembler level analysing debugger for Windows

### Decompiler

#### Java
 * [dex2jar](https://code.google.com/p/dex2jar/) - Tools to work with android .dex and java .class files
 * [JD-GUI](http://jd.benow.ca/) - A standalone graphical utility that displays Java source codes of “.class” files
 * [JAD](http://varaneckas.com/jad/) - JAD Java Decompiler

#### .NET
 * [dotPeek](https://www.jetbrains.com/decompiler/) - a free-of-charge .NET decompiler from JetBrains

### Unpacker
 * [UPX](http://upx.sourceforge.net/) - the Ultimate Packer for eXecutables

### General purpose
 * [androguard](https://code.google.com/p/androguard/) - Reverse engineering, Malware and goodware analysis of Android applications


<a name="web" />
# Web

<a name="web-tools" />
## Tools

Tools for web hacking

### Encoding/Decoding

 * [tools.web-max.ca](http://tools.web-max.ca/encode_decode.php) - base64 base85 md4,5 hash, sha1 hash encoding/decoding


<a name="network" />
# Network

<a name="network-tools" />
## Tools

Tools for network analysis

### Packet Capture

#### TCP

 * [Wireshark](https://www.wireshark.org/) - A free and open-source packet analyzer
 * [NetworkMiner](http://www.netresec.com/?page=NetworkMiner) - A Network Forensic Analysis Tool (NFAT)
 * [tcpdump](http://www.tcpdump.org/) - a powerful command-line packet analyzer; and libpcap, a portable C/C++ library for network traffic capture

#### HTTP/HTTPS
 * [Paros](http://sourceforge.net/projects/paros/) - A Java based HTTP/HTTPS proxy for assessing web application vulnerability
 * [ZAP](https://www.owasp.org/index.php/OWASP_Zed_Attack_Proxy_Project) - The Zed Attack Proxy (ZAP) is an easy to use integrated penetration testing tool for finding vulnerabilities in web applications

### Man In The Middle
 * [mitmproxy](https://mitmproxy.org/) - An interactive, SSL-capable man-in-the-middle proxy for HTTP with a console interface
 * [mitmsocks4j](https://github.com/Akdeniz/mitmsocks4j) - Man in the Middle SOCKS Proxy for JAVA

### Packet Sniffer

### Scanner

 * [nmap](http://nmap.org/) - Nmap (Network Mapper) is a security scanner


<a name="forensic" />
# Forensic

<a name="forensic-tools" />
## Tools

Tools for forensic

* [Autospy](http://www.sleuthkit.org/autopsy/) - A digital forensics platform and graphical interface to [The Sleuth Kit](http://www.sleuthkit.org/sleuthkit/index.php) and other digital forensics tools

### Binary

 * [malzilla](http://malzilla.sourceforge.net/) - Malware hunting tool
 * [PEview](http://wjradburn.com/software/) - a quick and easy way to view the structure and content of 32-bit Portable Executable (PE) and Component Object File Format (COFF) files

### Hex Editor

 * [HxD](http://mh-nexus.de/en/hxd/) - A hex editor which, additionally to raw disk editing and modifying of main memory (RAM), handles files of any size
 * [WinHex](http://www.winhex.com/winhex/) - A hexadecimal editor, helpful in the realm of computer forensics, data recovery, low-level data processing, and IT security

### Others

 * [BinText](http://www.mcafee.com/kr/downloads/free-tools/bintext.aspx) - A small, very fast and powerful text extractor that will be of particular interest to programmers


# Cryptography


<a name="wargame" />
# Wargame

<a name="wargame-system" />
## System
 * [OverTheWire - Semtex](http://overthewire.org/wargames/semtex/)
 * [OverTheWire - Vortex](http://overthewire.org/wargames/vortex/)
 * [OverTheWire - Drifter](http://overthewire.org/wargames/drifter/)
 * [pwnable.kr](http://pwnable.kr/) - Provide various pwn challenges regarding system security
 * [Exploit Exercises - Nebula](https://exploit-exercises.com/nebula/)
 * [SmashTheStack](http://smashthestack.org/)

<a name="wargame-reverse-engineering" />
## Reverse Engineering
 * [Reversing.kr](http://www.reversing.kr/) - This site tests your ability to Cracking & Reverse Code Engineering
 * [CodeEngn](http://codeengn.com/challenges/) - (Korean)
 * [simples.kr](http://simples.kr/) - (Korean)

<a name="wargame-web" />
## Web
 * [Hack This Site!](https://www.hackthissite.org/) - a free, safe and legal training ground for hackers to test and expand their hacking skills
 * [Webhacking.kr](http://webhacking.kr/)

<a name="wargame-cryptography" />
## Cryptography
 * [OverTheWire - Krypton](http://overthewire.org/wargames/krypton/)

<a name="wargame-general" />
## general


<a name="ctf" />
# CTF

<a name="ctf-competition" />
## Competition
 * [DEF CON](https://legitbs.net/)
 * [CSAW CTF](https://ctf.isis.poly.edu/)
 * [hack.lu CTF](http://hack.lu/)
 * [Pliad CTF](http://www.plaidctf.com/)

<a name="ctf-information" />
## Information
 * [CTFtime.org](https://ctftime.org/) - All about CTF (Capture The Flag)
 * [WeChall](http://www.wechall.net/)