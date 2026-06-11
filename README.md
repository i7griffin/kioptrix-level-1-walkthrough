# Kioptrix Level 1 Walkthrough

## Overview

Kioptrix Level 1 is a beginner-friendly vulnerable machine from VulnHub that helped me practice the fundamentals of penetration testing in a safe lab environment.

## Skills Practiced

- Linux navigation
- Network discovery
- Service enumeration
- Vulnerability research
- Exploitation methodology
- Privilege escalation
- Documentation

---

## Lab Environment

### Attacker Machine
- Kali Linux

### Target Machine
- Kioptrix Level 1

### Virtualization
- VMware Workstation

### Network Configuration
- Host-Only Lab Network

---

## Methodology

### Phase 1: Reconnaissance

The first step was identifying systems on the network and confirming that the target machine was reachable.

**Concepts learned:**
- Host discovery
- IP addressing
- Network segmentation

---

### Phase 2: Enumeration

After locating the target, I enumerated exposed services and gathered information about the operating system and running applications.

**Concepts learned:**
- Port scanning
- Service identification
- Banner grabbing
- Version detection

---

### Phase 3: Vulnerability Assessment

Using the information collected during enumeration, I researched potential weaknesses associated with the discovered services.

**Concepts learned:**
- CVE research
- Searchsploit usage
- Exploit validation
- Attack surface analysis

---

### Phase 4: Initial Access

After identifying a suitable attack path, I successfully obtained access to the target system.

**Concepts learned:**
- Exploitation workflow
- Shell access
- Remote command execution

---

### Phase 5: Privilege Escalation

Once inside the system, I performed local enumeration and escalated privileges.

**Concepts learned:**
- Linux privilege escalation
- System enumeration
- User permissions
- Root access concepts

---

## Key Takeaways

### Technical

- Enumeration is the most important phase of penetration testing.
- Small details in service information can lead to successful exploitation.
- Understanding Linux commands greatly improves efficiency.
- Documentation is critical throughout an engagement.

### Personal Learning

This machine helped me improve my understanding of:

- Linux fundamentals
- Nmap methodology
- Service enumeration
- Exploit research
- Penetration testing workflow

---

## Screenshots

Screenshots documenting the process are available in the `screenshots/` directory.

---

## Tools Used

- Kali Linux
- Nmap
- Netdiscover
- Searchsploit
- Linux Command Line
- VMware Workstation

---

## Disclaimer

This walkthrough was completed in a controlled home lab environment for educational purposes only.
