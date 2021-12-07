# Gitea Debian Repository

### Repository is no longer supported: use https://raspbian-addons.org instead

This is a simple Debian repository for the Gitea project, a self-hosted Git solution.

### Repository installation
Involves adding .list file and gpg key for added security.
```bash
sudo wget https://ryanfortner.github.io/gitea-debs/gitea.list -O /etc/apt/sources.list.d/gitea.list
wget -qO- https://ryanfortner.github.io/gitea-debs/KEY.gpg | sudo apt-key add -
sudo apt update && sudo apt install gitea -y
```

