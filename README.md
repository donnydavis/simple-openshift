# simple-openshift
There are prequsite things for this role to work
You need python2-shade and all of the openstack clients
You will also need to setup ansible for dynamic inventories, and that can be found here https://github.com/donnydavis/randombits


Provision Openshift on Openstack

    git clone https://github.com/donnydavis/simple-openshift.git
    cd simple-openshift
    ansible-playbook site.yaml

To deprovision things are pretty simple
    ansible-playbook delete.yaml


All of the variables are in the group_vars folder, there is only one file and its pretty self explanatory. 
