### ssh-keygen
```
ssh-keygen -t rsa -b 4096 -f ~/.ssh
```

### ssh connection
```
Host rsf
    HostName xxxxxx.com
    User root
    Port 22
    IdentityFile ~/.ssh/xxxxxx
    StrictHostKeyChecking no
    UserKnownHostsFile=/dev/null
```
