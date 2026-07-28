# Firewall Integration & Monitoring using OPNsense and Wazuh SIEM

## Overview

This project was completed as part of my SOC Internship to demonstrate the deployment of a firewall, implementation of network security policies and security monitoring using Wazuh SIEM within a virtualized lab environment.
The lab was built using VMware and includes an OPNsense firewall, Wazuh Server, Linux endpoints and a Windows workstation for dashboard access. The project focuses on configuring and validating firewall policies, monitoring endpoint security events and creating custom Wazuh detections for improved visibility.

> **Note:** This project was performed entirely in an isolated VMware lab using private RFC1918 IP addresses (`192.168.x.x`). No production systems or public infrastructure were involved.

## Objectives

- Deploy an OPNsense firewall within a VMware-based virtual lab.
- Configure core network services including WAN, LAN, DHCP, and DNS.
- Route endpoint traffic through the firewall for centralized policy enforcement.
- Implement and validate firewall security policies, including GeoIP blocking, DNS-based website blocking, and administrator access control.
- Monitor endpoint security events using the Wazuh Agent deployed on OPNsense.
- Create and validate a custom Wazuh detection rule for Rootcheck events.
- Build a custom Wazuh dashboard visualization to display rule activity.
