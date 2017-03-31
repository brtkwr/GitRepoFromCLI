# Installation

## Ubuntu

```bash
git clone http://www.github.com/brtknr/GitRepoFromCLI
cd GitRepoFromCLI
chmod u+x git-mkrepo
mkdir ~/.local/bin
ln -rs git-mkrepo ~/.local/bin
echo 'export PATH=$PATH:~/.local/bin' >> ~/.bashrc
source ~/.bashrc
```

## macOS

```bash
git clone http://www.github.com/brtknr/GitRepoFromCLI
cd GitRepoFromCLI
chmod u+x git-mkrepo
mkdir ~/.local/bin
ln -rs git-mkrepo ~/.local/bin
echo 'export PATH=$PATH:~/.local/bin' >> ~/.bash_profile
source ~/.bash_profile
```

# One time `.netrc` configuration

Generate a [new access token]:(https://github.com/settings/tokens/new) and run the following to update your .netrc. You can also use your Github password but that is a really bad idea for obvious reasons.

```bash
machine api.github.com login USERNAME password TOKEN >> ~/.netrc
```

# Usage

```bash
mkdir ~/NewRepositoryFolder
cd ~/NewRepositoryFolder
git mkrepo
```

# Late realisation

Since I wrote this script, I now realise that there is a much more mature alternative over at http://github.com/github/hub which has a command called `git create` which does almost exactly the same thing. Ah well, I learnt a lot about bash scripting.