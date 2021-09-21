# Infrastructure as Code ESTGV

## Setup

1. Set-up a virtual enviroment
- `python -m venv docker-env`
- `source docker-env/bin/activate`

2. Install the following dependencies:
- `pip install ansible`

3. Install the following dependencies to create graph visualization of the playbooks (**optional**)
- `sudo apt install graphviz`
- `pip install ansible-playbook-grapher`

4. Run the playbooks:
- `ansible-playbook -i inventory <your-playbook.yml>`

## To do
  - work on creating the awx resources
  - work on creating openstack resources
  - work on creating openstack instance maintenance tasks
  - work on deploying moodle instance
  - work on deploying students lab network
  - work on deploying students lab instaces
  - encrypt credentials **IMPORTANT!!!**
  - refactor roles into multiple tasks files, and use vars file
  - work on documentation