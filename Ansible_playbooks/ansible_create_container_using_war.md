---
- hosts: all
  become: true
  tasks:
  - name: building docker image
    command: docker build -t my-devops-image .
    args:
      chdir: /opt/docker
