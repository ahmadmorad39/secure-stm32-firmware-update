# 🔐 Secure Firmware Update System (STM32 + UART + AES + ECDSA)

## 🚀 Project Overview

This project implements a **secure firmware update mechanism** for embedded systems based on STM32 microcontrollers. It supports **encrypted and signed firmware updates** delivered over **UART**, with a dedicated **bootloader** that performs cryptographic verification before applying updates.

The system is suitable for real-world use cases like **medical devices**, **industrial control units**, and **smart locks**.

---

## 🛡️ Security Features

- ✅ **Digital Signature Verification** (ECDSA over SHA-256)
- ✅ **Firmware Encryption** (AES-128-CBC or AES-256-GCM)
- ✅ **Secure Bootloader** stored in read-only Flash
- ✅ **Anti-Rollback Protection** via version checks
- ✅ **CRC32 or SHA-256 Integrity Verification**

