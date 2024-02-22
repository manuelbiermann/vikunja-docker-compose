# vikunja-docker-compose

This is a non-offical opinionated template to get [vikunja](https://vikunja.io/) up and running. We are using docker-compose, [Sendgrid](https://sendgrid.com/) to send emails, Google OpenID, and [Caddy](https://caddyserver.com/) to set up a reverse-proxy.

## Steps

1. Clone this repo to the host
2. Adjust the docker-compose and config.yml
3. Set up your DNS Records so the publicUrl is poiting to your host
4. Adjust the Caddyfile
5. Run 'docker-compose pull'
6. Run 'docker-compose up'
