# Wireshark Network Traffic Analysis

## Project Overview

This project demonstrates practical network traffic analysis using Wireshark. DNS, HTTP, and TCP traffic were analyzed using packet inspection, display filters, and custom coloring rules.

## Analysis Performed

### DNS Traffic Analysis
- Analyzed DNS request and response packets.
- Inspected source and destination IP addresses.
- Examined DNS packet details.

### HTTP Traffic Analysis
- Filtered and analyzed HTTP traffic.
- Inspected HTTP requests and responses.
- Examined source, destination, and port information.

### TCP Traffic Analysis
- Analyzed TCP packets and connection behavior.
- Examined TCP flags and packet details.
- Used SYN and FIN filters for TCP traffic analysis.

## Wireshark Filters

**TCP SYN Filter**
tcp.flags.syn == 1
**TCP FIN Filter**
tcp.flags.fin == 1

**Custom Coloring Rules**

Custom Wireshark coloring rules were configured to visually identify specific TCP packets.
tcp.flags.syn == 1 → Green
tcp.flags.fin == 1 → Grey
This makes TCP connection-related packets easier to identify during traffic analysis.

**Tools Used**
Wireshark
Windows
