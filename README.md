# The gatewayd-ansible playbook

## Features

- Install and configure nginx webserver
  - Generate Self-Signed SSL Certificate
  - Add gateway (sub)domain in nginx config

- Install and configure postgres database

- Install and configure gatewayd application
  - Add gateway (sub)domain to gatewayd config
  - Add gateway Ripple hot wallet config & database
  - Add gateway Ripple address to gatewayd config
  - Add gateway admin api key to config
  - Add systemd init task for gatewayd application

