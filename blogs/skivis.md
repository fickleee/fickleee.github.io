---
layout: page
permalink: /blogs/skivis/index.html
title: 论文阅读笔记-SkiVis


---

## SkiVis: Visual Exploration and Route Planning in Ski Resorts


> 更新时间：2024/04/23

#### Introduction

What: A visual analytics application to interactively **explore ski slopes** and provide **routing recommendations based on user preferences**.

![image-20240429161951512](skivis.assets/image-20240429161951512.png)

<br>

#### Related Work

- Ski Visualizations

  - The painted panorama style distorts the underlying topography to emphasize certain memorable features

    ![image-20240425154152429](skivis.assets\image-20240425154152429.png)

  - Metro map

  - Preference-based visualization techniques reduce time required for route planning

  - Visualizing slopes by a color-coded line according to their difficulty

  - Display further information on individual slopes

- Routing in Geospatial Networks

<br>

#### Motivation

**Research Gap**: No analysis approach exists that enables the visual exploration of the resort and interactively provides routing recommendations based on user-defined preferences.

- The painted panorama style distorts the underlying topography to emphasize certain memorable features

- Display further information on individual slopes
- Most approaches for route planning focus on other outdoor activities such as cycling or hiking

- Neglect user-specific preferences

<br>

#### Requirement and design

- [T1]Exploration of a ski resort according to the defined features 
  
  - Double-line visual approach consisting of an outer and inner line

    ![image-20240429162214758](skivis.assets/image-20240429162214758.png)
  
  - Tooltip
  
    ![image-20240429162154170](skivis.assets/image-20240429162154170.png)
  
- [T2]Provide a ranking based on preferences toward these features 

  ![image-20240429162236569](skivis.assets/image-20240429162236569.png)

- [T3]Allow routing between two arbitrary network points Neglect user-specific preferences
  
- Dijkstra
  
- [T4]Integrate preferences into the routing algorithm
  - Compute cost for each slope according to the user preferences
  
    ![image-20240429162301626](skivis.assets/image-20240429162301626.png)
  
  - Automated/semi-automated workflow

<br>

#### Critical thinking

- New area ?
- Color encoding
- Satisfy the collective preference