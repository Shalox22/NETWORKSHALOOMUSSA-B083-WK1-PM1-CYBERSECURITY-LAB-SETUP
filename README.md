# NETWORKSHALOOMUSSA-B083-WK1-PM1-CYBERSECURITY-LAB-SETUP
# Cybersecurity Internship – Week 1: Lab Setup & Foundations

<p align="center">
  <img src="https://img.shields.io/badge/Track-Cybersecurity-0A84FF?style=for-the-badge&logo=shield&logoColor=white" alt="Cybersecurity" />
  <img src="https://img.shields.io/badge/Week-01-FFD43B?style=for-the-badge" alt="Week 1" />
  <img src="https://img.shields.io/badge/Status-Setup%20in%20Progress-28A745?style=for-the-badge" alt="Status" />
</p>

A cybersecurity internship repository for Week 1, focused on building the lab environment, understanding core security concepts, and preparing for hands-on practice in digital forensics, networking, and ethical hacking fundamentals.

---

## Overview

This repository is designed to help interns:

- Set up a secure cybersecurity lab environment
- Understand the basic tools used in cybersecurity
- Learn about networking, operating systems, and security workflows
- Build a foundation for practical labs in later weeks
- Follow safe, ethical, and professional security practices

This project is part of the Week 1 learning track and is intended as a starter environment for cybersecurity training and experimentation.

---

## Learning Objectives

By the end of this week, interns should be able to:

- Install and configure the required security tools
- Understand the purpose of a cybersecurity lab
- Identify common security concepts such as threats, vulnerabilities, and controls
- Navigate Linux/Windows environments used in cyber labs
- Practice safe and ethical security testing
- Prepare for more advanced tasks in later internship weeks

---

## Week 1 Focus Areas

- Cybersecurity fundamentals
- Lab environment setup
- Operating system basics
- Networking basics
- Threats, vulnerabilities, and attack surfaces
- Safe lab practices and ethical conduct
- Introductory reconnaissance and security tools

---

## Recommended Tools

These are commonly used in beginner cybersecurity labs:

- Kali Linux / Ubuntu VM
- Git & GitHu
- Windows/Linux OS for testing environments
- VirtualBox or VMware Workstation
---

## Lab Setup

### 1. Install a Virtualization Platform
Install one of the following:

- VirtualBox
- VMware Workstation
- Hyper-V (for Windows systems)

### 2. Create a Security Lab VM
Recommended setup:

- OS: Kali Linux or Ubuntu
- RAM: 4GB minimum
- Storage: 50GB+
- Network mode: NAT + host-only (for isolated practice)

### 3. Install Core Tools
Install the main tools needed for your lab:

```bash
sudo apt update
sudo apt upgrade
sudo apt install nmap wireshark net-tools curl git vim
