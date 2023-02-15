# ansible-prometheus-demo

Ansible Prometheus Configuration
This project is a simple Ansible playbook that installs and configures Prometheus and sets up custom rules and alerts on a remote Ubuntu server. The playbook is designed to be run on a local machine, and uses SSH to connect to the remote server.

Requirements
Local machine with Ansible installed
Remote Ubuntu server with SSH access
Basic knowledge of Ansible and Prometheus
Usage
Clone the repository to your local machine.
Edit the inventory file to add the IP address of your remote server.
Edit the vars/main.yml file to set any custom variables you may need, such as the port number for Prometheus.
Run the playbook with the command ansible-playbook -i inventory prometheus.yml.
