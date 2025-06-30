---
layout: default
title: PULSE
permalink: /pulse/
---

<nav>
  <a href="{{ '/' | relative_url }}">Home</a> |
  <a href="{{ '/about/' | relative_url }}">About</a> |
  <a href="{{ '/contact/' | relative_url }}">Contact</a> |
  <a href="{{ '/downloads/' | relative_url }}">Downloads</a> |
  <a href="{{ '/docs/' | relative_url }}">Docs</a> |
  <a href="{{ '/pulse/' | relative_url }}">PULSE</a> |
  <a href="{{ '/startram/' | relative_url }}">STARTRAM</a> |
  <a href="{{ '/tools/' | relative_url }}">Tools</a> |
</nav>

# PULSE
### Scope of PULSE

PULSE (Powering and Unifying Long-ranged Sensor Ecosystems) is focused on evaluating support infrastructure for remote weather sensor stations. This includes methods for data collection and transmission, and for powering the system.

### Data transmission methods and diagrams
*photo here*

### Defining vocabulary

- **JSON** – “JavaScript Object Notation”, stores name-value pairs in a human readable format  
- **Meshtastic** – an open source protocol for a mesh network on top of long range radio (LoRa)  
- **Parsing data** – cleaning up raw  messages and pulling out the useful parts so the data can be used more easily in other tools or systems 
- **NodeRED** – a visual programming language based on NodeJS  

### Why Meshtastic?

Meshtastic has a widespread community of enthusiasts who have created tools, written documentation, and, most importantly, have run into all kinds of problems. This makes it an ideal tool to use for student projects. Meshtastic is an open source protocol for an ad hoc mesh network over long range radio. Any number of Meshtastic “nodes” can form a network, and nodes can be added and removed without impacting the structure of the network.

### Power system

- Creating a cheap, weatherproof enclosure with widely available materials  
- 100w Solar Panel + 50AH Battery  

### Meshtastic range

Meshtastic range depends on several factors like terrain, antenna, and environment:

Typical range: About 1 to 10km in open line-of-sight conditions.

With relay nodes: You can extend the network much farther by adding more nodes that pass messages along.

In obstructed or forested areas: Range can drop significantly, sometimes to just a few hundred meters.
