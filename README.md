# Install git
```sh
sudo apt install -y git
```



# Clone the repository
```sh
git clone git@github.com:Raaaaaaay/nvim.git
cd dotfiles
```

# Install Ansible
```sh
./install
```

# Run playbook
```sh
ansible-playbook --ask-become-pass bootstrap.yml
```
