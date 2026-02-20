# Intro-to-Computer-Security

# 🔐 Computer Security Course – Summary of Learning

This repository represents a structured summary of what I learned in my Computer Security course.  
It covers foundational principles, core cryptographic mechanisms, system and network security, and broader human-centered concerns such as usability and privacy.

The goal of this course was not only to understand attacks, but to understand *why* systems fail, how to defend them, and how security interacts with real-world human behavior.

---

## 📌 1. Introduction to Computer Security

- Goals of computer security: confidentiality, integrity, availability
- Threat models and attack surfaces
- Different domains of security
  - Physical security
  - System-level security
  - Network-level security

This section established the conceptual foundation: security is not a feature you add later — it must be designed from the beginning.

---

## 🔑 2. Cryptography Review

### Symmetric vs Asymmetric Encryption
- Differences in key usage, performance, and practical applications
- Trade-offs between efficiency and scalability

### Symmetric Encryption
- DES (Data Encryption Standard)
- AES (Advanced Encryption Standard)

### Asymmetric / Public-Key Cryptography
- RSA and its mathematical foundation
- Practical applications in authentication and secure communication

### Key Exchange & Security Protocols
- Diffie-Hellman key exchange
- Needham-Schroeder protocol
- Understanding protocol vulnerabilities and replay attacks

### PKI (Public Key Infrastructure)
- Certificates
- Certificate authorities
- Trust chains

### Hashing
- Cryptographic hash functions
- Integrity verification
- Password storage mechanisms

This section emphasized how cryptographic primitives combine to form secure systems.

---

## 🖥 3. Operating System Security

- OS execution environment
- Process isolation and access control
- Buffer overflow vulnerabilities
- Memory exploitation concepts

This part highlighted how low-level implementation flaws can compromise entire systems.

---

## 🦠 4. Malware

- Computer viruses and worms
- Common malware attack strategies
- Detection techniques and countermeasures
- Defense-in-depth principles

Understanding malware reinforced how attackers think and adapt.

---

## 🌐 5. Network Security

- Data link layer security mechanisms
- Network layer protections
- Transport layer security concepts

This section explored how data is protected while in transit and where interception or manipulation can occur.

---

## 🌍 6. Web Security

- SSL/TLS protocols
- Server-side attacks
- Client-side attacks
- Authentication mechanisms
- Password security practices

This module demonstrated how modern web systems are secured — and how they fail.

---

## 👤 7. Usability and Security

- Usability vs Security trade-offs
- Human-centered security
- Designing systems that users can actually use securely

This was a critical insight: a secure system that users cannot understand is effectively insecure.

---

## 🔒 8. Privacy

- Why privacy matters
- Privacy policies and compliance
- Global perspectives on privacy

This section connected technical mechanisms with ethical and societal implications.

---

# 🧠 Key Takeaways

- Security must be built into systems, not patched afterward.
- Cryptography is powerful but fragile if implemented poorly.
- Many security failures stem from human factors.
- Privacy is both a technical and socio-political issue.
- Security is a continuous process, not a one-time solution.

---

This repository reflects both theoretical understanding and applied learning from the course.
