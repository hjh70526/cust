```
mount -t tmpfs -o size=100% rootfs /media
wget -O- https://github.com/cnddy/cust/raw/master/rootfs.tgz|tar -xz -C /media
systemctl switch-root /media /init
```
