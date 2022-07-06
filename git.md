# Using git large file
## Installation
Download git lfs from [this link](https://github.com/git-lfs/git-lfs/releases/download/v2.9.0/git-lfs-linux-amd64-v2.9.0.tar.gz).

```bash
cd ~/Downloads
tar -xf git-lfs-linux-amd64-v2.9.0.tar.gz
chmod 755 install.sh
sudo ./install.sh
```

## Usage
```bash
git lfs install
git lfs track "*.m"
git add .gitattributes
```
