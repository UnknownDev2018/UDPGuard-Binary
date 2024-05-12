
---

## Installation Guide for UDPGuard with HYSTERIA + SlowDNS

This guide provides step-by-step instructions to install UDPGuard with DNS-TT integration on your system. Follow these steps to ensure a successful installation.

### Prerequisites

Before starting the installation, ensure your system is up to date:

```bash
sudo apt update -y && sudo apt upgrade -y && sudo apt dist-upgrade -y
```

### Download and Install UDPGuard

1. **Download the Installation Script**

   Use `wget` to download the latest version of the UDPGuard installation script:

   ```bash
   wget -c "https://raw.githubusercontent.com/UnknownDev2018/UDPGuard-Binary/main/Install_DNSTT-UDPGuard" -O Install_DNSTT_UDPGuard
   ```

2. **Make the Script Executable**

   Change the permission of the downloaded script to make it executable:

   ```bash
   chmod +x Install_DNSTT_UDPGuard
   ```

3. **Set Environment Variable**

   Set the required environment variable `AUTH_TOKEN`:

   ```bash
   export AUTH_TOKEN=UDPGuardDEVsidev6
   ```

4. **Run the Installation Script**

   Execute the script to start the installation process:

   ```bash
   ./Install_DNSTT_UDPGuard
   ```

### Completion

Once the installation is complete, your system will be equipped with UDPGuard, configured to enhance your network security and performance.

For any issues during installation, refer to the troubleshooting section or contact support.


https://t.me/webtunnelvpn2023


---
