# n9kv-automation
Several different Ansible playbooks, roles, etc to help in conveying the power of Ansible usage in having automation discussions with network engineering staff.  Playbooks progress in complexity, from very linear, single purpose playbooks using CLI/SSH transport -- to more complex playbooks with conditional elements, encrypted information in Vault, and calls to external messaging services ("ChatOps") to indicate completion of device provisioning.

### Usage
Playbooks designed around (2) NXOS9000v hosts provisioned in VIRL.  E1/1 interfaces on each switch are assigned to external layer-2 FLAT network.  E1/2 interfaces are connected between switches.  0/0 route for management traffic is configured.  NXAPI enabled with non-standard port.  All other configuration is default on the devices.
