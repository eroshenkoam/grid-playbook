# Selenium grid playbook

## Setup selenium hub

`ansible-playbook -i hosts.ini --ask-sudo-pass selenium-hub.yml`

## Setup selenium nodes

`ansible-playbook -i hosts.ini -e selenium_hub_host=<selenium hub host here> --ask-sudo-pass selenium-hub.yml`
