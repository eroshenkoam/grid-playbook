# Selenium grid playbook

## Setup selenium hub

`ansible-playbook -i hosts.ini selenium-hub.yml --ask-sudo-pass`

## Setup selenium nodes

`ansible-playbook -i hosts.ini selenium-nodes.yml --ask-sudo-pass`
