# Setup script

This is the ansible script to setup WSL / home desktop for development work from scratch.

```
sudo apt-get install ansible unzip -y

cd ~

wget https://github.com/kenchoihm/ansible-local/archive/refs/heads/master.zip

unzip master.zip

mv ansible-local-master ansible-local

cd ansible-local
```

## Set up WSL:
```
ansible-playbook playbook/setup-wsl.yml
```

## Set up the home desktop:
```
ansible-playbook playbook/setup-home.yml
```

