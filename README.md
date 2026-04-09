# Update VS Code without dnf

```bash
# 1. Download the latest VS Code: RPM package
cd /tmp
wget "https://code.visualstudio.com/sha/download?build=stable&os=linux-rpm-x64" -O code-latest.rpm

# 2. Install/upgrade using rpm (this will upgrade if already installed)
sudo rpm -Uvh code-latest.rpm
```
