# VLAN Segmentation Lab – Coffee Shop Guest WiFi

## Overview
This lab simulates a small coffee shop network that provides guest WiFi while protecting internal business resources.

## Objective
Allow guest users to access the internet while preventing access to internal devices.

## Scenario
Small businesses often offer guest WiFi for customers. Without proper segmentation, guest devices could access internal systems such as POS terminals, printers, or administrative machines.

This lab demonstrates VLAN segmentation to separate guest and internal traffic while maintaining internet access.

## Technologies Used
- VLAN segmentation
- Router-on-a-stick
- Inter-VLAN routing
- NAT
- ACLs
- Cisco Packet Tracer

## Validation
The lab verifies:
- Internal network communication works
- Guest network reaches internet
- Guest network blocked from internal resources

## Structure
- `topology/` → Packet Tracer lab file
- `screenshots/` → configuration and validation steps

## Key Takeaway
This design keeps the architecture clean and scalable while improving security for small business environments.