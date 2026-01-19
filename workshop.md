---
layout: default
title: Workshop Guide
nav_order: 2
has_children: false
---

# BAC - Tableau Pulse Workshop 2026
{: .no_toc }

> Repo: https://bacrepo.github.io/bac-tab-pulse-workshop/  

## Workshop Tasks Overview
This workshop covers:
- Tableau Pulse fundamentals
- Tableau Cloud UI walkthrough
- Preparing Published Data Source (PDS)
- Building Pulse Metrics and interpreting insights
- Setting up Pulse Goals (including Dynamic Goals)
- Compound / Composite metrics for deeper analysis
- Validation of AI-generated insights
- Mobile consumption (iOS / Android)
- Pitching Tableau Pulse with business context

---

## 1) Tableau Pulse Introduction
**Instructor-led**
- Overview of Tableau Pulse
- What Pulse is designed to do (business-facing insights + metric monitoring)

![Tableau Pulse Overview](images/pulse-000.png)

---

## 2) Tableau Cloud User Interface

**Instructor-led**

- Walkthrough of Tableau Cloud interface
- Key areas: navigation, content, projects, data sources, permissions basics

> **Image placeholder:** *(Add “Tableau Cloud UI screenshot” here)*

---

## 3) Prepare Published Data Source (PDS)
**Instructor-led**
- Create a Published Data Source in Tableau Cloud using: `SuperStoreSimple.csv`
- Shared tenant naming rule:
  - Data Source Name must be renamed to the assigned number format  
    Example: `-01`, `-02`, `-03` *(Instructor will assign)*

> **Image placeholder:** *(Add “Published Data Source creation steps” here)*

---

## 4) Accessing Tableau Pulse
**Instructor-led**
- Enable **Tableau AI**
- Navigate and explore the Tableau Pulse interface

> **Image placeholder:** *(Add “Enable Tableau AI / Pulse UI” here)*

---

## 5) Create Simple Pulse Metric
**Hands-on (guided)**
- Create a new **Pulse Metric**
- Instructor explains Pulse Metric configuration options (each configurable)
- Recommended Filters:
  - `Category`
  - `Region`
  - `Segment`

> **Image placeholder:** *(Add “Metric creation screen + filter config” here)*

---

## 6) Pulse Metric Definition
**Instructor-led**
- What makes a “Metric Definition”
- How the definition influences insights and explanations

> **Image placeholder:** *(Add “Metric definition example” here)*

---

## 7) Pulse Metric Explanation
**Instructor-led**
- How to explain Tableau Pulse generated insights
- Understand the Insight structure and terminology

### Insight Group Types
- **Top Contributor**
- **Top Detractor**
- **Grouped Contributor / Detractor**
- **Polarity**
- **Significantly Decreased / Increased**

> **Image placeholder:** *(Add “Insight group examples” here)*

---

## 8) AI-Based Insight Searching
**Instructor-led**
- How to ask Tableau Pulse for insights (prompting / querying)
- Techniques to refine insight search

> **Image placeholder:** *(Add “AI insight search prompt examples” here)*

---

## 9) Follow Pulse Metric
**Instructor-led**
- Follow a Pulse Metric
- Configure digestion / delivery options

> **Image placeholder:** *(Add “Follow + digest options screen” here)*

---

## 10) Set up Tableau Pulse Goal
**Instructor-led**
- Set up Tableau Pulse Goal

Reference:
- https://help.tableau.com/current/online/en-us/pulse_goals.htm

> **Image placeholder:** *(Add “Goal setup screen” here)*

---

## 11) Set up Tableau Pulse Dynamic Goal (Part 1) — Published Data Source

### Download New Dataset: `SuperStoreTarget`
- https://drive.google.com/file/d/1oxgqayk7oZZhubzNhhB68wv1hBZZ2P2a/view

**Instructor-guided**
- Add the dataset into the data model

### Create Relationships
Make a relationship between:
- `OrderYearMonth` ↔ `TargetYearMonth`
- Then relate by:
  - `Category`
  - `Segment`

> **Image placeholder:** *(Add “Data model relationships diagram” here)*

---

## 12) Set up Tableau Pulse Dynamic Goal (Part 2) — Metric Definition
**Instructor-guided**
- Set **Measure for Goals**
- Delete **Manual Goal** (then proceed with Dynamic Goal behavior)

> **Image placeholder:** *(Add “Goal measure + delete manual goal” here)*

---

## 13) Compound / Composite Metric for Data Analysis
**Instructor-guided**
- Create a **Compound Metric** in Pulse Metric Definition

> **Image placeholder:** *(Add “Compound metric configuration” here)*

---

## 14) Insight Analysis
**Instructor-guided**
- Interpret insights correctly
- Why compound metrics matter (importance and impact on interpretation)

> **Image placeholder:** *(Add “Insight analysis examples” here)*

---

## 15) How to Prove Tableau Pulse is Correct?
**Instructor-guided**
- Test validity of generated insights per use case
- Cross-check with known calculations / baseline analysis

> **Image placeholder:** *(Add “Validation approach example” here)*

---

## 16) Mobile Application
**Instructor-guided**
- Consume Tableau Pulse content on Tableau Mobile
  - iOS
  - Android

> **Image placeholder:** *(Add “Tableau Mobile Pulse view” here)*

---

## 17) Tableau Pulse Pitching
**Instructor-led**
- Technical aspects are not enough
- Business framing is required for real adoption and success

> **Image placeholder:** *(Add “Pitching framework slide” here)*

---

# Your Turn (Hands-on Assignment)

## Dataset Download: `Electronic.csv`
- https://bacrepo.github.io/bac-tab-pulse-workshop/Electronic.csv

## Required Deliverables
1) **Define business goal**  
2) **Feature selection**
   - Identify relevant columns to **use**
   - Identify columns to **exclude**
3) **Compound metric creation**
4) **Find insights** for this dataset using Tableau Pulse
5) **Consume content on your phone** (Tableau Mobile)

> **Image placeholder:** *(Add “Your final metric + insights + mobile screenshot” here)*

---

## Notes
- Keep naming conventions consistent (especially in shared environments)
- Use recommended filters when starting, then refine based on insights
- Always validate AI-generated insights with a quick sanity check
