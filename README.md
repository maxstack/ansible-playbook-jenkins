# ansible-playbook-jenkins

RHEL/CentOS 7 - Playbook to install jenkins

## Requirements

ansible-galaxy install -r requirements.yaml

## Role Variables

Available variables are listed below, along with default values:

    jenkins_hostname: localhost
    jenkins_admin_username: admin
    jenkins_admin_password: somecomplexpassword
    jenkins_plugins:
      - git
      - ...
    jenkins_plugins_install_dependencies: yes
