# Day-2: Authentication Log Aaalysis

🎯 **Objective:**  
Analyze a log file on a Linux (Ubuntu) Virtual Machine using basic CLI tools.

---

🛠️ **Procedure:**

**Step 1: Install Ubuntu on VirtualBox**  
- Download the Ubuntu ISO image from the official site: [https://ubuntu.com/download](https://ubuntu.com/download)  
- Open VirtualBox and create a new virtual machine.  
  - **Name:** Ubuntu Log Analysis  
  - **Type:** Linux | **Version:** Ubuntu (64-bit)  
  - Assign memory (e.g., **2048 MB**) and create a virtual hard disk (e.g., **20 GB**).  
- Start the VM, load the ISO, and install Ubuntu.

---

**Step 2: Login to the Ubuntu Machine**  
- Use your credentials to log in to the Ubuntu desktop or terminal interface.

---

**Step 3: Download the sample log file**  
```bash
wget https://raw.githubusercontent.com/0xrajneesh/challenge-resource/refs/heads/main/auth.log_2.log -O /var/log/auth.log_2.log
```
** Step 4: View the log file

```
cat /var/log/auth.log_2.log
```
