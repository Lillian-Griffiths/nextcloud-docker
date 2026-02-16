# nextcloud-docker

This is a simple cloud storage solution using Docker, Nextcloud, and MariaDB.

# Prereqs and Required Files
`Docker`

`Docker Compose`

`.env`

`compose.yml`

# Deployment and setup

```
git clone https://github.com/Lillian-Griffiths/nextcloud-docker.git

cd nextcloud-docker

docker compose up -d
```
Access the web interface at your server's IP:8080. 

The default admin credentials are admin and password. The credentials for the Database Configuration setting are nextcloud, password, nextcloud, and db, in that order. All credentials can be viewed and modified in the .env file.

Click install

Setup Complete!

Warning: This is an insecure setup and only suitable for a lab environment. Beware that this setup is internet facing and not secured for actual use.
