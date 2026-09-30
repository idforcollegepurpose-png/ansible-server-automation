# Automate Server Configuration using Ansible

## Overview
Ansible playbook that configures multiple web servers with one command.

## What it does
- Installs and starts Nginx on all servers
- Deploys a custom website using Jinja2 templates
- Applies SSH security hardening (root login and password login disabled)
- Generates an HTML report of all server details

## How to run
ansible-playbook -i inventory/hosts.ini site.yml

## Tools used
Ansible, Docker (managed nodes), GitHub Codespaces (control node)
