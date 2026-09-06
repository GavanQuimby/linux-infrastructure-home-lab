# Day 2 — Ubuntu Server Deployment

## Objective

Deploy the first Linux server for the Linux Infrastructure Home Lab using a virtual machine.

## Virtualization

**Hypervisor:** VirtualBox

## Server

**Hostname:** LAB-WEB01
**Operating System:** Ubuntu Server LTS
**CPU:** 2 cores
**Memory:** 4 GB
**Storage:** 30 GB
**Network:** NAT

## Configuration

The server was configured with:

* Ubuntu Server LTS
* OpenSSH Server
* DHCP network configuration
* Local administrative user
* System updates

## Initial Testing

The following commands were used to verify the installation:

```bash
whoami
hostname
ip addr
ip route
ping -c 4 google.com
```

## Result

The Ubuntu Server installation was completed successfully and network connectivity was verified.

## Next Steps

* Learn Linux filesystem navigation
* Configure users and permissions
* Configure SSH remote administration
* Configure static networking
* Deploy Nginx
* Implement firewall and security controls
