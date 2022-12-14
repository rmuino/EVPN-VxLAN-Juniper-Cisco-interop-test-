# EVPN-VxLAN-Juniper-Cisco-interop-test
Interoperability test for EVPN-VxLAN in Data-Center Clos topology

This interoperability test were done for a particular customer requirement whos needed to add Juniper leaves to existing Cisco IP-fabric Clos topology at their data-center.

*** LAB DESCRIPTION ***

This example details how to deploy an edge-routed bridging (ERB) architecture using a 3-stage Clos fabric. It's deployment uses OSPFv2 for the underlay, iBGP for the overlay, and EVPN-VxLAN to provide connectivity across the Layer 3 fabric.

*** HARDWARE | SOFTWARE SPECIFICATIONS ***

<img width="745" alt="image" src="https://user-images.githubusercontent.com/117160980/199208033-67dc0fe5-8772-46a6-b1a7-ae927be2ec08.png">

*** LAB TOPOLOGY ***

<img width="1095" alt="image" src="https://user-images.githubusercontent.com/117160980/199244331-bdf4f112-0e57-4d50-a114-4ceec27ac8bf.png">

*** USER GUIDES ***

Juniper EVPN User Guide: https://www.juniper.net/documentation/us/en/software/junos/evpn-vxlan/index.html 

Cisco Nexus 9000 Series NX-OS VXLAN Configuration Guide: https://www.cisco.com/c/en/us/td/docs/switches/datacenter/nexus9000/sw/92x/vxlan-92x/configuration/guide/b-cisco-nexus-9000-series-nx-os-vxlan-configuration-guide-92x.html
