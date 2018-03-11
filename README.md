# ipSpaceCourse
ipSpaceCourse network automation course

# Lab Environment  
Initially I tried using vagrant and virtual box to build my environment. I had limited success. Although I was able to create an NMS and arista topology, I could connect the NMS and Arista MGMT interfaces to an OOB network.

I then moved my efforts to using GNS3 and VMWare Workstation. I created a new VMnet NAT network in he Virtual Network Editor. I initially tried using the GNS3 automation docker appliance but soon realised it was lacking in features. In that network I built an NMS using Ubuntu.

I then tried to build an Arista topology but again I could not get the MGMT interfaces to reach with the NMS. I then tried a Cisco router in NMS and it worked perfectly. So I built a lab using Cisco routers only. However I would like to re-visit the Arista issue in the future when I have more time.

# Network Diagram
A very simple topology. I will elaborate on this in the future, but for now I need to catch up on the course material.
https://raw.githubusercontent.com/eoinwhite/ipSpaceCourse/master/images/NetworkDiagram.PNG

# Ansible
I've created an inventory file and used the raw module to run commands on my lab.

# GIT
I'm using text editors on my laptop to carry out my work. I then us github.com to sync changes to the NMS.
