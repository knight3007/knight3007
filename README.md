<h1 align="center">Hi, I'm Hậu 👋</h1>

<p align="center">
  <b>IoT & Network Engineering · Cloud Infrastructure & Security · IoT/UAV Research</b>
</p>

<p align="center">
  <a href="mailto:dothaihau2005@gmail.com"><img alt="Email" src="https://img.shields.io/badge/Email-Contact_me-D14836?logo=gmail&logoColor=white"></a>
  <a href="https://www.linkedin.com/in/knight3007/"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-knight3007-0A66C2?logo=linkedin&logoColor=white"></a>
  <a href="https://www.credly.com/users/knight3007"><img alt="Credly" src="https://img.shields.io/badge/Credly-Verified_badges-FF6B00?logo=credly&logoColor=white"></a>
</p>

Fourth-year **Computer Networks and Data Communications** student at the **University of Information Technology (UIT)**. I build **embedded IoT systems**, **enterprise network infrastructure** and **cloud security automation**, and I research **Edge AI** and **UAV cybersecurity**.

> 🔎 **Open to internships:** IoT / Embedded Systems · Network Engineering · Cloud Infrastructure

---

## 🎓 Education

**University of Information Technology (UIT)**  
**Major:** Computer Networks and Data Communications  
**Year:** Fourth-year undergraduate  
**GPA:** 7.98 / 10
<!-- TODO: add the expected graduation date, e.g. "Expected 2027". -->

---

## 🏅 Certifications

All credentials are verifiable on [Credly](https://www.credly.com/users/knight3007).

| Issuer | Credential |
| --- | --- |
| **AWS** | Certified Solutions Architect – Associate |
| **AWS** | Certified AI Practitioner |
| **AWS** | Certified Cloud Practitioner |
| **Cisco Networking Academy** | CCNA: Introduction to Networks *(course badge)* |
| **Cisco Networking Academy** | CCNA: Switching, Routing, and Wireless Essentials *(course badge)* |
| **Cisco Networking Academy** | CCNA: Enterprise Networking, Security, and Automation *(course badge)* |

**In progress:** AWS Certified SysOps Administrator – Associate (SOA-C03) 

---

## 🌏 Languages

- **English:** TOEIC Listening & Reading 700 · Speaking & Writing 270
- **Japanese:** Preparing for JLPT N4
- **Vietnamese:** Native

---

## 🚀 Featured Projects

### 🔥 [NT532 — Distributed IoT Fire Detection & Response](https://github.com/knight3007/Project-NT532.R12)

`ESP32-H2` `ESP-IDF` `OpenThread` `CoAP` `Raspberry Pi 5` `Python` `MQTT` `GitHub Actions`

A lab-scale fire-detection system. ESP32-H2 sensor and actuator nodes talk over a Thread mesh to a Raspberry Pi 5 edge station, which handles processing, coordinated response and LAN monitoring.

**Role:** Led implementation and system integration

- **Architecture:** Designed a layered system (nodes → Thread/CoAP → border router → Pi orchestrator → MQTT dashboard) that keeps node-level control separate from central orchestration.
- **Implementation:** Built ESP-IDF firmware, Thread/CoAP adapters, node command interfaces and the Pi orchestration flow for detection → aiming → actuation.
- **Quality:** Set up GitHub Actions CI for Python service tests and embedded firmware builds, plus integration and scenario test tooling.
<!-- TODO: add metrics, e.g. number of nodes, end-to-end response time, number of tests. -->
<!-- TODO: if the project uses an Edge AI model, add a bullet that says what it detects and put `Edge AI` back in the stack. -->

<summary><b>Full lifecycle</b></summary>

- **Requirements:** Sensor monitoring, event detection, node-to-station communication, response coordination and safety constraints.
- **Detailed design:** CoAP message contracts, node command interfaces, firmware-to-station data flows and orchestration states.
- **Deployment:** Lab deployment of the nodes, Thread border router, Pi services and LAN dashboard, refined through configuration and logging iterations.

**Lifecycle:** System architecture → firmware & networking → edge integration → lab deployment → validation & iteration


### 🌐 [FastPay — Multi-Site Enterprise Network](https://github.com/knight3007/FastPay-Network-Design)

`Cisco Packet Tracer` `VLAN` `OSPF` `HSRP` `GRE` `ACL` `NAT/PAT` `DHCP`

A three-site enterprise network (headquarters plus two regional branches), designed and simulated in Cisco Packet Tracer with departmental segmentation, secure inter-site links and redundant gateways.

**Role:** Network design, configuration and validation

- **Design:** Hierarchical LAN/WAN topology with access-layer and multilayer switches, redundant edge routers and GRE hub-and-spoke tunnels.
- **Configuration:** VLANs and inter-VLAN routing, OSPF, HSRP gateway redundancy, ACL policies, DHCP relay and NAT/PAT.
- **Validation:** Verified DHCP allocation, ACL restrictions, inter-site reachability and NAT-based Internet access. Tested HSRP and switch failover.
<!-- TODO: add scale, e.g. number of VLANs, subnets and devices. -->

<summary><b>Full lifecycle</b></summary>

- **Requirements:** Connectivity, departmental isolation, controlled resource access and high availability across three sites.
- **Detailed design:** VLAN/subnet and IP addressing plans, GRE tunnel layout, HSRP roles, ACL rules and NAT/PAT policies.
- **Deliverables:** Device configurations, topology diagrams, test plans and a troubleshooting guide for reproducible demos.

**Lifecycle:** Network requirements → topology & IP plan → device configuration → simulated deployment → connectivity & failover validation


### ☁️ [Azure Compliance Guard — Cloud Security Automation](https://github.com/NtQuang-23521287/NT542-CIS-Azure-Storage)

`Microsoft Azure` `Terraform` `Python` `Azure SDK` `Azure CLI` `CIS Benchmark`

A compliance toolkit for Azure Storage, Key Vault and SQL. It detects configuration drift, records audit evidence and runs approval-gated remediation.

**Role:** Led implementation and cloud security engineering

- **Architecture:** A Terraform infrastructure baseline plus a Python pipeline: resource collection → evaluation → remediation planning → audit log.
- **Implementation:** Compliance collectors and policy checks with severity classification, time-bounded exceptions and plan-first remediation through the Azure SDK and CLI.
- **Safety:** Offline tests, linting, `terraform validate` and dry-run/approval gates. Destructive cloud operations never run in CI.
<!-- TODO: add the number of compliance checks and tests. Confirm the checks follow the CIS Azure benchmark. -->


<summary><b>Full lifecycle</b></summary>

- **Requirements:** Configuration compliance, drift detection, finding severity, auditability and change approval.
- **Detailed design:** Resource checks, exception expiry, remediation plan verification and guards against unintended changes.
- **Operation:** Runs in an educational Azure lab, with repeatable review through audit logs, drift re-scans and controlled remediation.

**Lifecycle:** Security requirements → infrastructure as code → compliance implementation → cloud-lab integration → audit & validation


---

## 🛠️ Technical Skills

| Area | Technologies & tools |
| --- | --- |
| **IoT & Embedded** | ESP32 / ESP32-H2, ESP8266, Raspberry Pi, ESP-IDF, sensors, Thread, 6LoWPAN, CoAP, MQTT |
| **Networking** | TCP/IP, UDP, HTTP/HTTPS, VLAN, OSPF, HSRP, GRE, ACL, NAT/PAT, Wireshark, Cisco Packet Tracer |
| **Cloud & Infrastructure** | AWS, Microsoft Azure, Linux, OpenStack, Terraform |
| **Programming** | C/C++, Python, C# |
| **Engineering & Automation** | Git, GitHub Actions, CI pipelines, automated testing, deployment scripts |

**Currently learning:** Docker, Kubernetes, Rust and DevOps/DevSecOps practices.

---

## 🔬 Research Interests

- **IoT Networking:** Low-power protocols (Thread, 6LoWPAN, CoAP), sensor communication reliability and latency.
- **Edge AI:** Running AI inference on embedded and edge devices in distributed IoT systems.
- **UAV Cybersecurity:** Reinforcement-learning-based detection of and response to UAV communication threats, studied in simulation environments.
