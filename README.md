README
======

This repo contains a cloud-init script for easy reactor installation.

To use it, simply edit for the correct repo:

   echo cloud-init | sed -e 's|${REPO}|http://.....|g' > mycloudinit
