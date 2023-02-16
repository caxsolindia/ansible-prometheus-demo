# Configuring Prometheus on Remote Server using Ansible

This project aims to demonstrate how to use Ansible to configure Prometheus on a remote server, and set up rules and alerts for monitoring.

# Prerequisites
  - Ansible installed on your local machine
  - A remote server running Ubuntu with SSH access

# Getting Started
  - Clone this repository to your local machine.
  - Set up your inventory file with the IP address of your remote server.
  - Run the playbook using the following command:
    - ansible-playbook -i prometheus/tests/inventory prometheus/tests/test.yml 
  
# Files
  - The files included in this project are:

  - /tasks/main.yml: The main Ansible playbook that installs and configures Prometheus on the remote server.
  - tests/inventory: The inventory file that lists the IP address of the remote server.
  - templates/prometheus.yml.j2: The Jinja2 template file used to create the Prometheus configuration file on the remote server.
  - /files/custom_rules.yml: The custom rules file that defines the rules and alerts for Prometheus.

# Customization
  - The playbook can be customized to fit your specific needs by modifying the file and the Jinja2 template file in the templates directory. You can also       add or remove tasks in the playbook as needed.
  
# Credits
  - This project was created by Ronak Prajapati From Caxsol Team.




