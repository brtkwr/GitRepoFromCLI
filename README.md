# Installation

## Ubuntu

```bash
git clone http://www.github.com/brtknr/GitRepoFromCLI
cd GitRepoFromCLI
chmod u+x git-mkrepo
mkdir ~/.local/bin
ln -s git-mkrepo ~/.local/bin
echo 'export PATH=$PATH:~/.local/bin' >> ~/.bashrc
source ~/.bashrc
```

## macOS

```bash
git clone http://www.github.com/brtknr/GitRepoFromCLI
cd GitRepoFromCLI
chmod u+x git-mkrepo
mkdir ~/.local/bin
ln -s git-mkrepo ~/.local/bin
echo 'export PATH=$PATH:~/.local/bin' >> ~/.bash_profile
source ~/.bash_profile
```

# Usage

```bash
mkdir ~/NewRepositoryFolder
cd ~/NewRepositoryFolder
git mkrepo
```