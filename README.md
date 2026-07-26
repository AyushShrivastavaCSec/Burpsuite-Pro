# Burpsuite-Pro
Step-by-step guide to install Burp Suite Professional on Kali Linux.

# Burp Suite Professional Installation Guide (Kali Linux)

## Step 1: Update System Packages

Before starting the installation, update the system package list.

```bash
sudo apt update
```

---

## Step 2: Download JDK 21

1. Open **Firefox**.
2. Search for **JDK 21**.
3. Open the **Java SE 21 Archive Downloads** page.
4. Scroll down to **Java SE Development Kit 21.0.11**.
5. Download the package according to your system.
6. For Kali Linux (64-bit), download:

**Linux x64 Debian Package (.deb)**

---

## Step 3: Install JDK 21

Open the terminal and navigate to the **Downloads** directory.

```bash
cd ~/Downloads
ls
sudo dpkg -i jdk-21.0.11_linux-x64_bin.deb
```

---

## Step 4: Install Burp Suite Professional

Run the following command in the terminal:

```bash
sudo apt update && sudo apt install -y wget && wget -qO- https://raw.githubusercontent.com/xiv3r/Burpsuite-Professional/main/install.sh | sudo bash
```

## Step 5: Launch Burp Suite Professional

After the installation is complete, launch Burp Suite Professional.

1. The **License Agreement** window will appear.
2. Read the terms and click **I Accept** to continue.

### Screenshot

![License Agreement](screenshots/step5-license-agreement.png)

*Figure 5: Burp Suite Professional License Agreement.*

## Step 6: Enter Your License

After accepting the license agreement, Burp Suite will prompt you to enter a valid license key.

1. Enter your **valid Burp Suite Professional license key**.
2. Click **Next** to continue with the setup.

### Screenshot

![Enter License Key](screenshots/step6-enter-license.png)

*Figure 6: Enter your Burp Suite Professional license key.*
