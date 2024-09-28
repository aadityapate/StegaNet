# StegaNET: Secure Communication with Steganography & SAML

### Overview

**StegaNET** is a secure communication system designed to protect sensitive information using advanced steganography and cryptography techniques, combined with Secure Assertion Markup Language (SAML) for user authentication. The project ensures the confidentiality, integrity, and authenticity of transmitted messages by embedding encrypted data within carrier files, such as images or audio. Only authenticated users can access these hidden messages, making it a robust solution for secure communication in a digital world.

### Features

- **Steganography**: Messages are hidden within carrier files (e.g., images, audio) using advanced steganography techniques, making it difficult for third parties to detect the presence of a message.
- **Encryption**: The system uses strong encryption algorithms (e.g., AES-256) to ensure the confidentiality of messages before embedding them within the carrier data.
- **SAML Authentication**: Secure user authentication via SAML ensures that only authorized individuals can access and transmit messages.
- **User-friendly Interface**: The system is designed with a simple and intuitive interface, making it easy for users to compose messages, select carrier files, and manage the communication process.

### Problem Statement

With the rise of sophisticated cyber threats, traditional encryption methods are increasingly vulnerable to attacks. StegaNET addresses this issue by embedding encrypted messages within seemingly innocuous files, thereby enhancing communication security and offering a covert approach to secure digital exchanges.

### Objectives

1. Implement a secure communication system that integrates advanced cryptography and steganography techniques.
2. Regulate user access through SAML, allowing entry only to authenticated and authorized users.
3. Ensure that sensitive messages are protected against unauthorized access and detection.

### System Architecture

1. **Message Encryption**: Messages are encrypted using robust algorithms (e.g., AES-256) before being embedded within carrier files.
2. **Steganographic Embedding**: Advanced steganography techniques are used to embed messages into various file formats (images, audio, video).
3. **SAML Authentication**: User access is restricted through SAML-based authentication, ensuring only verified users can retrieve the hidden messages.

### Technologies Used

- **Python-SAML**: Used for integrating SAML-based user authentication.
- **OpenStego**: A steganography library that enables secure message embedding.
- **PyCryptodome**: A library for implementing AES-256 encryption.
- **Diffie-Hellman Key Exchange**: An optional secure key exchange mechanism.

### Usage

1. **Login**: Authenticate using your SAML credentials.
2. **Compose Message**: Enter the message you want to secure.
3. **Select Carrier File**: Choose an image or audio file as the carrier for your hidden message.
4. **Encrypt and Embed**: The message is encrypted and embedded within the selected carrier file.
5. **Send/Receive Message**: Share the carrier file with the recipient, who can extract and decrypt the message using their credentials.

### Applications

- **Corporate Security**: Ensuring secure internal communications.
- **Healthcare**: Safeguarding sensitive medical information.
- **Government**: Protecting classified communications.
- **Journalism**: Enabling secure, confidential communication for journalists and whistleblowers.

### Future Work

- Implement additional steganography techniques to enhance message capacity and reduce detectability.
- Introduce a mobile version for secure communication on-the-go.
- Explore cloud integration for secure message storage.

