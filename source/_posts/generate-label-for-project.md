---
title: Generate Labels for  Project
date: 2024-12-17 05:38:17
categories: 
- Project Tools
tags:
---

This feature creates labels for all static texts in all objects of the selected project. Location: **[Project Node] > HMT > Generate Label For Project.**

## Prerequisites

- A Dynamics 365 solution must be open.
- Each project must have a label file added under the current model.

## Demonstration:

1. Set **Set Label For Source Code** to **True**.
2. Create a new project and add objects, filling in the Label or Text properties.
3. Edit some objects' source code, adding string types and inputting hard-coded values.
4. Navigate to **Extensions > HMT** and click the **Generate Label For Project** button.
5. Check if all static strings have been converted to labels.