# hyperv-lubuntu-20.04-tool
configure Lubuntu 20.04 Desktop to run under enhanced session mode in Hyper-V


script modified from :

https://github.com/Hinara/linux-vm-tools


script will patch system if needed before installing and configuring XRPD to run in hv_sock mode.


once the installation is complete, run in host powershell 


```
set-vm -VMName <NAME_OF_VM> -EnhancedSessionTransportType HvSocket
```
