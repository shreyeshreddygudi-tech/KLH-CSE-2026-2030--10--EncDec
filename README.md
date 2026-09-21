# Design and Simulation of Data Encryption & Decryption Unit

**DDCA Project · Department of Computer Science and Engineering**  
**KL University, Hyderabad**  
**B.Tech CSE · Batch-10 · AY 2026–2030**

---

## Project Overview

This project implements a **purely combinational, gate-level symmetric-key cipher** using XOR logic.  
It performs **4-bit encryption and decryption** with the same key and includes built-in verification to confirm that the decrypted output matches the original plaintext.

The entire system is designed and simulated in **Logisim** using only basic logic gates and comparators — no clocks, flip-flops, or memory elements.

**Core Identity:**  
\[
(P \oplus K) \oplus K = P
\]

---

## Team Members

| Name                          | Roll Number   |
|-------------------------------|---------------|
| Shreyesh Reddy Gudi           | 2620030608    |
| Kaustubha Srinivas Kaseebhotla| 2620030601    |
| Rachuri Harshita              | 2620030654    |
| Rudrakashala Harshitha        | 2620030591    |

**Guide:** Lakshmi Karthek Vankamamidi 

---

## Objectives

1. **Encrypt** – Build a 4-bit XOR encryptor: \( C = P \oplus K \)
2. **Decrypt** – Recover the plaintext using the same key: \( D = C \oplus K \)
3. **Verify** – Use comparators to automatically check \( D == P \)
4. **Simulate** – Design and test the complete circuit in Logisim
5. **Document** – Validate behaviour with truth tables (1-bit and 4-bit cases)

**Design Constraint:** Only gates and comparators — no encoders, decoders, or sequential elements.

---

## System Architecture
