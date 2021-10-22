For execute:
```
ansible-playbook -i hosts deploy.yml
```

After cluster setuo, you should create users and passwords for elasticsearch.

You can connect to any node and run the command:

```
docker exec -it node3 bash
echo y | /usr/share/elasticsearch/bin/elasticsearch-setup-passwords auto
```
