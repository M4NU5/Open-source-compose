# Mattermost
Open source replacement for Slack

[Website](https://mattermost.com/)

[Github Repo](https://github.com/mattermost/docker)

[Documentation](https://docs.mattermost.com/install/install-docker.html)

#### Example deployments
Without Nginx
`sudo docker compose -f docker-compose.yml -f docker-compose.without-nginx.yml up -d`

With Nginx
`sudo docker compose -f docker-compose.yml -f docker-compose.nginx.yml up -d`
