# Linux-Server-Project

This project focuses on setting up a DNS server and an FTP server using Linux Ubuntu 18.04. The objective was to simulate file transfer and domain resolution between two Linux systems in a controlled internal network environment using VirtualBox.

[View Full Project Report (PDF)](Linux_Project.pdf)

## Project Highlights
- Installed and configured Bind9 DNS service.
- Set up a vsftpd FTP server for file sharing.
- Connected two Ubuntu systems using an internal network setup.
- Verified DNS resolution and FTP file transfers using Filezilla and terminal commands.

---

## Key Outcomes
- Successfully configured a working DNS server on Linux Ubuntu.
- Set up FTP services allowing secure file sharing between devices.
- Achieved domain-based communication, reducing dependency on static IP addresses.
- Validated the setup through practical tests using Filezilla and terminal-based transfers.

---

## Tools Used
- Oracle VirtualBox
- Linux Ubuntu 18.04
- Windows 11
- Filezilla FTP Client
- Cisco Packet Tracer (for basic simulation references)

---

## Project Steps

### 1. DNS Server Configuration
Installed Bind9 on the server machine and configured the DNS service. Set up the server's IP address manually and modified DNS settings to create a functioning domain name server for the internal network.

![DNS Setup](ss/bind9.png)
> **Figure 2:** Bind9 DNS service configuration and network adapter setup.

Setup the DNS server in the interface
![DNS Setup](ss/DNS_config.png)
> **Figure 3:** Setup the DNS service interface.


---

### 4. FTP Server Setup
Installed and configured the vsftpd FTP server on the Linux server. Edited the FTP configuration file, created a dedicated FTP user, and set appropriate access permissions.

![FTP Setup](images/ftp-configuration.png)
> **Figure 4:** vsftpd FTP server installation and user configuration.

---

### 5. Testing and Verification
Tested DNS server functionality by pinging the server using the configured domain name. Verified FTP services by logging into the server via Filezilla and transferring files successfully.

![Testing FTP and DNS](images/testing.png)
> **Figure 5:** Successful DNS resolution and FTP file transfer between server and client.

---

> _"Automating server configurations for a seamless digital experience."_
