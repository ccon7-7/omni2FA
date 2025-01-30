# Privacy Policy for omni2FA

Last Updated: [Current Date]

## Overview
omni2FA is a browser extension designed to generate two-factor authentication (2FA) codes directly in your browser. We take your privacy and security seriously, and this policy explains how your data is handled.

## Data Collection and Storage

### What We Collect
- 2FA secret keys that you input or scan
- Basic extension settings and preferences
- No personal information is collected or required

### How Data is Stored
- All sensitive data is encrypted using AES-GCM 256-bit encryption
- Encrypted data is stored locally in your browser using Chrome's storage API
- A unique encryption key is generated for each installation
- If Chrome Sync is enabled, encrypted data may be synced across your Chrome browsers

### What We Don't Collect
- We do not collect any usage statistics
- We do not track user behavior
- We do not transmit data to external servers
- We do not store any unencrypted sensitive information

## Data Usage

### Local Processing
- All code generation happens locally in your browser
- No network connections are required for normal operation
- QR code scanning is performed locally
- All cryptographic operations use Chrome's Web Crypto API

### Chrome Sync
- If you enable Chrome Sync, your encrypted data may be synchronized across your Chrome browsers
- This synchronization is handled by Chrome's built-in sync system
- We have no access to this synchronized data

## Permissions

The extension requires minimal permissions:
- `storage`: To save your encrypted 2FA secrets
- `activeTab`: To enable QR code scanning
- `scripting`: For basic extension functionality

## Data Security

### Encryption
- All sensitive data is encrypted using AES-GCM 256-bit encryption
- Encryption keys are unique per installation
- Keys are securely stored using Chrome's local storage
- No plain text secrets are ever stored

### Export and Backup
- Exported backup files contain encrypted data
- Users are responsible for securing their backup files
- We recommend storing backups securely

## Third-Party Services

- This extension does not use any third-party services
- No data is shared with third parties
- No analytics or tracking tools are implemented

## User Rights and Control

You have the right to:
- Export your data at any time
- Delete all stored data
- Control Chrome Sync settings
- Uninstall the extension and remove all associated data

## Chrome Sync Considerations

If you use Chrome Sync:
- Your encrypted data may be synchronized across your Chrome browsers
- Security depends on your Chrome account's security
- We recommend enabling 2FA on your Chrome account
- You can disable Chrome Sync for this extension in Chrome's settings

## Changes to Privacy Policy

- We reserve the right to update this privacy policy
- Significant changes will be communicated through the extension's update notes
- Continued use of the extension after changes implies acceptance

## Data Deletion

To remove your data:
1. Uninstall the extension
2. Clear Chrome's storage data
3. If using Chrome Sync, remove extension data from sync

## Contact

For privacy-related questions or concerns:
- GitHub Issues: [Your GitHub Repository URL]
- Email: [Your Contact Email]

## Recommendations for Users

We recommend:
- Maintaining separate backups of 2FA secrets
- Using strong passwords for your Chrome account
- Enabling 2FA on your Chrome account if using sync
- Storing backup files securely
- Regularly reviewing your security settings

## Disclaimer

While we implement strong security measures, the security of your data also depends on:
- Your Chrome browser's security
- Your computer's security
- Your Chrome account's security (if using sync)
- How you handle exported backup files

## License

This extension is open source and licensed under [Your License]. The source code is available for review at [Your GitHub Repository URL].
