# ansible-netapp
Ansible modules and playbooks utilizing the Python API in the NetApp Manageability SDK

This utilizes custom Ansible modules built using the NetApp Manageability SDK (NMSDK). The playbooks aid in the provisioning and management of Clustered Data ONTAP and hopefully entire FlexPods.

## Dependencies

Install the NetApp Manageability SDK

https://community.netapp.com/t5/Software-Development-Kit-SDK-and-API-Discussions/NetApp-Manageability-NM-SDK-5-4-Introduction-and-Download-Information/td-p/108181

!!!Make sure to add the location of the NMSDK to your PYTHONPATH environment variable!!! 

e.g. 

PYTHONPATH="/Volumes/data/Netapp/netapp-manageability-sdk-5.5/lib/python/NetApp:$PYTHONPATH"

export PYTHONPATH
