OpenShift 4 F5 Load Balancer Role
===========================================

## Description
------------

This is an Ansible Role that configures an BigIP F5 LTM Load Balancer for OpenShift 4.

## Infrastructure Prerequisites

1. A fully functional and properly configured F5 LTM

### Expected Outcome

1. Monitors are created for ports 6433 (API), 22623 (Machine-API), and HTTP.
2. Role will create Master and Worker Nodes with correct monitors.
3. Four (4) pools will be created for API, Machine-API, HTTP, and HTTPS with correct Monitors.
4. Four (4) virtual servers will be created with the correct pools.

AUTHOR
------
Morgan Peterman
