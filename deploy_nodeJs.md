# Node Js Deplyment After successfull installation of required nodejs version

### Update Installation drivers 
```bash 
    sudo apt update
```
### Install PM2 Gobally
- Install this globally Open Terminal anywhere in your system and run this command
```bash 
    sudo npm install pm2@latest -g
```

### After the installation you have to setup the file which you want to run on pm2 . for that you have to run this command
```bash
    pm2 start pathofyourstartingfileofproject.js
```

### Now Let's setup it so it will runs automatically on restart also
```bash
    pm2 startup systemd
```

