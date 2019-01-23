

## Getting started page

# P4 Language Documentation

* Point to p4 language spec (Robert)
* Point to control plane interface? (P4 Runtime) (Robert)

# Pre-built Environments

To start with some P4 tutorials you will need to build a virtual machine. 
If you are skilled with git, vagrant and Virtualbox:

`git clone https://github.com/p4lang/tutorials`

`cd tutorials/vm`

`vagrant up`

Building the virtual machine will take about an hour because it is necessary to run a some scripts to load the whole environment.

Log in with username p4 and password p4 and issue the command:

`sudo shutdown -r now`



# Installation and hardware compatibility guides

The P4 software environment is Linux based, however different hardware targets have different platform requirements.

## P4 Software environment

## P4-NetFPGA Environment

P4-NetFPGA is an open source software/hardware platform, and requires a NetFPGA board.

[P4-NetFPGA Getting Started and Setup Guide](https://github.com/NetFPGA/P4-NetFPGA-public/wiki/Getting-Started)

[NetFPGA motherboard compatibility](https://github.com/NetFPGA/NetFPGA-SUME-public/wiki/Motherboard-Information)



* Per-hardware target installations
    * What is the operating system assumed?
    * What software is needed?
    * Installation guides for Ubuntu VM and OpenSource tools (Andy)
    * EdgeCore + Ubuntu
    * EdgeCore + ONL
    * Netronome (Eder)

# Additional Resources

Useful information can be found in the following links:

* [P4 Youtube Channel](https://www.youtube.com/channel/UCOQAFkDKucJWr-KafdJsdIQ)
    
* Andy's guides (Andy)
* SIGCOMM Tutorials (Robert)
* ONOS tutorial
    * To learn about the support for P4 in ONOS there is a tutorial updated on December 2018. You can find a tutorial presentation that includes an introduction to P4Runtime, ONOS, and use cases (fabric.p4 and spgw.p4) here:

    https://wiki.onosproject.org/pages/viewpage.action?pageId=16122675

    * This tutorial includes hands-on exercices:

    https://github.com/opennetworkinglab/onos/tree/master/apps/p4-tutorial

 
# Code Examples

* Pointers to download example code (Robert)

 
