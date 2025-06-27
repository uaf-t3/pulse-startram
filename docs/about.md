---
layout: default
title: About
permalink: /about/
---
<nav>
  <a href="{{ '/' | relative_url }}">Home</a> |
  <a href="{{ '/downloads/' | relative_url }}">Downloads</a> |
  <a href="{{ '/contact/' | relative_url }}">Contact</a> |
  <a href="{{ '/tools/' | relative_url }}">Tools</a> |
  <a href="{{ '/about/' | relative_url }}">About</a> |
  <a href="{{ '/docs/' | relative_url }}">Docs</a>
</nav>

# About the Projects
### How do PULSE and STARTRAM work together?

These two research projects work closely together. STARTRAM focuses on evaluating and analyzing different types of weather stations, figuring out how they perform, what kind of data they produce, and how that data can be used. PULSE, on the other hand, is focused on how to transmit that data from remote locations using long-range radio systems, making sure it can be logged and accessed reliably, even without internet or cell service.

### Who’s involved?
This project was developed by the Cyberpod, a student research team working to bridge the gap between cutting-edge research at the Alaska Center for Energy and Power (ACEP) and the motivated students in the Upward Bound and Teaching Through Technology (T3) programs.

The Cyberpod team includes Adrian Burke, Hailey Hodgins, and Petie Deveer, with mentorship and support from Dayne Broderson.

### T3 and ACEP Connections
The T3 Alaska program has emphasized environmental monitoring due to the profound impact that changes in the environment can have on life in rural Alaska. Students have carried out projects in past years that explored data collection in remote areas (Chena Hot Springs Resort); however, problems with data transmission and power in places with minimal infrastructure have prevented sensors from being deployed and maintained long-term.

### Partner Organizations
The broad applicability and direct relevance to multiple research and education efforts has allowed this work to be supported by the URSA program, along with programs at ACEP and UAF College of Engineering and Mines (CEM): 
UAF Upward Bound Program, funded by the Dept. of Education;
ARCTIC Program, funded by the Department of the Navy, Office of Naval Research under ONR award number N00014-22-1-2049
Project STORM, funded by National Science Foundation EPSCoR (RII Track-2 FEC) award number 2316402



## PULSE
### Scope of PULSE

PULSE (Powering and Unifying Long-ranged Sensor Ecosystems) is focused on evaluating support infrastructure for remote weather sensor stations. This includes methods for data collection and transmission, and for powering the system.

### Data transmission methods and diagrams
*photo here*

### Defining vocabulary

- **JSON** – “JavaScript Object Notation”, stores name-value pairs in a human readable format  
- **Meshtastic** – an open source protocol for a mesh network on top of long range radio (LoRa)  
- **Parsing data** – *(definition needed)*  
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

## STARTRAM
