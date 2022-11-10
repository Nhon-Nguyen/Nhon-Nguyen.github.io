# Installing-Docker-on-Ubuntu-20.04
Install Docker on Ubuntu 20.04
For course projects, we will need access to a Docker installation. To install Docker on your private Ubuntu Server 20.04 VM, follow the steps outlined in the official Docker install instructions: 

https://docs.docker.com/engine/install/ubuntu/ 

Specific steps:
sudo apt update
sudo apt install ca-certificates curl gnupg lsb-release
curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo gpg --dearmor -o /usr/share/keyrings/docker-archive-keyring.gpg
echo "deb [arch=$(dpkg --print-architecture) signed-by=/usr/share/keyrings/docker-archive-keyring.gpg] https://download.docker.com/linux/ubuntu $(lsb_release -cs) stable" | sudo tee /etc/apt/sources.list.d/docker.list > /dev/null
sudo apt update
sudo apt install docker-ce docker-ce-cli containerd.io
sudo usermod -aG docker sysadmin
Install Docker Compose
Additionally, we will want to use Docker Compose. Install it by following the following instructions:

https://docs.docker.com/compose/install/linux/#install-using-the-repository

sudo apt-get update
sudo apt-get install docker-compose-plugin


Note: the old version of docker compose was a standalone program called docker-compose. The newer docker compose is a plugin/subcommand of the Docker program. This is a minor difference, but you may see examples online using "docker-compose" (v1) and some using "docker compose" (v2).
