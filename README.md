![Docker Installation](./docker-installation-guide.png)

# 🚀 DOCKER INSTALLATION

### Setup Docker on Amazon Linux 2

## 📌 Docker Installation Steps

```bash
sudo yum update -y
sudo yum install -y docker
sudo systemctl enable docker
sudo systemctl start docker
sudo systemctl status docker
docker --version

# Optional: Install Git
sudo yum install -y git

# Install Docker Compose
sudo curl -L "https://github.com/docker/compose/releases/download/1.22.0/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose
sudo chmod +x /usr/local/bin/docker-compose
docker-compose --version
