A couple of ansible playbooks using modules

Copy: This playbook is used to ping and copy a config file and a private key file from the control node to all hosts.

Apache: This playbook uses the yum module to install the Apache web server, the service module to start and enable the Apache service, the copy module to create an index.html file, the file module to set the ownership of the index.html file, the firewalld module to add a firewall rule to allow HTTP traffic, and the wait_for module to check if Apache is running and responding on port 80. Finally, the debug module is used to display the Apache service status after the previous step.
