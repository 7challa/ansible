# ansible examples
Lets say you have 100s of server which you access through Jump Server and you need to setup SSH keys from Jump Server >>> Remote hosts


ansible-playbook -vvv -i new_host.inv add_key.yml -u <username> -k
