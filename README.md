# Implementing an IDS-IPS with Snort

1. To ensure system is up to date, I run the following commands to update system.

![update ](https://github.com/user-attachments/assets/8bf6bf98-f189-47bd-a2cd-7b23cbee1306)

![upgrade](https://github.com/user-attachments/assets/1d337ea7-70f8-4ada-abc1-c6e081578efc)

2. Updated the depencecies.

![dependency update](https://github.com/user-attachments/assets/337f93a9-7e5a-4a80-b9ca-68a909843d35)

3. Downloaded snort source code. (version 2.9.20)

![snort 2  9 download](https://github.com/user-attachments/assets/2c6ab334-434d-4d98-af15-4980015ca9dd)

4. Extracted the downloaded file.

![extracted snort](https://github.com/user-attachments/assets/aa4202a9-723b-4ab2-8765-fa0488af332b)

5. Compiled and installed Snort.
   
![change Dir](https://github.com/user-attachments/assets/2df0cd80-54d4-4456-80dc-37442baf2471)

![compiled and installed snort](https://github.com/user-attachments/assets/635778bc-af85-4fca-9d5e-ec2fc3b3338c)

6. Verified installation.

![checked installaton of snort](https://github.com/user-attachments/assets/0aec6d31-63b5-479d-a90c-65c1f830a1ad)

7. Downloaded Snort Rules through registration and downloading Free community rules.

![community rules](https://github.com/user-attachments/assets/8eb9e401-cb90-4687-9537-29bb396ad786)

8. Unpacked community rules

![unpacked community rules and copied to etc files](https://github.com/user-attachments/assets/940f97b9-3472-43c0-af7a-3bd3ff532696)

9. Opened and configured the snprt configuration file with nano command setting Network variables and ensuring rule pathss are correct and the community files included.

![confirgured Etc file](https://github.com/user-attachments/assets/f8bd4013-9c45-4afb-b321-8fca01dd8ac0)
![included community rules](https://github.com/user-attachments/assets/b4200b62-7bad-49d8-a2fd-191285586e62)

10. Tested the configuration and Run snort in IDS mode with the commands listed in screenshot.

![running snort to test](https://github.com/user-attachments/assets/8c3262a1-5c74-4bdd-b2ac-5ad7c36fba8d)

![Running snort in IDS Mode](https://github.com/user-attachments/assets/6b5440d9-7c92-4de9-b9ee-ed16d9b83efb)

    - A console : Prints Alerts to the console
    - q: Quiet mode( less verbose output)
    - c /etc/snort/snort.conf: specfies the configuration file.
    - i enp0s3: specifies the network interface to monitor.


 **Tools Used**
 
Ubuntu Server, Snort 
