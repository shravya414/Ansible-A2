# Ansible-A2

Used Ansible playbook to deploy flask app, HAproxy, Nginx and SNMP onto servers. Where flask app answers the requests by replying with time and name of the host.
Configured HAproxy and Nginx to load balance servers, where Nginx looks after SNMP and HAproxy looks after flask app.
