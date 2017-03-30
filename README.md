# Installation

```bash
git clone http://www.github.com/brtknr/GitRepoFromCLI
cd GitRepoFromCLI
chmod u+x makeRepo
ln -s makeRepo ~/.local/bin
echo 'export PATH=$PATH:~/.local/bin' >> ~/.bashrc
source ~/.bashrc
```

# Usage

```bash
mkdir ~/NewRepositoryFolder
cd ~/NewRepositoryFolder
makeRepo
```
