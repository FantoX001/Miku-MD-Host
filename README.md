# Host [Miku MD](https://github.com/FantoX001/Miku-MD) from here

### ✧✧ `Userland` Hosting guide (Android):

✧ Download UserLand app from Googlre Play Store. <br>
✧ Install Debial terminal using userland. <br>
✧ Install `wget` in Debian terminal using this following command: `sudo apt install wget` <br>

✧ Next copy and paste this command in your UserLand's Debian Terminal. <br>
```
wget -q0- https://raw.githubusercontent.com/FantoX001/Miku-MD-Host/main/installmiku.sh | bash
```
<br>
<br>

### ✧✧ How to stop bot:
```
ctrl+c
```

### ✧✧ How to start the bot again (Without closing the UserLand session):
```
npm start
```

### ✧✧ How to start the bot again (After closing the UserLand session):
```
cd Miku-MD
npm start
```

### ✧✧ How to change the session or get a new qr after logout:
```
cd Miku-MD
rm session.json
npm start
```

