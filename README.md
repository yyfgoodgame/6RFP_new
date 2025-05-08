# 6RFP: Efficient Router Fingerprinting in IPv6 Networks

![Peer Review Status](https://img.shields.io/badge/status-peer%20review-orange)

> **Status:** This repository is under peer review and will be made public once approved.

---

## 📘 Overview

**6RFP** is a lightweight tool for router fingerprinting in IPv6 networks. With only 16 probes per target, it achieves efficient and accurate identification of router vendors and models.

---

## ✨ Key Advantages

- **High Efficiency**  
  Parallel probing with adaptive rate control reduces measurement overhead by approximately 60%.

- **High Accuracy**  
  Leveraging EUI-64 and IPv6 IPID features, it achieves an overall accuracy of 85.8%, representing an 86% improvement over existing methods.

- **Wide Coverage**  
  Successfully classifies over 53% of 2.05 million router addresses in RIPE Atlas and CAIDA ITDK datasets.

- **Lightweight Design**  
  Sends only 16 packets per device, minimizing scanning footprint and reducing the likelihood of triggering security alarms.

---

