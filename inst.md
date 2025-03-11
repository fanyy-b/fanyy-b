# ssh keys

```
cd && \
    apt update && \
    apt purge -y nano && \
    apt install -y vim mc htop git sudo curl wget gnupg apt-transport-https && \
    mkdir -p .ssh && \
    curl https://github.com/ondrejsika.keys >> ~/.ssh/authorized_keys
```
