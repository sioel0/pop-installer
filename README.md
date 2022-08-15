# Pop-Os installer
This is my Ansible script for basic system installation, it works on Pop-Os
or any Ubuntu based linux distro.(Tested only on Pop-Os)

This script installs all my basic software and add my dotfiles to the
system.

# How to use
To use it make sure to have ansible installed using
```
pip install ansible
```

It is important to add an ssh-key registered with your github account such
that it is possible to clone repositories using ssh.

Once you have ansible installed you can run the script using:
```
ansible-playbook install.yaml --ask-become-pass
```
