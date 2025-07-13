# Blockchain-KeyExchange-SecureAuth-VANET

This project implements a secure, scalable, and privacy-preserving authentication framework for Vehicular Ad-hoc Networks (VANETs) using **Blockchain** and **Identity-Based Online/Offline Signature (IBOOS)** mechanisms. The system simulates interactions between **Vehicles**, **Roadside Units (RSUs)**, and a **Trusted Authority**, focusing on conditional privacy, secure key generation, and efficient data transmission.

---

## 📘 Abstract

In VANETs, real-time vehicle communication improves safety and traffic management but introduces serious security and privacy concerns. This project proposes a decentralized, blockchain-integrated approach to key management and authentication. RSUs act as trusted nodes, helping to generate and distribute encrypted pseudonyms and secret keys to vehicles. All authentication events are recorded on a blockchain ledger, enhancing traceability, data integrity, and attack resilience without relying on a single point of trust.

---

## 🎯 Objectives

- Enable secure vehicle authentication using identity-based signatures.
- Improve data transmission efficiency and privacy.
- Minimize communication overhead on RSUs and central authority.
- Ensure traceability, scalability, and resistance to network attacks.

---

## 📦 Project Modules

1. **Encryption Module (IBOOS + CP-ABE)** – Secure encryption/decryption based on identity and access policies.
2. **Central Controller Module** – Manages RSU/vehicle/content server information.
3. **Bilinear Pairing Module** – Handles secure key outsourcing to improve performance.
4. **Data Replication Module** – Detects and handles duplicate vehicle records across RSUs.

---

## 🧠 Technologies Used

- Java (Frontend & Backend)
- Blockchain simulation
- Cryptography: IBOOS, CP-ABE, Diffie-Hellman
- GUI with Java Swing
- Datagram Sockets for communication

---

## 📈 System Flow

1. Vehicle sends request to nearest RSU with pseudonym and public key.
2. RSU verifies pool capacity and communicates with Trusted Authority (TA).
3. TA assigns encrypted pseudonym sets and key attributes.
4. Vehicle receives the pseudonym set and communicates securely.
5. All authentication and transaction events are recorded on blockchain.

---

## 🧩 Advantages

- ✅ Blockchain ensures tamper-proof, traceable authentication.
- ✅ Reduced centralized authority load using decentralized RSUs.
- ✅ IBOOS + CP-ABE provides flexible, fine-grained access control.
- ✅ Prevents common attacks: spoofing, Sybil, and man-in-the-middle.

---

## 📝 License

This project is developed for academic use only.
