The Markdown Resume
===================

### Instructions
```bash
git clone https://github.com/mszep/pandoc_resume
cd pandoc_resume
vim markdown/resume.md   # insert your own resume info
make
```

### Running Dockerized
```bash
git clone https://github.com/mszep/pandoc_resume
cd pandoc_resume
vim markdown/resume.md   # insert your own resume info
docker-compose up -d
```

### Requirements

* ConTeXt 0.6X
* pandoc 2.x
    * 1.x is deprecated

Last tested on the above versions and that's not to say the later versions won't work. Please try to use the latest versions when possible.

#### Debian / Ubuntu

```bash
sudo apt install pandoc context
```

#### Fedora
```bash
sudo dnf install pandoc texlive-collection-context
```

#### Arch
```bash
sudo pacman -S pandoc texlive-core
```

#### OSX
```bash
brew install pandoc
brew cask install mactex
```
