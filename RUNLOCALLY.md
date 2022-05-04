curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh | bash
login/logout
nvm install 14

curl -o- https://go.dev/dl/go1.18.1.linux-amd64.tar.gz
rm -rf /usr/local/go && tar -C /usr/local -xzf go1.18.1.linux-amd64.tar.gz

Add export PATH=$PATH:/usr/local/go/bin to ~/.bashrc

login/logout

sudo mkdir /data
sudo chown $USERNAME /data

Run Portainer:
yarn start:toolkit
