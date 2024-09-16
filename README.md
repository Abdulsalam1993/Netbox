Da im Rahmen der Migration der Server, der IP-Manager durch die Software NetBox aufgrund des besseren Funktionsumfanges abgelöst werden soll, müssen die bisherigen Automatismen in Ansible auf die neue Software umgestellt werden. Hierzu sollen Playbooks entwickelt werden, die die dynamische IP-Verwaltung über ein bestehendes Ansible-Modul(netbox) erledigen.
 

 Befahel: ansible-playbook --ask-vault-pass netbox.yml 
 passswort: Abed    
