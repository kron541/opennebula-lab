# opennebula-lab

Vagrantfie creates two machines:
## frontend
[frontend](https://docs.opennebula.org/5.10/deployment/opennebula_installation/frontend_installation.html)
after provisioning you need to manualy copy /var/lib/one/.one data to backend(after bridge creation), and make ssh-keygen
to add backend to cluster use [sunstone](http://192.168.200.11:9869/) . credentials in /var/lib/one/.one/one_auth
## backend
[backend](https://docs.opennebula.org/5.10/deployment/node_installation/kvm_node_installation.html)
create bridge, add eth1 to it(ip should be on bridge ofc.), set bridge's link up
