# Computer Network Topology & Static Routing

A computer networking project developed using Cisco Packet Tracer to design and configure an interconnected multi-building network.

## Overview

This project focuses on designing a network topology and implementing IP addressing using Variable Length Subnet Masking (VLSM). The network consists of multiple routers and interconnected buildings with different host requirements.

The configuration includes IP addressing, router configuration, static routing, backup and restore, and network connectivity testing.

## Features

- Network topology design
- VLSM IP addressing
- Multi-router configuration
- Static routing
- PC, server, and laptop configuration
- Network connectivity testing
- Router configuration backup and restore

## Technologies

- Cisco Packet Tracer
- VLSM
- IPv4
- Static Routing
- Network Configuration

## Network Structure

The project consists of six network segments:

- Gedung Dimas
- Gedung Hendrik
- Gedung Arif
- Gedung Naufal
- Gedung Atta_1
- Gedung Atta_2

Each segment uses a different subnet based on its host requirements.

## IP Addressing

The project applies VLSM to efficiently allocate IP addresses according to the number of required hosts.

Example:

| Network | Prefix |
|---|---|
| Gedung Dimas | /20 |
| Gedung Hendrik | /21 |
| Gedung Arif | /23 |
| Gedung Naufal | /22 |
| Gedung Atta_1 | /27 |
| Gedung Atta_2 | /25 |

## Routing

Static routing is configured between the routers to enable communication between different network segments.

The router configuration includes:

- Dimas
- Hendrik
- Arif
- Naufal
- Atta_1
- Atta_2

## Tools

This project was implemented and tested using **Cisco Packet Tracer**.

## Documentation

The repository contains the Cisco Packet Tracer project file and supporting documentation.


## Project Type

Academic Project — Computer Networks
