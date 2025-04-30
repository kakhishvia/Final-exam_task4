
# Task 4 – Email Encryption and Signature Simulation (PGP Style)

## 🔐 Overview
This task simulates secure email communication using asymmetric encryption and digital signatures (similar to PGP/S/MIME).

---

## 🔄 Encryption & Signature Workflow

### 🔹 Alice:
1. Generates an RSA key pair (`private.key`, `public.asc`)
2. Writes a message to `original_message.txt`
3. Signs the message with her private key → `signed_message.asc`

### 🔹 Bob:
4. Verifies the signature using Alice's public key
5. If valid, saves the original message as `decrypted_message.txt`
6. Logs the result in `signature_verification.txt`

---

## 📂 Files Submitted

- `original_message.txt` – Plaintext message from Alice  
- `signed_message.asc` – Signature of the message  
- `decrypted_message.txt` – Verified message (only if signature is valid)  
- `public.asc` – Alice’s public key  
- `private.key` – Alice’s private key  
- `signature_verification.txt` – Signature verification result  
