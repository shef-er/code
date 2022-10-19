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

```shell
# Theme
code --install-extension monokai.theme-monokai-pro-vscode

# Language support and code completion
code --install-extension christian-kohler.path-intellisense
code --install-extension christian-kohler.npm-intellisense
code --install-extension dotenv.dotenv-vscode
code --install-extension golang.go
code --install-extension ms-python.python
code --install-extension ms-vscode.vscode-typescript-next

# Highlight and format
code --install-extension EditorConfig.EditorConfig
code --install-extension esbenp.prettier-vscode
code --install-extension ibm.output-colorizer

# Docker
code --install-extension ms-azuretools.vscode-docker

# K8S
code --install-extension ms-kubernetes-tools.vscode-kubernetes-tools

# Database tools
code --install-extension mtxr.sqltools
code --install-extension mtxr.sqltools-driver-mysql
code --install-extension mtxr.sqltools-driver-sqlite

# Check installed extensions
code --list-extensions
```

### phpactor extension

```
wget https://github.com/phpactor/vscode-phpactor/releases/latest/download/phpactor.vsix
code --install-extension phpactor.vsix
```
