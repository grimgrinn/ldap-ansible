Устанока LDAP-сервера на Ubuntu с помощью Ansible

Директории: templates - шаблоны ldif для ldap

Файлы: vars - переменные, inventory - файл инвентори, playbook.yml - плейбук ansible

Скриншоты с выполнением команд для проверки подключения, результата работы скрипта, наличия пользователей и групп


Запуск:
ansible-playbook -i inventory.ini playbook.yml
