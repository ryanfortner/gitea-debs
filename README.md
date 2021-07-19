# Gitea Debian Repository

This is a simple Debian repository for the Gitea project, a self-hosted Git solution.

### Repository installation
Involves adding .list file and gpg key for added security.
```
sudo wget https://gitea.armlinux.ml/gitea.list -O /etc/apt/sources.list.d/gitea.list
wget -qO- https://gitea.armlinux.ml/gitea-debs/KEY.gpg | sudo apt-key add -
sudo apt update && sudo apt install gitea-y
```

