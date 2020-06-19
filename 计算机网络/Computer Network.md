# Computer Network

## Introduction

- network edge
  - end system(hosts)
  - client/server model
  - peer-peer model
- access networks
- nertwork core
  - circuit switching
  - packet switching
    - delay
      - processing delay
      - queuing delay
        - La/R
      - transmission delay: L/R
      - propagation delay: d/s
    - packet loss
    - throughput
- protocol stack
  - application layer: message
  - Transport layer: segment
  - Network layer: datagram
  - Link layer: frame

## Application layer

- process communication
  - client process
  - server process
- socket
  - process $\to$ TCP(buffer)
- HTTP
  - statesless
  - persistent
  - non-persistent
  - cookie
- web cache
  - delay = Inetnet delay + access delay + LAN delay
- DNS
- P2P

## Transport layer

- logical communication between processes
- UDP socket
  - dest IP address
  - dest port number
- TCP socket
  - source IP address
  - source port number
  - dest IP address
  - dest port number
- pipeline
  - GBN
  - SR
- TCP
  - segment
  - Ack Seq
  - flow control
  - congestion control

## Network layer

- logical communication between hosts
- IPv4
  - MTU
  - CIDR
    - a.b.c.d/x
      - subnet + host
      - prefix matching
  - DHCP
  - NAT
- IPv6
  - checksum
  - options
  - ICMPv6
- IPv4 IPv6
  - tunneling
- routing
  - OSPF
  - BGP
- ICMP

## Link layer

- multiple access
  - channel partitioning
    - TDM
    - FDM
  - random access
    - slotted ALOHA
    - pure ALOHA
    - CSMA
    - CSMA/CD
    - CSMA/CA
  - taking-turns
- MAC
  - ARP
    - self-learning
    - plug-and-play
- switch
  - self-learning
- segment
  - DNS 90
  - UDP 132
  - TCP 154-20bits
  - IPv4 214-20bits
  - IPv6 228-
  - Ethernet 309
