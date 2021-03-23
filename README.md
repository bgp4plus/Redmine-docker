# Redmine-docker
## How to use
1. Install docker and docker-compose
```
curl -L get.docker.com | sudo bash
sudo apt install docker-compose -y
```
2. Fix configuration
- docker-compose.yml
- config/configuration.yml
3. Up Redmine

`docker-compose up -d`

4. Remarks
  1. Install plugins
  - make plugins directory.
  - install plugin to ./plugins/
