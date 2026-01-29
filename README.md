Automated Server Configuration Using Ansible

This project demonstrates how to automate Linux server setup using Ansible instead of manual commands.

Architecture
Control Node (Ansible) → SSH → Target EC2 Server

Tech Stack

Ansible

Linux

AWS EC2

SSH

Features

Automated package installation

Service management

Idempotent configuration

SSH-based automation

Files

hosts – inventory file

setup.yml – Ansible playbook

Setup

Launch Ubuntu EC2

Install Ansible on local machine

Add EC2 to inventory

Run playbook

Verify Nginx running

Result

After running the playbook, the web server is live.
