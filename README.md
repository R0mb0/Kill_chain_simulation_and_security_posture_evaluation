Urbino`s University - Computing and digital innovation - IT security

<div align="center">
  <h1>☠️Kill chain simulation and security posture evaluation⛓️</h1>

  [![Codacy Badge](https://app.codacy.com/project/badge/Grade/2223402176bb4238a296015e69bab52a)](https://app.codacy.com/gh/R0mb0/Kill_chain_simulation_and_security_posture_evaluation/dashboard?utm_source=gh&utm_medium=referral&utm_content=&utm_campaign=Badge_grade)
  [![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://github.com/R0mb0/Kill_chain_simulation_and_security_posture_evaluation)
  [![Open Source Love svg3](https://badges.frapsoft.com/os/v3/open-source.svg?v=103)](https://github.com/R0mb0/Kill_chain_simulation_and_security_posture_evaluation)
  [![MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/license/mit)
  [![Donate](https://img.shields.io/badge/PayPal-Donate%20to%20Author-blue.svg)](http://paypal.me/R0mb0)

  <p>
    Academic pentesting &amp; security evaluation lab for a Master's Cybersecurity course. Simulates a Cyber Kill Chain in an isolated VirtualBox network (Kali vs Apache/PHP/MySQL). Explores web attacks (SQLi, XSS, Command Injection), log analysis, and secure coding remediation to assess and improve the overall system security posture.
  </p>
</div>

<div align="center">
  <a href="http://paypal.me/R0mb0">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://github.com/R0mb0/Support_the_dev_badge/blob/main/Badge/SVG/Support_the_dev_badge_Dark.svg">
      <source media="(prefers-color-scheme: light)" srcset="https://github.com/R0mb0/Support_the_dev_badge/blob/main/Badge/SVG/Support_the_dev_badge_Light.svg">
      <img alt="Saved you time? Support the dev" src="https://github.com/R0mb0/Support_the_dev_badge/blob/main/Badge/SVG/Support_the_dev_badge_Default.svg">
    </picture>
  </a>
</div>


## 1. Network Topology & Architecture
To ensure a safe and controlled environment, the penetration testing laboratory is deployed on **VirtualBox** using an **Internal Network** configuration (named `LabSicurezza`). This guarantees total isolation from the host machine and the external internet.

### 1.1 IP Addressing Plan (Subnet: 192.168.100.0/24)
* **Attacker Machine (Kali Linux):** * IP: `192.168.100.10`
  * Role: Execution of vulnerability scanning, enumeration, and exploitation.
* **Victim Machine (Vulnerable Server):** * IP: `192.168.100.20`
  * Role: Hosting vulnerable web applications and services to monitor logs and implement defense strategies.
