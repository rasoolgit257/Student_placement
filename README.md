VSCODE:---- Docker: Add docker file to workspace

docker build -t aws_demo_deployment .

docker images
docker ps -a
docker run -d -p 5002:5002 aws_demo_deployment:latest 
docker stop $(docker ps -q) --- this will stop all running containers

sudo apt update
sudo apt install python3
sudo apt-get install python3-pip

sudo apt install python3-venv
python3 -m venv <ENV NAME>
source <ENV NAME>/bin/activate

sudo apt update
sudo apt upgrade -y
sudo apt install apt-transport-https ca-certificates curl software-properties-common
curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -
sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu $(lsb_release -cs) stable"
sudo apt update
sudo apt install docker-ce
docker --version

sudo usermod -aG docker $USER
newgrp docker

Now Bulid Docker App

Setup Security Groups > give our port number in bound groups






