Ansible playbook experiment
===========================

setup vagrant and ansible config

- running vagrant machine as remote server require installed **virtualbox** and **vagrant** command
- before running ansible playbook. Change ssh port in **hosts** file first
  - for lookup ssh port run command ```vagrant ssh-config```

setup remote docker using playbook

- run ```ansible-playbook python.yml```
- run ```ansible-playbook dockerce.yml```

running container in remote

- run ```ansible-playbook -e gitlab_token=<token here> -e gitlab_username=<username here> authen.yml```

