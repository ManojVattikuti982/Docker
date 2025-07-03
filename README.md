<h1 align="center">🚀 DOCKER INSTALLATION</h1>
<h3 align="center">Setup Docker on Amazon Linux 2</h3>

---

## 📌 Docker Installation Steps

```bash
sudo yum update -y
sudo yum install -y docker
sudo systemctl enable docker
sudo systemctl start docker
sudo systemctl status docker
docker --version
sudo yum install -y git
# Install Docker Compose
sudo curl -L https://github.com/docker/compose/releases/download/1.22.0/docker-compose-$(uname -s)-$(uname -m) -o /usr/local/bin/docker-compose
sudo chmod +x /usr/local/bin/docker-compose
docker-compose --version
```


---

##<h1 align="center">📦 DOCKER TASK</h1>
<h3 align="center">Run, Stop, and Remove HTTPD Container</h3>

---

### 📌 Task Steps

> Pull one `httpd` image from Docker Hub,  
> Run a container,  
> Stop the container,  
> Remove the container,  
> And remove the Docker image.

---

### 📋 Docker Task Commands

```bash
docker ps
docker ps -a
docker images
docker pull httpd
docker images
docker run -it -d httpd
docker ps
docker inspect 4e7c9f04be92
docker ps
docker stop 4e7c9f04be92
docker ps
docker start 4e7c9f04be92
docker ps
docker stop 4e7c9f04be92
docker rm 4e7c9f04be92
docker ps -a
docker images
docker rmi httpd
docker images
```


