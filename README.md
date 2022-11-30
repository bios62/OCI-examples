# OCI-examples

In this repository I will add some examples of my different scripts I use for managing Oracle OCI
### OCi IAM Domain configuration
Writeup and example of configuring Azure AD as IdP with Oracle OCI IAM as SP is [Here](https://github.com/bios62/OCI-examples/blob/main/azureAD_federation_v1_domain.pdf)


### Bastion service scripts
Currently I have added the following two scripts:
Two smalls cripts that creates a bastin serssion for you on the commandline
The requirement is that the bastion service entry is already created and the targets are prepared.
The aim of the scripts is to make life with bastion service easier without compromizing security.
The bastion service is a requirement to create centralized governance and audit on all ssh access to any computenodes

- [createBastionSession.bash](https://github.com/bios62/OCI-examples/blob/main/createBastionSession.bash) creates a SSH port forwarding session
- [createBastionManagedSession.bash](https://github.com/bios62/OCI-examples/blob/main/createBastionManagedSession.bash) creates a Managed SSH session
- complete description is available in the document [securing exacs or dbcs with bastion service.pdf](https://github.com/bios62/OCI-examples/blob/main/securing%20exacs%20or%20dbcs%20with%20bastion%20service.pdf)


For full documentation of Oracle OCI Bastion service [here](https://docs.oracle.com/en-us/iaas/Content/Bastion/home.htm)


