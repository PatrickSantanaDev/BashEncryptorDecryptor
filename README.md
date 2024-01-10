# Advanced File Encrypter/Decrypter

This Bash script provides an advanced solution for encrypting and decrypting files. It's designed to be user-friendly and efficient, suitable for handling sensitive data with added security measures.

## Features

- **Encryption and Decryption**: Allows users to encrypt and decrypt files using GPG (GNU Privacy Guard).
- **Recursive File Selection**: Enables specifying a directory to recursively find all files for encryption or decryption.
- **Secure File Deletion**: Securely deletes original files post-encryption using the `shred` command.
- **Intuitive User Interface**: Offers a simple, menu-driven interface for ease of use.
- **Restoration of Original File Names**: Restores files to their original names after decryption, removing the `.gpg` extension.

## Usage

1. **Start the Script**: Run the script in your terminal.
2. **Select an Operation**: Choose to Encrypt, Decrypt, or Exit.
   - **Encrypt**: Enter a directory to encrypt files within it.
   - **Decrypt**: Enter a directory to decrypt files within it.
   - **Exit**: Exit the script.
3. **File Processing**: The script will then perform the chosen operation and provide feedback.

## Requirements

- **GPG**: Ensure GPG is installed on your system.
- **Bash Environment**: The script runs in a Bash environment.

## Security Note

The script uses `shred` for secure deletion, which may not be effective on all file systems or SSDs.
