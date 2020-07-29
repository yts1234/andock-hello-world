# Hello World!

This repository is meant for save dockerfile and ansible playbook.

## Hello World Container
This image use Alpine for its base image

1. Build the Dockerfile images with command:
```bash
docker build -t <put any name> .
```
2. Run the container:
```bash
docker run -rm <images name>
```

## Hello World Playbook
This playbook will run simple task to all of your host defined in your ansible inventory

1. Set your ansible host for testing this playbook.
2. run
```bash
ansible-playbook yosua-hello-ansible.yml
```
This command will run simple task echo "Hello World" to all of your host.

4. You should get "Hello World" message from debug section
