# Single Node OpenShift on Baremetal for Home Lab

## Subscription
Sign up for the Red Hat Developer for Individuals program.

## Build an ISO for an automated installation
Sign into the Red Hat Console: https://console.redhat.com
Navigate to the OpenShift cluster page, and Select Create Cluster -> Datacenter -> Baremetal (x86_64).
Direct link: https://console.redhat.com/openshift/install/metal

From there, select the following:
* Cluster name
* Pull secret
* Single-node openshift

On the next window, select Add Hosts to Cluster
Make sure to add the contents of a public ssh key, in case you need to connect to the cluster node later for any reason.
* I selected Full ISO
* Add your SSH keyfile or public key content

Use Rufus (or another bootable disk creator) to write the ISO to a USB drive.

## Hardware notes
- Install with only your root/system hard drive in place. 
- Add your storage drive(s) after initial installation.
