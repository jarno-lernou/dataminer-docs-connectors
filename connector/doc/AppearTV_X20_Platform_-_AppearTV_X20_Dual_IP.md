---
uid: Connector_help_AppearTV_X20_Platform_-_AppearTV_X20_Dual_IP
---

# AppearTV X20 Platform - AppearTV X20 Dual IP

This connector can be used to view information on and configure settings of **Dual IP cards** connected to the AppearTV X20 chassis. This includes information regarding IP inputs and outputs, services, IP interfaces, physical ports and virtual ports.

## About

The connector uses an **HTTP** connection. This connection uses the Firewall API of the Dual IP card to retrieve information from the card and configure settings on the card. The information transfer is performed using JSON.

Note: This connector is automatically generated by the AppearTV X20 Platform connector, from range 1.0.0.x onwards.

### Product Info

| **Range**     | **Device Firmware Version** |
|----------------------|-----------------------------|
| 1.0.0.x              | 1.10.2-1433-g641c1cd        |
| 1.0.1.x              | 1.10.2-1433-g641c1cd        |
| 1.1.0.x              | 1.12                        |
| 1.2.0.x \[SLC Main\] | 2.x.x                       |

## Installation and configuration

### Creation

This connector is **automatically generated** by the parent connector **AppearTV X20 Platform**.

## Usage

### Dual IP Inputs - Services

This page contains a tree control with the **IP inputs** of the card and the **services per input**. It allows you to view and configure information related to the inputs.

### Dual IP Inputs

This page contains a table with configurable information related to the IP inputs.

### Dual IP Outputs - Services

This page contains a tree control with the **IP outputs** of the card and the **services per output**. It allows you to view and configure information related to the outputs, and to add, change or remove services on a specific output.

### Dual IP Outputs

This page contains a table with configurable information related to the IP outputs.

### Dual IP Outputs Redundancy

This page contains two tables with configurable information related to the Dual IP input redundancy sources.

### Dual IP Interfaces

This page contains a table with information related to the IP interfaces of the card. Adjusting the configuration in this table is not possible, as this could accidentally disconnect the DMA.

### Dual IP Ports

This page contains two tables with information about **physical and virtual ports**. For virtual ports, the **Allow Seamless** and **Allow Cloned** settings can be adjusted.