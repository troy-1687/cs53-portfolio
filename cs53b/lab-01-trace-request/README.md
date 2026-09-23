# Lab 1: Trace the Request

## What I practiced

In this lab, I worked with a simple virtual Linux network and used networking tools to examine:

- name resolution,
- route selection,
- next-hop addressing,
- outgoing interface and source addressing,
- and neighbor information.

## Request trace

In one or two sentences, explain how the client moves from `web.minicorp.test` to its next-hop device.

> The client uses name resolution to find the IP address for web.minicorp.test. Then after, it uses its routing table to find the next hop device and then sends traffic through the network interface using the hop link's layer address.

## Key takeaway

Explain why the client needs both an IP address and a link-layer address when sending traffic to the next hop.

> The client needs both an IP address and a link-layer because the IP identifies the next hop device at the network layer and the link-layer address helps allow the client to deliver the frame to that device on the local network.
