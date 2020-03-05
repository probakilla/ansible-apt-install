# Apt Install

Use to install basic programs

## Variables

Variables in the defaults/main.yml file

```
# Location where to install vundle
vundle_location: ~/.vim/bundle/Vundle.vim
# Location where oh my zsh plugins are installed
ohmyzsh_plugins_path: ~/.oh-my-zsh/plugins
```

## Howto use this role

This role needs to be included in a playbook
You can install it with *Galaxy*

```bash
ansible-galaxy install -r requirements.yml
```

requirements.yml
```
- src: probakilla.apt_install
```

# Requirements

- Ansible 2.4+
