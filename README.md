# OCI-examples

In this repository I will add some examples of my different scripts I use for managing Oracle OCI

### Bastion service scripts
Currently I have added the following two scripts:
Two smalls cripts that creates a bastin serssion for you on the commandline
The requirement is that the bastion service entry is already created and the targets are prepared.
The aim of the scripts is to make life with bastion service easier without compromizing security.
The bastion service is a requirement to create centralized governance and audit on all ssh access to any computenodes

- createBastionSession.bash and   creates a SSH port forwarding session
- createBastionManagedSession.bash   creates a Managed SSH session


For full documentation of Oracle OCI Bastion service [here](https://docs.oracle.com/en-us/iaas/Content/Bastion/home.htm)


