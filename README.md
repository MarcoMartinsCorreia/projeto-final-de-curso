# Datacenter and Automation Tasks

This repository contains the implementation and automation framework developed for my final year project in the Bachelor's degree in Computer Engineering – Networks and Telecommunications at Instituto Superior de Engenharia de Lisboa (ISEL).

## 📘 Project Overview

The project focuses on automating network configuration and management tasks within a datacenter environment, with the goal of eliminating human error, ensuring consistency, and improving operational efficiency.

The implemented framework integrates:
- **NetBox** as the Source of Truth (SoT) for structured inventory and configuration data.
- **Ansible** with **Jinja2** templates for automating the provisioning of network infrastructure.
- **Containerlab** for simulating a virtual environment with **Nokia SR Linux** devices.
- **EVPN-VXLAN** over a **leaf-spine topology** to support scalable and multitenant data center fabrics.

## 🚀 Features

- Day 0: Design and modelling of the infrastructure in NetBox.
- Day 1: Automated deployment of the underlay and overlay fabrics using Ansible.
- Day 2: Operational tasks like provisioning new services and scaling the fabric by adding switches — all done by simply updating the source of truth.

## 🧰 Technologies Used

- **NetBox** – DCIM and IPAM platform (used as Source of Truth)
- **Ansible** – Automation engine
- **Jinja2** – Templating system for configuration generation
- **Containerlab** – Virtual lab environment
- **Nokia SR Linux** – Simulated network OS
- **EVPN-VXLAN** – Overlay protocol for L2/L3 multitenancy
- **BGP Unnumbered** – Underlay routing protocol

