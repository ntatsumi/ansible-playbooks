ansible-playbooks
=================
Automation scripts with Ansible

## How-to for Mac OS
Install ansible
```
brew doctor # make sure Homebrew is happy
brew update # make sure you have the latest formulas
brew install ansible
```

Set environment variables
```
export ANSIBLE_HOSTS=~/secure/inventory
export ANSIBLE_HOST_KEY_CHECKING=false
export ANSIBLE_NOCOWS=1
```

Specify your host(s)
```
vi inventory
```

Run playbook
```
ansible-playbook ${playbook}.yml
```
