# Installing Docker Centos 8

> Centos is a good distribution to work on with `docker`, docker support 2 version of CentOS 7 and 8, and the Archived versions are not supported.

## Road Map

- Prerequisites
- Uninstall old version
- Installation Methods
- Uninstall of Docker Engine

## Prerequisites

- a working installation of CentOS 8
- A user account with sudo privellages
- Terminal Access (SSH)
- DNF software packahe instakker (Included by default)
- The Firewall manager disabled

> Important: The firewalld manager in Centos 8 prevents DNS resolution within docker containers.

### Disaple firewalld on CentOS 8

One simple command is enough to disable firewalld in CentOS 8:

```{SSH}
sudo systemctl disable firewalld
```

