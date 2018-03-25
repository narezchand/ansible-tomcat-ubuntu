## Standalone Tomcat Deployment to ubuntu Os

- Requires Ansible 1.2 or newer
- Expects Ubuntu hosts
- Install Openjdk 1.8
- Install Tomcat7

These playbooks deploy a very basic implementation of Tomcat Application Server,
version 7. To use them, first edit the "hosts" inventory file(/etc/ansible/hosts) to contain the
hostnames of the machines on which you want Tomcat deployed.

Then run the playbook, like this:

For Tomcat :

	ansible-playbook site.yml --user ubuntu

	
When the playbook run completes, you should be able to see the Tomcat
Application Server running on the ports you chose, on the target machines.

This is a very simple playbook and could serve as a starting point for more
complex Tomcat-based projects.

### Ideas for Improvement
-- @narezchand
