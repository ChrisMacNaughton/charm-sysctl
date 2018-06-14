# Overview

```
juju deploy ubuntu
juju deploy sysctl --config="sysctls='---
net.ipv4.ip_forward: 1
vm.swappiness: 60'"
juju add-relation ubuntu sysctl
```