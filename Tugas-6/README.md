SSH ROOT
![alt text](ssh.png)

sudo apt update && sudo apt upgrade -y
![alt text](image.png)

sudo fallocate -l 2G /swapfile
sudo chmod 600 /swapfile
sudo mkswap /swapfile
sudo swapon /swapfile
![alt text](image.png)

cat /etc/fstab
![alt text](image-1.png)

free -h
![alt text](image-2.png)

Swap = `backup RAM`
Bukan buat nambah performa, tapi biar server tidak crash
Kalau swap sering kepakai → tanda harus upgrade RAM