# 🧪 CCNA Skills Integration Challenge

## 📌 Overview

This lab integrates IPv4 subnetting, IPv6 configuration, device security, and connectivity validation using Cisco Packet Tracer.

## 🎯 Objectives

* Design a subnetting scheme from 192.168.0.0/24
* Configure IPv4 and IPv6 addressing
* Secure router and switches
* Enable SSH access
* Verify full network connectivity

---

## 🌐 Subnetting Design (VLSM)

| Department | Hosts Needed | Network       | Subnet Mask | Range       |
| ---------- | ------------ | ------------- | ----------- | ----------- |
| Staff      | 100          | 192.168.0.0   | /25         | .1 – .126   |
| Sales      | 50           | 192.168.0.128 | /26         | .129 – .190 |
| IT         | 25           | 192.168.0.192 | /27         | .193 – .222 |
| Guest      | 25           | 192.168.0.224 | /27         | .225 – .254 |

---

## ⚙️ Key Configurations

### 🔐 Security Settings

* Enable secret: `Ciscoenpa55`
* Console password: `Ciscoconpa55`
* Password encryption enabled
* Minimum password length: 10
* Login blocking configured
* Banner message set

### 🌍 Router (R1)

* IPv4 + IPv6 configured on all interfaces
* SSH enabled:

  * Domain: `CCNA-lab.com`
  * RSA key: 1024 bits
  * User: `Admin1`

### 🔌 Switches (S1, S2, S3)

* VLAN 1 SVI configured
* Default gateway assigned
* Remote access secured

---

## 🖥 PC Configuration

Each PC was configured with:

* IPv4 address
* Subnet mask
* Default gateway
* IPv6 address
* Link-local address

---

## ✅ Connectivity Tests

* Successful ping between all devices
* Access to:

  * http://www.cisco.pka
  * http://www.cisco6.pka

---

## 📘 Key Learnings

* Variable Length Subnet Masking (VLSM)
* Dual-stack (IPv4 + IPv6) configuration
* Network security best practices
* SSH configuration on Cisco devices
* End-to-end connectivity validation

---

## 📂 Files Included

* Packet Tracer file (.pkt)
* Device configurations
* Network topology screenshot
