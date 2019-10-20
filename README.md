# Ubuntu Ansible

Local Ubuntu workstation setup using ansible. This has only been tested using Xubuntu 19.10.

Make sure everything is up to date.

  sudo apt-get update
  sudo apt-get upgrade

Use the latest version of ansible.

  sudo apt-add-repository ppa:ansible/ansible
  sudo apt-get update
  sudo apt-get install ansible

Install git

  sudo apt-get install git

Run the installation.

  sudo ansible-pull -U https://github.com/karlkedrovsky/ubuntu-ansible.git
