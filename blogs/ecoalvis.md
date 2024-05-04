---
layout: page
permalink: /blogs/ecoalvis/index.html
title: Notes-ecoalvis

---

## ECoalVis: Visual Analysis of Control Strategies in Coal-fired Power Plants

> *Lastest Update: 25th April 2024*

#### Introduction
a novel interactive system visually analyze the **control strategies** of coal-fired power plants extracted from historical sensor data.
![image-20240504114808433](ecoalvis.assets/image-20240504114808433.png)

<br>

#### Motivation
- Environment
- Risky
- Limited datasets and strong assumptions
- Difficult to capture the potential spread of the impact of control strategies



<br>

#### **Challenges**
- Extraction of control strategies
- Cascading impact
- Time-lag-aware analysis

<br>

#### Requirement and design
- [R1] Extract the impact of control strategies with time series queries (forward)
  - Discretizing time series
  - Aligning sensor events
  - Matching partial strategy
  ![image-20240504115226296](ecoalvis.assets/image-20240504115226296.png)
- [R2] Identify responsible control strategies for anomalies in important sensors (backward)
  - Time-lag-aware breadth-first search
  ![image-20240504115211372](ecoalvis.assets/image-20240504115211372.png)
- [R3] Explore the spatial propagation of control strategy impact
  - relationship-oriented/Context-oriented
  ![image-20240504115258290](ecoalvis.assets/image-20240504115258290.png)
- [R4] Obtain the temporal cascading of control strategy impact
  - topology-temporal-separated
  ![image-20240504115336497](ecoalvis.assets/image-20240504115336497.png)
- [R5] Inspect the details of the sensor time series
![image-20240504115410821](ecoalvis.assets/image-20240504115410821.png)

#### **Critical thinking**

- Multi-dimensional visualization
- Link
- Extend to other domains with strong temporal correlation



