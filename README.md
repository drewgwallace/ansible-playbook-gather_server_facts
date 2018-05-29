# Ansible Playbook



## Purpose
  Execute this play against a supported server, it will gather-facts and save them to a logfile for viewing or archiving.
  
----

## Execution
<pre>
    ansible-playbook gather_server_facts.yml -e "variable_host=<b>HOST_IN_INVENTORY</b>"
</pre>

----

## Notes
+ Be sure to populate the /etc/ansible/hosts file with your variable_host.
++ Optionally you could edit the hosts line in gather_server_facts.yml or create a new hosts file and call it with the -i command line flag.
