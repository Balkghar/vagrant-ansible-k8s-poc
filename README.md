# POC of a deployment for a K8S cluster with Vagrant and ansible

Before deploying the infrastructure, be sure that Vagrant and ansible is working on your computer, it used VirtualBox as a VM provider.

I use Flatcar for the VM, so you need to add the image to youz vagrant with this command:

```bash
wget https://alpha.release.flatcar-linux.net/amd64-usr/current/flatcar_production_vagrant.box
vagrant box add flatcar-alpha flatcar_production_vagrant.box
```

## Deploy the VMs with Vagrant

In the folder **Vagrant**, use `vagrant up` to deploy the machine.
