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

## Step 5: Complete the Initial Setup

After launching Burp Suite Professional, complete the initial setup by following the on-screen instructions.

Once the setup is complete, the application will proceed to the next screen.

### Output

![Initial Setup Completed](screenshots/step5-output.png)

*Figure 5: Burp Suite Professional initial setup screen.*
