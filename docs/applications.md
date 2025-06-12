## Accessing the Applications

Now that your containers have been created and applications launched, you can login to them using your browser and via SSH.  We recommend you keep this page open as you work your way through the tutorial as it provides a guide to URLs, container names, and user credentials.

**At this point, you can jump to the first section of the tutorial:  [ColdFront](../coldfront/README.md)**


### User Accounts

For the scope of this tutorial, we have created a default user account
```
username: hpcadmin
password: ilovelinux
```

### Logging in to the frontend

You must first login to the frontend via SSH using the default user:
```
ssh -p 6222 hpcadmin@localhost
```  

### Open OnDemand
**NOTE: You must login to the front end before trying to login to the OnDemand container!**

Open OnDemand is used for accessing HPC resources, submitting jobs to a cluster, user file access, etc.

SSH container name: ondemand 
URL: https://localhost:3443  
*Portal Logins include:*  
Once logged in, click on "Clusters" and then "HPC Cluster Shell Access" and you will be logged in to the cluster frontend container.

### Slurm and Compute Nodes

~~There is a slurm controller, slurm database container, and two compute nodes in this cluster.~~

~~Login to the front end first:~~
~~`ssh -p 6222 hpcadmin@localhost`~~

~~Then login to any of the containers using any of the LDAP accounts listed above.~~

~~SSH container name for Slurm controller: `slurmctld`~~
~~SSH container name for Slurm database: `slurmdbd`~~
~~SSH container name for compute node 1: `cpn01`~~
~~SSH container name for compute node 2: `cpn02`~~

## Tutorial Navigation 
[Next - OnDemand](../ondemand/README.md) 
[Previous Step - Getting Started](getting_started.md)  
[Docker Tips](docker_tips.md)  
[Back to Start](../README.md)  
