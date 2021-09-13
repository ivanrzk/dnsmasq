dnsmasq


## How to disable systemd-resolved in Ubuntu
### Stages
- Disable and stop the systemd-resolved service:
```
  sudo systemctl disable systemd-resolved.service
  sudo systemctl stop systemd-resolved
```
Delete the symlink /etc/resolv.conf
```
  rm /etc/resolv.conf
```