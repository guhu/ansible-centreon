# ansible-centreon

##Centreon Infrastructure (Central - Poller - Db Server) deployment

- Requires Ansible 1.2 or newer
- Expects CentOS/RHEL 6.x hosts

These playbooks can deploy a simple all-in-one Centreon server or a distributed 
infrastructure with on Central, many Pollers and a dedicated Db server. To use, 
copy the `hosts.example` file to `hosts` and edit the `hosts` inventory file to
to include the names or URLs of the servers you want to deploy.
