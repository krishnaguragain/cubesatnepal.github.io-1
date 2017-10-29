---
layout: post
title:  "Cubesat Space Protocal"
image: ''
date:   2016-03-12 00:06:31
tags:
- mongodb
description: ''
categories:
- Learn GH 
---



# The CubeSat Space Protocol
The CubeSat Space Protocol enables distributed embedded systems to deploy a service-oriented network topology.
The layering of CSP corresponds to the same layers as the TCP/IP model. The implementation supports a connection
 oriented transport protocol (Layer 4), a router-core (Layer 3), and several network-interfaces (Layer 1–2).
 A service-oriented topology eases the design of satellite subsystems, since the communication bus itself
 is the interface to other subsystems. This means that each subsystem developer only needs to define a service-contract,
 and a set of port-numbers their system will be responding on. Furthermore, subsystem inter-dependencies are reduced,
 and redundancy is easily added by adding multiple similar nodes to the communication bus.