``` shell 
pacman -S xorg
```

vim /etc/ssh/sshd_config
X11Forwarding yes
X11UseLocalhost no

systemctl restart sshd
