Usage:

```
sudo apt-add-repository ppa:ansible/ansible
sudo apt update
sudo apt install ansible
ansible-playbook -vD my-desktop.yml --ask-become-pass
```

- apt repositories and packages
- Unity desktop specific
- laptop specific
    - powertop
    - laptop-mode-tools
        - exclude some USB devices(mouse)
- device specific
    - Lenovo YOGA 900 13ISK
        - add missing display resolution for lightdm
