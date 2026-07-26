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

### Step 5: Update the License Name

In the **License Text** field, replace the default name with your own system or username.

**Example:**

Before:
License to h3ll0w0rld

After:
License to dynoking

### Output
![Burp Suite Screenshot](WhatsApp%20Image%202026-07-26%20at%204.35.57%20AM.jpeg)

*Figure 5: Burp Suite Professional initial setup screen.*
