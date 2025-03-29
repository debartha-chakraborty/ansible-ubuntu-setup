My required setup for Ubuntu 24.04 LTS.

How to use it:

```
ansible-playbook -i "localhost," -c local main.yml --become --ask-become-pass
```

Ansible tested:

```
$ ansible --version
ansible [core 2.17.10]
  config file = /etc/ansible/ansible.cfg
  configured module search path = ['/home/roster/.ansible/plugins/modules', '/usr/share/ansible/plugins/modules']
  ansible python module location = /usr/lib/python3/dist-packages/ansible
  ansible collection location = /home/roster/.ansible/collections:/usr/share/ansible/collections
  executable location = /usr/bin/ansible
  python version = 3.12.3 (main, Feb  4 2025, 14:48:35) [GCC 13.3.0] (/usr/bin/python3)
  jinja version = 3.1.2
  libyaml = True

```

Apps:
* Chrome
* Curl
* DBeaver
* Docker*
* Docker Compose*
* Git*
* GitKraken
* Gnome Tweak Tools
* Go(Golang)*
* Neovim
* Python 3.11 as default
* ROS 2 Jazzy
* Slack
* Telegram
* Terraform*
* Tilix
* Vscode
* VSCode Insiders
* Zoom