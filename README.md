# notes
A place to keep notes.


## Troubleshooting
Cannot connect to cluster portal on Mac.

First, do an nslookup and see what response you are getting, if any:
$ nslookup console-openshift-console.apps.homelab.delaporte.us

If you don't have other DNS setup, edit your /etc/hosts file to add entries recommended by Red Hat during the initial cluster installation.
