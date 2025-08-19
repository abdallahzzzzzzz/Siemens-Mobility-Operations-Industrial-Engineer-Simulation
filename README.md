# Siemens Mobility Operations Industrial Engineer Simulation  

## Introduction  
This project replicates real-world tasks of an [**Operations Industrial Engineer**](https://www.theforage.com/simulations/siemens-mobility/operations-industrial-engineering-xh22) at Siemens Mobility as part of the *Project Velocity – Aurora Express* initiative.  

Siemens Mobility is a leading provider of transport solutions, continuously developing its portfolio in rolling stock, rail automation, electrification, turnkey systems, intelligent traffic systems, and related services. With digitalization, Siemens Mobility enables operators worldwide to build intelligent infrastructure, enhance sustainability, improve passenger experience, and ensure availability.  

During this simulation, I stepped into the role of an **Operations Industrial Engineer**, tasked with identifying inefficiencies and proposing improvements in the Aurora Express’s assembly line.  

![Intro Visual](images/intro/siemens_engineer_efficiency.png)

---

## Task 1 — Time Study & Bottleneck Analysis  

### Background & Goal  
On Monday morning, the team gathered for a critical meeting led by Jamal, the senior operations manager. The challenge was clear:  
- Identify inefficiencies in the **Aurora Express assembly line**.  
- Analyze time study data to find bottlenecks and propose solutions.  
- Ensure the project meets — and surpasses — benchmarks for efficiency and sustainability.  

### Key Findings  
- **Step 14 (Mount wheel to axle)** → **Primary bottleneck** due to significantly higher average time.  
- **Step 6 (Lubricate wheel bearings)** → **High variability** (CV outlier).  

**Visuals:**  
![Bottleneck Time Analysis](images/task1_visuals/time_bottleneck.png)  
*Interpretation: Step 14 has the highest average time, creating a throughput bottleneck.*  

![Variability Analysis](images/task1_visuals/variability_bottleneck.png)  
*Interpretation: Step 6 shows high relative variability, reducing process consistency.*  

### Recommendation  
- **Step 14 (Mount wheel to axle):** Initially proposed automation to reduce manual handling.  
- **Step 6 (Lubricate wheel bearings):** Standardization of lubrication tools/methods to reduce variability.  

---

## Task 2 — Layout Reconfiguration  

### Background & Goal  
Following Task 1, full automation for Step 14 was deemed **cost- and time-prohibitive**. Instead, the focus shifted to **reconfiguring the assembly line layout** to improve efficiency without expensive equipment investments.  

### Layout Comparison  

**Original Layout (Limitations):**  
- Tools not pre-positioned, causing repeated setup.  
- Inspection step inline, blocking downstream tasks.  
- Step 14 bottleneck due to unbalanced flow.  
- Harder for QA and supervisors to monitor.  

**Proposed Layout (Improvements):**  
- Convert to **assembly line process layout** with defined workstations.  
- Pre-position tools and small-parts stock at stations.  
- Separate inspection workstation to prevent blocking Step 4.  
- Group Steps 4–9 in the first station (longest block), balance flow to Step 14.  
- Add **“Assembled Product” area** to free workstations quickly.  

**Visuals:**  
![Original Layout](images/task2_layout/Original_Layout.png) ![Proposed Layout](images/task2_layout/Proposed_Layout.png)  

| Aspect                | Original Layout                        | Proposed Layout                            |
|------------------------|-----------------------------------------|---------------------------------------------|
| Tools/Setup           | Repeated setup each cycle              | Pre-positioned tools, reduced setup         |
| Inspection            | Inline, blocking downstream            | Separate station, prevents delays           |
| Task Distribution     | Unbalanced, Step 14 bottleneck         | Balanced flow, Step 14 no longer bottleneck |
| Oversight             | Harder for QA/supervisors              | Easier monitoring, clear segmentation       |
| Throughput            | Slower, inconsistent                   | Faster, more consistent                     |

### Rationale & Benefits  
- **Efficiency Gains:** Reduced setup/waiting, streamlined flow.  
- **Workflow Stability:** Balanced stations eliminate bottlenecks.  
- **Improved Oversight:** Easier QA/supervision of processes.  
- **Sustainability:** Less wasted motion and waiting → long-term productivity.  

---

## Conclusion  
This project combined **data-driven analysis (Task 1)** with **practical process design (Task 2)** to address bottlenecks in the Aurora Express assembly line.  

- **Task 1:** Identified bottlenecks and variability using time study analysis.  
- **Task 2:** Proposed a feasible layout reconfiguration that relieves the Step 14 bottleneck without costly automation.  

By blending statistical insight with engineering design, this work demonstrates how industrial engineers can deliver both **efficiency** and **sustainability** in high-impact projects.  
