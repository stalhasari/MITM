---

# MITM (Man-in-the-Middle) Attack

This Python script allows you to perform a Man-in-the-Middle (MITM) attack on a local network. It utilizes ARP (Address Resolution Protocol) poisoning to intercept traffic between a target machine and the gateway.

## Prerequisites

- **Python 3**: Make sure you have Python 3 installed on your system.
- **Scapy**: This script depends on Scapy library for crafting and sending packets. You can install it via pip:
  ```
  pip install scapy
  ```

## Usage

1. Run the script with Python 3.
   ```
   python mitm.py -t <target_ip> -g <gateway_ip>
   ```

2. Provide the IP addresses of the target machine (`-t` or `--target`) and the gateway (`-g` or `--gateway`).

3. The script will begin ARP poisoning, intercepting traffic between the target and the gateway.

4. Press `Ctrl + C` to stop the attack and reset the ARP tables.

**Note:** Use this script responsibly and only on networks you have permission to test.

---
