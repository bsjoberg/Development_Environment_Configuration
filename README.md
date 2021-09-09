<h1>Development Environment Configuration</h1>

Simple Development environment configuration for Java, Intellij using Ansible playbook.

To install ansible run the following commands:
``` shell 
sudo apt update
sudo apt install software-properties-common
sudo add-apt-repository --yes --update ppa:ansible/ansible
sudo apt install ansible
```

Then just run the following after downloading the YAML file:
``` shell 
sudo ansible-playbook development.yml
``` 

You could install curl and then output the linked YAML into a local file doing the following
``` shell
curl https://raw.githubusercontent.com/bsjoberg/Development_Environment_Configuration/master/development.yml > development.yml
```