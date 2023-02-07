# sshfs

```bash
cat mount-myjenkins.sh
#!/bin/bash

sshfs -C -o rw,uid=5003,allow_other root@myjenkins:/  $PWD/myjenkins


# centos 8
dnf --enablerepo=powertools -y install fuse-sshfs 
```
