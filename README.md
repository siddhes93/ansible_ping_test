# ansible_ping_test

#This is will be the output in case of my host. Make sure you replace your host details in to your inventory files. 

ansible-playbook -i hosts main.yml

PLAY [all] *********************************************************************

TASK [Gathering Facts] *********************************************************
[WARNING]: Platform linux on host 172.31.95.193 is using the discovered Python
interpreter at /usr/bin/python, but future installation of another Python
interpreter could change this. See https://docs.ansible.com/ansible/2.9/referen
ce_appendices/interpreter_discovery.html for more information.
ok: [172.31.95.193]
[WARNING]: Platform linux on host 172.31.93.213 is using the discovered Python
interpreter at /usr/bin/python, but future installation of another Python
interpreter could change this. See https://docs.ansible.com/ansible/2.9/referen
ce_appendices/interpreter_discovery.html for more information.
ok: [172.31.93.213]

TASK [test connection] *********************************************************
ok: [172.31.95.193]
ok: [172.31.93.213]

PLAY RECAP *********************************************************************
172.31.93.213              : ok=2    changed=0    unreachable=0    failed=0    skipped=0    rescued=0    ignored=0
172.31.95.193              : ok=2    changed=0    unreachable=0    failed=0    skipped=0    rescued=0    ignored=0
![image](https://user-images.githubusercontent.com/103021940/183280897-1aa904f2-22d3-43fa-b623-088bbffd0d3f.png)
