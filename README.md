# NetworkWalks Internship – Week 1 Assignment
## Kali Linux Virtual Machine Setup and Network Configuration

This repository documents my Week 1 practical work for the NetworkWalks Company assignment. The work focuses on setting up a Kali Linux virtual machine in Oracle VirtualBox and checking its basic networking and integration settings.

## Objectives

- Set up and launch a Kali Linux virtual machine in VirtualBox.
- Configure the VM network adapter using NAT networking.
- Review the Kali Linux network configuration and IP address.
- Test internet connectivity from the Kali Linux terminal.
- Configure VirtualBox integration features, including shared clipboard, drag-and-drop, and a shared folder.
- Create a VirtualBox snapshot to preserve the configured VM state.

## Tasks Completed

### 1. VirtualBox and Kali Linux Setup
Prepared the Kali Linux virtual machine in Oracle VirtualBox and launched the Kali Linux desktop environment.

**Evidence:** `screenshots/01-virtualbox-kali.png`, `screenshots/06-kali-desktop.png`

### 2. NAT Network Configuration
Reviewed the VM's network settings and configured the network adapter to use NAT. NAT allows the guest VM to access external networks through the host's network connection in a typical VirtualBox setup.

**Evidence:** `screenshots/02-nat-network.png`

### 3. Kali Linux Network Settings
Reviewed the virtual machine's network adapter settings.

**Evidence:** `screenshots/03-kali-network-settings.png`

### 4. Shared Clipboard and Drag-and-Drop
Reviewed/configured VirtualBox shared clipboard and drag-and-drop options to support data transfer between the host operating system and the Kali Linux guest. Availability can depend on Guest Additions and the selected VirtualBox settings.

**Evidence:** `screenshots/04-clipboard-dragdrop.png`

### 5. Shared Folder
Reviewed/configured the VirtualBox shared-folder feature for exchanging files between the host and guest operating systems.

**Evidence:** `screenshots/05-shared-folder.png`

### 6. IP Configuration
Used terminal commands to inspect the Kali Linux network configuration and identify the assigned network address.

**Evidence:** `screenshots/07-ip-configuration.png`

### 7. Internet Connectivity Test
Ran a terminal-based connectivity test to check whether the Kali Linux VM could reach an external destination.

**Evidence:** `screenshots/08-internet-test.png`

### 8. VirtualBox Snapshot
Created or reviewed a VirtualBox snapshot so the VM can be returned to a saved state if needed. A snapshot is useful before making further lab changes.

**Evidence:** `screenshots/09-snapshot.png`

## Repository Structure

Keep the README and screenshots arranged like this:

```text
networkwalks-week-1/
├── README.md
└── screenshots/
    ├── 01-virtualbox-kali.png
    ├── 02-nat-network.png
    ├── 03-kali-network-settings.png
    ├── 04-clipboard-dragdrop.png
    ├── 05-shared-folder.png
    ├── 06-kali-desktop.png
    ├── 07-ip-configuration.png
    ├── 08-internet-test.png
    └── 09-snapshot.png
```

## Tools Used

- Oracle VirtualBox
- Kali Linux
- Linux terminal
- VirtualBox VM network and integration settings

## Learning Outcomes

Through this task, I practised basic virtual-machine setup, NAT networking, Linux network inspection, connectivity testing, host–guest file-sharing options, and snapshot management. These are foundational skills for building a safe cybersecurity practice lab.

## Notes

- The screenshots in this repository serve as evidence of the configuration steps.
- Shared clipboard, drag-and-drop, and shared folders may require VirtualBox Guest Additions and appropriate VM settings.
- NAT provides general outbound connectivity; it does not automatically make services running inside the VM directly reachable from other devices.
- Only test connectivity and security tools on systems and networks that I own or have explicit permission to use.

## Submission

**Assignment:** Week 1  
**Organization:** NetworkWalks Company  
**Topic:** Kali Linux VirtualBox Setup and Basic Network Configuration

---

*Prepared as part of my cybersecurity learning and practical lab documentation.*
