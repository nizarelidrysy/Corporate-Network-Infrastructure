# SEBN-MA Corporation Network Infrastructure & Architecture:

A comprehensive documentation and implementation repository detailing the industrial network infrastructure of the SEBN-MA manufacturing plant in Tangier, Morocco. This project was compiled during a professional engineering internship within the Information Technology department.

---

## Project Overview

This repository houses the network architecture blueprints, structural diagrams, configuration scripts, and optimization analyses designed for the SEBN-MA production facility. It acts as both an academic showcase and a practical guide to industrial-grade, highly available network environments in the automotive wiring sector.

The focus is on balancing reliable real-time data flow for manufacturing execution systems (MES), ensuring robust security zones, and establishing redundant core infrastructure to prevent production downtime.

---

## Key Architectural Pillars

The design models a highly resilient, multi-tiered enterprise architecture tailored for a heavy manufacturing environment:

* Three-Tier Hierarchical Model: Core, Distribution, and Access layer separation to isolate high-speed switching from local endpoint policy enforcement.
* Industrial Redundancy (HA): Dual-homed connections, EtherChannel link aggregation, and Gateway Redundancy (in Active/Active configuration) to ensure zero single points of failure on the production floor.
* VLAN Segmentation: Strict logical isolation between corporate administrative traffic, engineering services, and IoT/machine-level networks to improve security and limit broadcast domains.
* Secure Boundary Control: Demilitarized Zones (DMZs) and access control lists (ACLs) managing traffic between external vendor diagnostic loops and internal operational technology (OT) zones.

---

## Repository Structure

```text
├── Documentation/
│   ├── Missions.pdf                        # My missions during the internship design doc
│   └── Internship_Technical_Report.pdf     # Summary of objectives, methodologies & findings
├── Network Topology/
│   ├── sebn_main_plant_topology.pkt        # Packet Tracer master project files
│   └── physical_layout_map.png             # Visual map of physical machines placements (MAO/WAO/CAO)
│   └── backup_process.png                  # How SEBN-MA handles it's backup schedules
└── Cisco Toolbox/
    └── core_switch_configuration.pdf       # Cisco IOS commands used
```

---

<div align="center">
  <p>Engineered with dedication by Nizar EL IDRYSY ❤️</p>
</div>
