# pyenv 
> https://github.com/pyenv-win/pyenv-win
## 1 安装 
```shell
## 使用powershell
Invoke-WebRequest -UseBasicParsing -Uri "https://raw.githubusercontent.com/pyenv-win/pyenv-win/master/pyenv-win/install-pyenv-win.ps1" -OutFile "./install-pyenv-win.ps1"; &"./install-pyenv-win.ps1"
``` 
**安装后检查** :
```shell
pyenv --version

```

## 2 使用
1. 查看可安装列表 : ` pyenv install --list `
2. 查看安装过的列表 : ` pyenv versions `
3. 安装某个版本   : ` pyenv install 3.12.0 `
4. 设置/查看当前目录的python版本 : ,` pyevn local 3.12.0 ` , ` pyenv local `  
