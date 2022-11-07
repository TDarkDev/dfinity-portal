---
title: Peer-to-peer layer
---

![](/img/how-it-works/peer-to-peer-p2p.600x300.jpg)

# Peer-to-peer

The peer-to-peer layer (P2P) of the Internet Computer, the bottommost layer in the protocol stack, is responsible for the secure and reliable communication between the nodes of a subnet.
The P2P layer realizes a virtual peer-to-peer broadcast network between the nodes of a subnet, building upon the Internet Protocol (IP) connectivity between the nodes.
This makes the P2P layer the communications fabric that connects all the nodes of a subnet.
Using P2P, a node can broadcast a *message*, also called *artifact*, to all the nodes in the subnet.
Artifacts can be things like ingress messages submitted by users or protocol messages (e.g., block proposals) generated by the IC protocol.
P2P ensures that artifacts to be broadcast are eventually delivered to all nodes of the subnet.
Eventual delivery reflects the asynchronous nature of real-world communication networks, which we assume for the Internet Computer protocol.

[Go deeper](/how-it-works/peer-to-peer-p2p/)