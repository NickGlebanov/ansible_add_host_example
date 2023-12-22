# кейс продолжения работы плейбука на одном хосте из множества

## Запуск
```shell
export ANSIBLE_CONFIG=$(pwd)/ansible.cfg
ansible-playbook --verbose -i hosts playbook.yml
```