Ansible roles for Hello World nginx_app, swap, creating users

Assume that you have vagrant, ansible, virtualbox installed on your system.

Run "vagrant up" command and wait till vagrant environment will be provisioned and playbooks executed.
You can verify Nginx test page using localhost:8080 url.

SSH can be checked with "ssh admin@localhost -p 2222 -i .../roles/create_user/files/admin" command

Provisioned users are in the main.yml file. If other users are required add them in main.yml,also appropriate ssh keys should be created in roles/create_user/files directory.
