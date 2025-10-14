# 📊 Title III – Older Adults Dashboard

### A Power BI Dashboard for Exploring National Trends in Services and Expenditures

---

## 🧩 Overview

This dashboard visualizes **Older Adults** data from the **Administration for Community Living’s (ACL) Title III Programs**, focusing on **Persons Served**, **Units Delivered**, and **Expenditures** across the United States.

The dataset represents a **subset (~25%) of the full Title III dataset**, concentrating on services provided to **Older Adults (Age 60+)**, such as Personal Care, Homemaker, Chore, and Home-Delivered Meals.

Data sources are connected via **AWS Athena**, with metadata-driven structuring to enable dynamic filtering, semantic consistency, and service-level insights.

---

## 📑 Dashboard Pages

### **Page 1 – Overview**

**Purpose:** Provide a national snapshot of participation and expenditure patterns.

**Key Features:**

* KPIs for *Total Persons Served*, *Units Delivered*, and *Expenditure*
* Funding source breakdown (Title III, State, Non-State)
* Year-over-year expenditure trends
* Treemap of services by expenditure share
* Dynamic insight line summarizing key metrics
* Filters: *Year*, *Service*, *Geography*

**Goal:** Help users quickly grasp national trends and the expenditure composition of services for older adults.

---

### **Page 2 – Service Explorer**

**Purpose:** Deep-dive into specific services and their performance across metrics and time.

**Key Features:**

* KPIs for persons, units, and funding sources
* Time-series charts showing service-level trends
* State-level heatmap (Persons Served or Expenditure)
* Context cards with service definitions and notes (from metadata)

**Goal:** Enable users to explore how participation and expenditure evolve across different services and states.

**Data:** Downloaded from ACL's AGID Portal - [Data Explorer](https://agid.acl.gov/data-explorer)
---

## 🚀 Future Expansion

Upcoming phases will include:

* Integration of **Caregivers of Older Adults** and **Older Relative Caregivers** data
* Addition of **interactive benchmarking** for state and regional comparison
* May add **Demographics** data in the future.

---

## 🧾 License

This project is shared for **educational and portfolio purposes**.
Please credit **Arnav Ajay** if you reference or reuse any materials.

---

## 👨‍💻 Author
**Arnav Ajay**  
💼 [LinkedIn Profile]( https://www.linkedin.com/in/arnav-ajay/ )  

---