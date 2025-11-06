🏥 Hospital Appointment Scheduling Optimization using MIP & DES

This project applies Operations Research (OR) techniques to optimize hospital appointment scheduling — aiming to minimize patient waiting times and improve doctor utilization efficiency.

🔍 Overview

Hospitals often face inefficiencies due to overlapping appointments, idle doctor slots, and unpredictable patient arrivals. To tackle this, we developed two complementary models:

MIP (Mixed Integer Programming) — builds an optimized schedule that reduces overall waiting and idle times.

DES (Discrete Event Simulation) — simulates real-world hospital dynamics to validate and analyze performance outcomes.

By combining these two approaches, we evaluate how optimization affects system behavior in realistic conditions.

⚙️ Project Workflow
Step 1: Dataset Creation

Used or generated synthetic Indian hospital datasets with fields like:
patient_id | doctor_id | arrival_time | consultation_time | urgency | scheduled_time

Saved datasets as .csv files (e.g., dataset_mip.csv, dataset_des.csv).

Step 2: Data Cleaning & Preparation

Handled missing values, formatted timestamps, and standardized column names using Pandas.

Introduced random synthetic data for missing attributes to ensure consistency.

Step 3: Model Implementation

MIP Model (Akash): Implemented using PuLP/Pyomo to minimize total waiting + idle time under realistic constraints.

DES Model (Akashdeep): Built using SimPy to simulate hospital flow (arrival → consultation → discharge).

Step 4: Comparison & Analysis

Tested both models on identical datasets.

Compared performance between baseline, optimized (MIP), and simulated (DES) systems.

Visualized improvements using graphs and calculated % reduction in waiting time.

📊 Results & Takeaways

Our analysis demonstrated a significant reduction in average patient waiting time through MIP optimization, validated by DES simulation.
This hybrid OR approach showcases how optimization + simulation can together enhance hospital scheduling efficiency and patient experience.

👥 Contributors

Akash – MIP Optimization Model

Akashdeep – DES Simulation Model

Akhil – Analysis, Presentation & Documentation
