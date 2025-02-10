# Ansible-infra

## Ansible script to install Gentoo from the Gentoo live gui image

1. Boot up your Gentoo live gui image
2. Set the variables in the ```genbootstrap/defaults/main.yml```
3. Run ```ansible-playbook gentoo_bootstrap.yml```
    + **WARNING:** Your specified drive will be formatted and all data will be lost!
    + Only supports the ext4 filesystem for now

