# Linux customizations (config files & scripts)

## Setup
***TODO:*** Make a functional setup script using
[`setup/setup_custom_linux`](setup/setup_custom_linux)

```bash
#!/bin/bash

#Clone repo:
cd
git clone https://github.com/alainman-krh/custom_linux .custom_linux


cd
path_cfg=~/.custom_linux/config
ln -s $path_cfg/bashrc .bashrc
ln -s $path_cfg/vimrc .vimrc
ln -s $path_cfg/gitconfig .gitconfig
```

## [`bin/` directory](bin/)
***TODO:*** Populate [`bin/` directory](bin/) from sample script.

# Windows customizations
See [z_custom_windows/](z_custom_windows/) subdirectory.
