# termux converter video YouTube to mp3 

install termux https://play.google.com/store/apps/details?id=com.termux

### ควรเข้าโฟรเดอร์ที่ต้องการเก็บmusicไว้ก่อน
### และนำเข้าscript python

### install command

```bash
apt update && apt upgrade 
```

### install git 

```bash
apt-get install git
```

### install python

```bash
apt install python3
```

### INSTALL YOUTUBE_DL

```bash
pip install youtube_dl
```
### CLONE GITHUB
```bash
git clone https://github.com/HT002/termux-yt-dl.git
```
### IMPORT SCRIPT 
```bash
cd termux-yt-dl
```

### การนำเข้าmusicไปยังstorage

### install storage
```bash
termux-setup-storage
```
### เช็คว่ามีstorageไหม
```bash
ls
```
### นำเข้าstorage

```bash
cd storage
```
### และนำเข้าตามที่มี
<img src="https://github.com/HT002/manage-files/blob/main/IMG/Screenshot_20220209-122731_1.png">
