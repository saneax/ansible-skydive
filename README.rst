ansible-skydive
===============

This is ansible scripts to deploy skydive into tripleo nodes, post overcloyd
deployment.

Steps
-----
* git clone git@github.com:saneax/ansible-skydive.git
* cd ansible-skydive
* Populate the hosts and probably group them at playbook/hosts
* Run 'ansible-playbook playbooks/skydive.yaml'
