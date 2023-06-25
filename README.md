# users-api

```bash
git clone https://github.com/laxmipriyapattanayak/users-api.git

wget https://nodejs.org/dist/v18.16.1/node-v18.16.1-linux-x64.tar.xz

tar -xvf node-v18.16.1-linux-x64.tar.xz

cd /home/ubuntu/users-api
#change the USER, PASSWORD and HOST details in start.sh by following vi editor tips 

vi start.sh 
# press i for edit mode
# make the change
# press :
# wq! and press enter , for save and exit from vi editor
/home/ubuntu/node-v18.16.1-linux-x64/bin/node /home/ubuntu/node-v18.16.1-linux-x64/bin/npm install

sudo cp usersapi.service /etc/systemd/system/

sudo systemctl daemon-reload
sudo systemctl start usersapi.service
sudo systemctl status usersapi.service
sudo systemctl enable usersapi.service

```
