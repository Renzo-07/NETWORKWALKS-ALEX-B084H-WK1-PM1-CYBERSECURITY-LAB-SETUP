# NETWORKWALKS-ALEX-B084H-WK1-PM1-CYBERSECURITY-LAB-SETUP
Documentation of a hands-on cybersecurity lab setup using Oracle VirtualBox and Kali Linux. Includes network configuration, troubleshooting, connectivity verification, shared folders, snapshots and technical lessons learned.


## 1. Project Overview

This project documents the design, installation, configuration and verification of a virtual cybersecurity laboratory as part of the NetworkWalks Cybersecurity Internship Programme.

The laboratory was built using Oracle VM VirtualBox as the hypervisor and Kali Linux as the primary security testing environment.

The main goal was to create a functional virtual environment where cybersecurity tools, networking concepts and practical security techniques can be explored safely without interfering with the host operating system or external networks.

The project covers the installation of the required software, configuration of a virtual NAT Network, manual IP address assignment, internet connectivity testing, shared folder integration and virtual machine snapshot management.

It also documents the technical challenges encountered during setup, the troubleshooting methods used and the solutions implemented.

## 2. Project Objectives

The primary objectives of this project are to:

* Install and configure the required virtualization software.
* Deploy Kali Linux as a virtual machine using Oracle VirtualBox.
* Create a NAT Network with the subnet `10.0.0.0/24`.
* Configure Kali Linux with a static IPv4 address of `10.0.0.2/24`.
* Configure the default gateway and DNS settings.
* Verify internet connectivity from the Kali virtual machine.
* Configure bidirectional shared clipboard and drag-and-drop functionality.
* Establish a shared folder between the Windows host and Kali Linux.
* Create a baseline snapshot of the configured virtual machine.
* Document configuration errors, troubleshooting procedures and their solutions.

## 3. Project Scope

### 3.1 Phase 1: Core Laboratory Setup

Phase 1 covers the initial deployment and configuration of the cybersecurity laboratory.

The completed setup includes:

* 7-Zip installation.
* Oracle VirtualBox installation.
* NAT Network creation and configuration.
* Kali Linux virtual machine import.
* Static IP configuration.
* Internet connectivity verification.
* Shared folder configuration.
* Virtual machine snapshot creation.

### 3.2 Phase 2: Additional Virtual Machines (Optional)

Phase 2 is reserved for future expansion of the laboratory.

The proposed activities include:

* Installing Windows 11 or Windows 10 as a virtual machine.
* Installing Windows 7 as a virtual machine.
* Installing Android 9x as a virtual machine.
* Connecting the additional machines to the virtual network.
* Performing connectivity tests between all virtual machines.
* Creating snapshots of the additional virtual machines.

Phase 2 is optional future work and is not included in the completed Phase 1 implementation.

## 4. Security and Ethical Considerations

This laboratory is intended strictly for educational purposes and authorized cybersecurity training.

All security testing and network experiments will be conducted within controlled virtual environments.

No systems, networks or devices will be tested without appropriate authorization.

