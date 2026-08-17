# 📦 File Packer & Unpacker with Encryption

A Java-based file utility that combines multiple files into a single encrypted archive and restores them — with full metadata intact — on demand. Think of it as a lightweight, secure alternative to ZIP/TAR, built from scratch to demonstrate core file-handling and cryptography concepts in Java.

![Java](https://img.shields.io/badge/Java-JRE%20Compatible-orange)
![Platform](https://img.shields.io/badge/Platform-Cross--Platform-blue)
![Status](https://img.shields.io/badge/Status-Active-brightgreen)

---

## Overview

This project provides a simple, self-contained way to **archive** multiple files into one package and **restore** them later — all while preserving original file metadata such as name, size, and timestamp. To keep packed data secure, the archive is encrypted before being written to disk, and only users with the correct decryption key can unpack and access the original files.

It's designed both as a practical utility and as a hands-on learning exercise in Java I/O, metadata handling, and encryption fundamentals.

---

## Key Features

### File Packing
- Combines multiple regular files into a single, unified archive file.
- Preserves essential metadata — file name, size, and timestamp — alongside the actual content.

### File Unpacking
- Extracts individual files from the packed archive.
- Restores original metadata and file structure exactly as it was before packing.

### Data Security
- Encrypts the packed archive to prevent unauthorized access.
- Requires proper decryption before any data can be extracted.

### Cross-Platform Support
- Runs on any system with a Java Runtime Environment (JRE) — no platform-specific dependencies.

---

## Learning Outcomes

Working on this project provides hands-on experience with:

- Java I/O Streams and File Handling APIs
- Metadata management during file read/write operations
- Encryption and decryption techniques in Java
- Core principles behind archiving and compression utilities (similar to ZIP/TAR)

---

## Getting Started

### Prerequisites
- Java Runtime Environment (JRE) installed on your system
- Java Development Kit (JDK) if you intend to compile from source

### Usage

**Packing files into an archive:**
```bash
java FilePacker Demo Pack.txt
```

**Unpacking files from an archive:**
```bash
java FileUnpacker Pack.txt
```

> Replace `Demo` and `MarvellousPack.txt` with your source folder/files and desired archive name as needed.

---

## 🛠️ Tech Stack

| Component         | Technology             |
|-------------------|------------------------|
| Language          | Java                   |
| I/O Handling      | Java I/O Streams       |
| Security          | Java Encryption APIs   |
| Compatibility     | Any JRE-supported OS   |

---

## 📌 Roadmap Ideas

- [ ] Add compression support alongside encryption
- [ ] Support password-based key derivation for decryption
- [ ] Add a progress indicator for large archives
- [ ] Build a simple GUI wrapper

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to fork the repo and submit a pull request.

## 📄 License

This project is open source and available for educational and personal use.
