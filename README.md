# Ansible Role


## Purpose
  Execute this role against supported server(s), it will gather-facts and save them to a logfile for viewing or archiving.
  
----

## Execution
<pre>
    - hosts: all
      tasks:
      - include_role:
          name: drewgwallace.ansible-role-gather_server_facts
</pre>

----

## Notes