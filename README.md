# CyberVault CTF

A hands-on Capture The Flag (CTF) project covering **Web Security, Digital Forensics, Reverse Engineering, Binary Exploitation, and Cryptography**.

## Overview

CyberVault CTF was a practical cybersecurity challenge conducted at **MIT-WPU, Pune**.

The challenges required investigating vulnerable applications, analyzing source code and Git history, recovering hidden information, performing forensic analysis, reverse engineering encoded data, analyzing binary exploitation scenarios, and solving cryptographic problems.

The project helped strengthen practical skills in cybersecurity investigation, exploitation methodology, scripting, and problem solving.

## CTF Categories

The CTF covered the following areas:

- Web Security
- Digital Forensics
- Reverse Engineering
- Binary Exploitation (Pwn)
- Cryptography

## Challenges & Techniques

### Web Security

The web challenges involved reconnaissance, application analysis, source-code investigation, and identifying security weaknesses.

Techniques and tools included:

- `.git` exposure analysis
- Git history investigation
- Source-code recovery
- Web application reconnaissance
- Authentication analysis
- Local File Inclusion (LFI) analysis
- Vulnerable data-processing functionality
- HTTP request analysis
- Burp Suite

### Digital Forensics

The forensic challenges involved recovering information from partially obscured and protected files.

Techniques included:

- Image analysis
- Depixelization
- Archive investigation
- Password-protected file analysis
- Password hash extraction
- Password recovery

Tools used included:

- Depix
- pdf2john
- John the Ripper

### Reverse Engineering

The reverse-engineering challenges required analyzing encoded and transformed data.

Techniques included:

- Base64 decoding
- Gzip decompression
- Byte-level transformations
- XOR deobfuscation
- Python scripting
- Step-by-step data recovery

Tools used included:

- CyberChef
- Python
- Custom scripts

### Binary Exploitation

The Pwn challenges involved analyzing ELF binaries and understanding memory and control-flow related vulnerabilities.

Techniques included:

- ELF binary analysis
- Debugging with GDB
- Address calculation
- GOT manipulation
- Local exploitation
- Remote exploitation

Tools used included:

- GDB
- pwntools
- Python

### Cryptography

The cryptography challenge involved concepts related to lattice-based cryptography and learning with errors.

The analysis included:

- MLWE / LWE concepts
- Polynomial rings
- Finite fields
- Lattice construction
- LLL reduction
- Secret-key recovery
- Decryption

Tools and technologies included:

- SageMath
- Python
- Mathematical and lattice-based analysis

## Tools & Technologies

| Tool / Technology | Purpose |
|---|---|
| **Burp Suite** | Web application analysis and HTTP request inspection |
| **Git / wget** | Source and repository investigation |
| **Python** | Automation, scripting, decoding and analysis |
| **CyberChef** | Encoding and transformation analysis |
| **Depix** | Depixelization analysis |
| **John the Ripper** | Password recovery |
| **pdf2john** | Password hash extraction |
| **GDB** | Binary debugging |
| **pwntools** | Binary exploitation and scripting |
| **SageMath** | Mathematical and cryptographic analysis |

## Investigation Workflow

The challenges were approached using a structured investigation process:

```text
Reconnaissance
      ↓
Identify Attack Surface
      ↓
Source / File Analysis
      ↓
Understand Vulnerability or Data Format
      ↓
Develop Analysis / Exploitation Approach
      ↓
Automate Where Appropriate
      ↓
Recover Information
      ↓
Document Findings