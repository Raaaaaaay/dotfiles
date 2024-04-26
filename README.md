# Install git
```sh
sudo apt install -y git
```

# Install pip
```sh
    // If using arch
    sudo pacman -S python-pip
    sudo rm sudo rm /usr/lib/python3.11/EXTERNALLY-MANAGED
```


# Clone the repository
```sh
git clone git@github.com:Raaaaaaay/dotfiles.git
cd dotfiles
```

# Install Ansible
```sh
./install-ansible
```

# Run playbook
```sh
ansible-playbook --ask-become-pass bootstrap.yml
```
