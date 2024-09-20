# Node Js installation guide in ubuntu (using NVM- Node Version Manager)

### Update Installation drivers 
```bash 
    sudo apt update
```
### Install NVM using curl
- Remove [|bash] sign to make sure it don't change anythin which you don't want (optional)
- To make sure it is getting installed properly it is recomended that to use [|bash] at the end of the command
```bash 
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.3/install.sh | bash
```

### After the installation you want to use that so for that you must first source your [.bashrc]file:
```bash
    source ~/.bashrc
```

### Now You can list out golably available versions of NVM 
```bash
nvm list-remote
```

### Select specific version run this command
- [You can replace v14.10.0 as per your required version]
```bash
    nvm install v14.10.0
```

### To List out installed version in your Device
```bash
nvm list
``` 

### To switch in another version of node which is already installed in your device
- [You can replace v14.10.0 as per your required version]
```bash
nvm use v14.10.0
```
- [to check current verion of node]
- ```bash node -v ```

