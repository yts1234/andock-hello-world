# Hello World!

This repository means to save Dockerfile and Ansible playbook.

## Hello World Container
This image uses Alpine for its base image.

1. Build the Dockerfile images with command:
```bash
docker build -t <put any name> .
```
2. Run the container:
```bash
docker run -rm <images name>
```

## Hello World Playbook
This playbook will run a simple task to all of your hosts defined in your Ansible inventory.

1. Set your Ansible host for testing this playbook.
2. run:
```bash
ansible-playbook yosua-hello-ansible.yml
```
This command will run a simple task echo "Hello World" to all of your hosts.

4. You should get the "Hello World" message from debug section.
