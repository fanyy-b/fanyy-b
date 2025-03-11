# first inst

```
cd && \
    apt update && \
    apt full-upgrade -y && \
    apt install -y mc htop git sudo curl wget tmux gnupg apt-transport-https && \
    mkdir -p .ssh && \
    curl https://github.com/fanyy-b.keys >> ~/.ssh/authorized_keys
```

