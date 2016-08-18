## Backup mysql database
Run this using:
ansible-playbook playbook/mysql_backup.yml

For specific host:
ansible-playbook --limit imac-2.local playbook/mysql_backup.yml

For ssh password
ansible-playbook --limit lexusdesignawardrussia.ru  playbook/ssh.yml --ask-pass
