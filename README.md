<p><img src="https://assets.ubuntu.com/v1/15971bf5-cloud-init-primary.svg" alt="cloud-init-logo" title="cloud-init" align="top" height=70 /></p>

*Cloud-init is the industry standard multi-distribution method for cross-platform cloud instance initialisation. It is supported across all major public cloud providers, provisioning systems for private cloud infrastructure, and bare-metal installations.*

### General informations

This repository contains Cloud-Init profiles to setup applications on LXD server.

#### Requirements

* LXD >= 5.0
* Cloud-Init installed in instances

### How to use these profiles ?

```shell
lxc launch ubuntu/22.04 myinstance -c cloud-init.user-data="$(cat myprofile.yml)" [options]
```

### References

* LXD : https://linuxcontainers.org/lxd/introduction/
* Cloud-Init : https://cloudinit.readthedocs.io/en/latest/
