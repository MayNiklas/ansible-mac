# Ansible Macintosh playbook
[![Lines Of Code](https://tokei.rs/b1/github/MayNiklas/ansible-mac?category=lines)](https://github.com/XAMPPRocky/tokei)
[![Lines Of Code](https://tokei.rs/b1/github/MayNiklas/ansible-mac?category=code)](https://github.com/XAMPPRocky/tokei)
[![Lines Of Code](https://tokei.rs/b1/github/MayNiklas/ansible-mac?category=files)](https://github.com/XAMPPRocky/tokei)

### Installing brew
```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"
```

### Installing Ansible
```bash
brew install ansible
```
### Configure the variables to your liking
```
nano host_vars/localhost.yml
```

### Install required roles
```
ansible-galaxy install -r requirements.yml
```

### Executing playbook
```bash
ansible-playbook main.yml
```

Preperation:
- login into the app store
