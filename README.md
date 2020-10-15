# Ansible Macintosh playbook

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
nano config.yml
```

### Executing playbook
```bash
ansible-playbook site.yml
```

Preperation:
- login into the app store
