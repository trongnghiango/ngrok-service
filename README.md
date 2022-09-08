# ngrok-service
Aid to start ngrok on boot

```sh
git clone https://github.com/trongnghiango/ngrok-service.git
wget https://bin.equinox.io/c/bNyj1mQVY4c/ngrok-v3-stable-linux-amd64.tgz
tar -xzf ngrok-v3-stable-linux-amd64.tgz
./ngrok config add-authtoken 2E9skjfksjkfsjkfjksfjsk
sudo chmod +x /home/ubuntu/ngrok-service/scripts/service-installer.sh
sudo /home/ubuntu/ngrok-service/scripts/service-installer.sh
```
