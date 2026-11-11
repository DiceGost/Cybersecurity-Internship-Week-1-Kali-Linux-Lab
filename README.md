# Cybersecurity Internship — Week 1: Kali Linux Lab Setup

**Program:** Networkwalks Cybersecurity Internship  
**Module:** Week 1 — Practical Lab Environment Setup  
**Status:** Documentation started; practical setup verification pending

## Objective
Build an isolated cybersecurity practice environment using Oracle VirtualBox and a Kali Linux virtual machine, following the Week 1 project brief.

## Lab requirements
- [ ] Install the latest VirtualBox version
- [ ] Import the latest Kali Linux virtual machine
- [ ] Create a NAT Network using `10.0.0.0/24`
- [ ] Set Kali Linux's IP address to `10.0.0.2/24`
- [ ] Enable shared clipboard and drag-and-drop
- [ ] Configure a shared folder mapped to the host's Downloads folder
- [ ] Verify internet connectivity inside Kali Linux
- [ ] Create a snapshot of the working virtual machine

> These are project requirements, **not claims of completion**. Check off steps only after verifying them.

## Intended network architecture
```text
Host laptop / desktop
└── Oracle VirtualBox
    └── NAT Network: 10.0.0.0/24
        └── Kali Linux VM: 10.0.0.2/24
```

## Evidence to add
Add your own screenshots under `screenshots/` after completing the setup:
1. Running Kali Linux VM in VirtualBox
2. NAT Network configuration
3. Kali IP configuration (`ip addr`)
4. Internet connectivity test
5. Shared clipboard / shared folder settings
6. Snapshot in VirtualBox

**Privacy:** Blur personal identifiers, tokens, passwords and other sensitive details before uploading screenshots.

## Troubleshooting log
Record any errors you personally encountered, the fixes you tried, and whether they worked. Do not invent results.

## Resources
- [VirtualBox downloads](https://www.virtualbox.org/wiki/Downloads)
- [Kali Linux](https://www.kali.org/get-kali/)
- [Networkwalks](https://networkwalks.com/)

## Notes
This repository is a work-in-progress learning record. It should be updated with verified screenshots and findings before being presented as a completed lab.
