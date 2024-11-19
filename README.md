Sample code to demo "How to using NTN Link with Node-RED".

# General Description
NTN Link, built with Compal RMM-T1 NTN Module (SKYLO certified & Compliant with 3GPP Rel. 17 Standard) is a 2-way satellite communicator designed to transit IOT data located in area beyond cell coverage.

## Core Functionalities:
 - Bi-directional satellite data transmission
 - IoT device data sending and receiving
## Technical Specifications:
 - NTN Module: Compal RMM-T1
 - Communication Protocol: Modbus RTU
 - Communication Interface: RS485
 - Communication Parameters: Baudrate: 115200, Data bits: 8, Parity: None, Stop bits: 1
 
Sample code development tool: Node-RED    

# Dependencies
There are two dependencies on this sample flow.

- node-red-dashboard 
- node-red-contrib-modbus

# Usage
1. Configure Modbus Nodes: Ensure that the port settings of the Modbus nodes(Modbus Flex Getter / Modbus Flex Write) match the host.
2. Deploy Flow: Click the "Deploy" button in the Node-RED interface.
3. Monitor and Operate: Monitor data transmission and perform related operations through the Node-RED Dashboard interface.