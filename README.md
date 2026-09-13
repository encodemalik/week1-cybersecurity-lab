# Week 1 – Cybersecurity Lab Setup

## Objective
Set up a controlled cybersecurity testing environment using VirtualBox and Kali Linux.

## Lab Environment
- Hypervisor: Oracle VirtualBox
- Attacking machine: Kali Linux
- Network type: NAT Network
- Network: `10.0.0.0/24`
- Kali Linux IP: `10.0.0.2/24`
- Gateway: `10.0.0.1`
- DNS: `8.8.8.8`

## Work Completed
- Configured the VirtualBox NAT Network.
- Configured Kali Linux networking.
- Verified Kali's IP configuration.
- Verified Internet connectivity.
- Configured clipboard and drag-and-drop integration.
- Configured the host `/downloads` shared folder.
- Created a clean VM snapshot for lab recovery.

## Verification
Evidence screenshots are included in the `screenshots/` directory.

## Troubleshooting Notes
The lab guide notes that VirtualBox 7 with newer Kali releases can sometimes cause connectivity issues. Network configuration and connectivity were checked before proceeding with later practical exercises.

## Learning Outcome
This lab established an isolated and repeatable environment for authorized cybersecurity practice, including reconnaissance, scanning, enumeration and vulnerability-assessment exercises.

> All security testing is performed only against authorized lab systems and targets.
