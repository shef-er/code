# code

## setup

```shell
sudo pacman -S code

# for Code - OSS
git clone git@github.com:shef-er/code.git ~/.config/Code\ -\ OSS/User

# for VSCodium
git clone git@github.com:shef-er/code.git ~/.config/VSCodium/User

# for VS Code
git clone git@github.com:shef-er/code.git ~/.config/Code/User
```

## extensions

```
# List currently installed extensions
code --list-extensions

# Theme
code --install-extension monokai.theme-monokai-pro-vscode

# Code completion
code --install-extension christian-kohler.path-intellisense
code --install-extension christian-kohler.npm-intellisense
code --install-extension mikestead.dotenv
code --install-extension redhat.vscode-xml
code --install-extension redhat.vscode-yaml

# Phpactor
wget https://github.com/phpactor/vscode-phpactor/releases/latest/download/phpactor.vsix
code --install-extension phpactor.vsix

# Highlight and format
code --install-extension EditorConfig.EditorConfig
code --install-extension esbenp.prettier-vscode
code --install-extension ibm.output-colorizer

# Docker
code --install-extension ms-azuretools.vscode-docker
```

## Optional extensions

```
# Python
code --install-extension ms-python.python

# Golang
code --install-extension golang.go

# K8S
code --install-extension ms-kubernetes-tools.vscode-kubernetes-tools

# Database tools
code --install-extension mtxr.sqltools
code --install-extension mtxr.sqltools-driver-mysql
code --install-extension mtxr.sqltools-driver-sqlite
```
