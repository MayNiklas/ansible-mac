# Ansible Macintosh playbook

[![Lines Of Code](https://tokei.rs/b1/github/MayNiklas/ansible-mac?category=lines)](https://github.com/XAMPPRocky/tokei)
[![Lines Of Code](https://tokei.rs/b1/github/MayNiklas/ansible-mac?category=code)](https://github.com/XAMPPRocky/tokei)
[![Lines Of Code](https://tokei.rs/b1/github/MayNiklas/ansible-mac?category=files)](https://github.com/XAMPPRocky/tokei)

### Used roles

- <https://github.com/MayNiklas/ansible-osx_defaults.git>
- <https://github.com/MayNiklas/ansible-shell-mac.git>
- <https://github.com/MayNiklas/ansible-git.git>
- <https://github.com/MayNiklas/ansible-yubikey.git>
- <https://github.com/MayNiklas/ansible-homebrew.git>
- <https://github.com/MayNiklas/ansible-ssh.git>
- <https://github.com/MayNiklas/ansible-mas.git>

### how to execute the playbook

```bash
# install brew.sh
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"

# install ansible
brew install ansible

# clone repository
git clone --recursive https://github.com/MayNiklas/ansible-mac.git

# Configure the variables to your liking
nano host_vars/localhost.yml

# Install required roles
ansible-galaxy install -r requirements.yml

# execute playbook
ansible-playbook site.yml
```

Preperation:

- login into the app store
