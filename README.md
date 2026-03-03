# Neovim Setup

## Install Scoop
https://scoop.sh/
```powershell
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser
Invoke-RestMethod -Uri https://get.scoop.sh | Invoke-Expression
```

## Install Neovim
```powershell
scoop install neovim
nvim --version
```

## Install Lazy Prerequisite
```powershell
scoop install git
```

## Copy the repo
```powershell
git clone https://github.com/PPKan/nvim.git ~/.config/nvim
```

## Install neovim to VSCODE
Just install the neovim extension in VSCODE it will do the work automatically.