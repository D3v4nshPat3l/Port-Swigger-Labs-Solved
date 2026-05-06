# Access Control Labs

This directory contains solved PortSwigger Web Security Academy labs focused on Access Control vulnerabilities and authorization flaws.

These labs demonstrate how improper authorization mechanisms can allow attackers to access sensitive functionality, escalate privileges, or retrieve unauthorized data.

---

# About Access Control

Access control vulnerabilities occur when applications fail to properly enforce restrictions on what authenticated or unauthenticated users are allowed to do.

These flaws can lead to:
- Unauthorized access to sensitive data
- Privilege escalation
- Administrative account compromise
- Account takeover
- Information disclosure

---

# Labs Covered

## Apprentice Labs

- Unprotected admin functionality with unpredictable URL
- User role controlled by request parameter
- User role can be modified in user profile
- User ID controlled by request parameter
- User ID controlled by request parameter, with unpredictable user IDs
- User ID controlled by request parameter with data leakage in redirect
- User ID controlled by request parameter with password disclosure
- Insecure direct object references (IDOR)

---

## Practitioner Labs

- URL-based access control can be circumvented
- Method-based access control can be circumvented
- Multi-step process with no access control on one step
- Referer-based access control

---

# What Each Lab Contains

Each lab solution includes:
- Vulnerability overview
- Step-by-step exploitation
- Burp Suite request/response analysis
- Payload explanations
- Important observations
- Screenshots for proof and learning
- Security impact
- Mitigation techniques

---

# Key Concepts Practiced

- Vertical privilege escalation
- Horizontal privilege escalation
- IDOR vulnerabilities
- Authorization bypass
- Parameter manipulation
- Forced browsing
- Role-based access control flaws
- HTTP method tampering
- Header-based authorization bypass

---

# Tools Used

- Burp Suite Community Edition
- Firefox Developer Edition
- Kali Linux
- HTTP Request Manipulation
- Browser Developer Tools

---

# Educational Purpose

These labs are solved strictly for educational and ethical learning purposes within the legal environment provided by PortSwigger Web Security Academy.

---

# Goal

The primary objective of these labs is to strengthen practical understanding of:
- Web application authorization models
- Real-world access control flaws
- Exploitation methodology
- Secure application design
- Defensive security concepts
