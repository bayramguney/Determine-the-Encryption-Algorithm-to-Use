# Determine-the-Encryption-Algorithm-to-Use

# Determine the Encryption Algorithm to Use

## Overview

This lab explores different encryption algorithms and security methods used to protect personal data, wireless communications, and corporate data transmitted across the internet.

The goal of this lab is to understand how to select appropriate encryption and authentication technologies based on different security requirements.

---

# Objectives

- Secure personal data using encryption methods.
- Compare encryption algorithms and understand their strengths.
- Evaluate wireless security options.
- Identify IPsec encryption and authentication algorithms.
- Recommend appropriate security solutions for different scenarios.

---

# Lab Environment

**Required Resources:**

- Windows PC with Internet access
- 7-Zip compression and encryption utility
- Internet research resources
- Cisco IPsec documentation

---

# Part 1: Secure Personal Data

## Scenario

A student needs to store confidential information on a shared computer and wants to prevent unauthorized users from reading, stealing, or modifying the data.

## Security Approach

To protect personal files:

- Use file encryption.
- Apply strong passwords.
- Restrict file permissions.
- Store sensitive data inside encrypted archives.
- Use modern encryption standards.

## Encryption Algorithm Selection

### Recommended Algorithm: AES-256

AES (Advanced Encryption Standard) is recommended because:

- It provides strong encryption protection.
- It supports 128-bit, 192-bit, and 256-bit key sizes.
- It is resistant to brute-force attacks.
- It is faster and more secure than older algorithms.

### Algorithm Comparison

| Algorithm | Security Level | Status |
|---|---|---|
| DES | Weak | Outdated |
| 3DES | Moderate | Legacy |
| AES | Strong | Recommended |

---

# 7-Zip Encryption Testing

## Encryption Methods

7-Zip supports two encryption methods for ZIP archives:

### ZipCrypto

- Older ZIP encryption method.
- Provides limited security.
- Vulnerable to password-cracking attacks.
- Mainly used for compatibility.

### AES-256

- Modern encryption standard.
- Uses a 256-bit encryption key.
- Provides stronger protection.
- Recommended for sensitive information.

## Selected Method

**AES-256 encryption** was selected because it provides the strongest protection for confidential files.

---

# Part 2: Secure Wireless Data

## Scenario

A small IT support business needs to configure secure wireless access for a large home containing multiple devices, including:

- Smartphones
- Tablets
- Computers
- Smart TVs
- Oculus devices
- Printers
- Wi-Fi 6 enabled devices

The recommended solution is the **Linksys Atlas Pro 6 Wi-Fi 6 Mesh System**.

---

# Wireless Security Evaluation

## Available Security Features

The Linksys Atlas Pro 6 supports:

- WPA3 Personal
- WPA2 Personal
- WPA2/WPA3 Mixed Mode

---

## Recommended Wireless Security

### WPA3 Personal

WPA3 Personal is recommended because:

- It provides stronger encryption than WPA2.
- It improves protection against password attacks.
- It supports modern Wi-Fi 6 devices.
- It provides improved wireless security for home networks.

---

# Part 3: Secure Corporate Data Between Sites

## Scenario

A multi-site organization needs to securely transfer corporate data between locations over the public internet.

The organization uses Cisco ISR routers and requires a secure site-to-site IPsec VPN solution.

---

# IPsec Encryption Algorithms

Supported encryption algorithms include:

- DES
- 3DES
- AES-128
- AES-192
- AES-256
- AES-GCM

---

# IPsec Authentication and Integrity Algorithms

Hashing algorithms used for authentication and integrity include:

- MD5 (legacy)
- SHA-1
- SHA-2 family:
  - SHA-256
  - SHA-384
  - SHA-512

---

# Recommended Corporate VPN Security

## Encryption Algorithm

**AES-256**

Reason:

- Provides strong confidentiality.
- Protects sensitive corporate information.
- Resistant to modern attacks.

## Authentication Algorithm

**SHA-256**

Reason:

- Ensures data integrity.
- Detects unauthorized changes.
- Provides stronger security than MD5 and SHA-1.

---

# Final Security Recommendations

| Use Case | Recommended Security |
|---|---|
| Personal File Protection | AES-256 |
| 7-Zip Archive Encryption | AES-256 |
| Wireless Network Security | WPA3 Personal |
| Site-to-Site VPN Encryption | AES-256 |
| VPN Data Integrity | SHA-256 |

---

# Skills Demonstrated

- Understanding symmetric encryption algorithms.
- Comparing encryption strength and security methods.
- Configuring encrypted file archives.
- Evaluating wireless security protocols.
- Understanding IPsec VPN technologies.
- Selecting appropriate cryptographic algorithms.
- Applying cybersecurity principles to real-world scenarios.

---

# Key Takeaways

- Modern security solutions should use strong encryption algorithms such as AES.
- Legacy algorithms like DES and ZipCrypto should be avoided for sensitive information.
- WPA3 provides stronger wireless protection for modern networks.
- IPsec VPNs use encryption and hashing algorithms to protect data confidentiality and integrity.
- Choosing the correct security technology depends on the type of data and threat environment.
