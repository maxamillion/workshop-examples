# workshop-examples
Ansible Workshop Example Playbooks for Security Automation


## Exercise 2.1 Snort Rule
alert tcp any any -> any any (msg:"Attempted DDoS Attack"; uricontent:"/ddos_simulation"; classtype:successful-dos; sid:99000010; priority:1; rev:1;)
