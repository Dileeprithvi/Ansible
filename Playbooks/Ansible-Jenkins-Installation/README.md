# Ansible--Jenkins-Installation
Installation of Open Source Jenkins by Ansible Playbook without Ansible Roles.

The purpose of this document is to provide the Implementation of Open Source Jenkins Installation by the Simple Ansible Playbook.

Customization: 

Default Ansible Host Location: /etc/ansible/hosts

I am creating a group called [test] and placing my private IP.


Ansible Modules Used:
          - yum
          - get_url
          - rpm_key
          - systemd
          - wait_for: timeou
          - shell
          - debug
          
       
          
