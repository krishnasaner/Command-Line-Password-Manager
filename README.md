# Command-Line Password Manager

A secure and lightweight command-line password manager that allows users to store, retrieve, and manage credentials locally using encryption and a master password. Designed for developers, system administrators, and privacy-conscious users.

## Features

- Store and retrieve encrypted credentials from the command line
- Master password authentication using secure hashing (PBKDF2 / bcrypt)
- Local encryption and decryption using the system keyring
- Support for multiple accounts per service
- Cross-platform compatibility (Linux, macOS, Windows)
- No cloud dependencies — all data is stored locally

## Technology Stack

- **Language**: Python
- **Libraries**:
  - `keyring` – securely store secrets in the OS key manager
  - `getpass` – secure password entry
  - `hashlib`, `secrets`, `base64` – encryption and secure hashing
  - `argparse` – command-line argument parsing
  - Optional: `cryptography` or `pyAesCrypt` for enhanced encryption

