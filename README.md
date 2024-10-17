# ansible-macos

<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/f/fa/Apple_logo_black.svg/391px-Apple_logo_black.svg.png" alt="apple_logo" width="300"/>

This repository contains Ansible files to automate the setup and configuration of my macOS environment. It includes the installation of various packages and tools, as well as the cloning of my [neovim](https://github.com/dme86/neovim) and [fish](https://github.com/dme86/fish) configuration files.

## Prerequisites

todo

## Installation

All systems:
```shell 
ansible-playbook main.yml -e "setup_type=common"
```

Private setup:
```shell
ansible-playbook main.yml -e "setup_type=private"
```

