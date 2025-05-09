# 🚴‍♀️ Ingesting Real-Time Data with Eventstream in Microsoft Fabric

This repository documents the completion of a hands-on lab that demonstrates how to build a real-time data pipeline using **Eventstream** and **Eventhouse** in Microsoft Fabric. The lab simulates data ingestion from a live stream of bike-share activity in a city.

## 🎯 Purpose of the Lab

The objective of this lab was to ingest, transform, and store **real-time event data** using Microsoft Fabric’s Real-Time Intelligence capabilities, specifically focusing on the following components:
- Eventstream (for streaming ingestion and transformations)
- Eventhouse (for persistent storage and KQL-based querying)
- Kusto Query Language (KQL) for analysis

## 🧠 What I Learned

During this lab, I worked through an end-to-end real-time solution and gained hands-on experience with:

- **Creating and Managing Workspaces**  
  Learned how to set up a Fabric workspace with Real-Time Intelligence features enabled.

- **Building a Real-Time Pipeline with Eventstream**  
  Connected to a **sample bike-share dataset** and created a real-time stream using Eventstream, which automatically captured and routed data to a destination.

- **Storing Data in an Eventhouse (KQL Database)**  
  Used an Eventhouse to store raw and transformed streaming data in structured KQL tables for analysis.

- **Real-Time Transformations with Grouping**  
  Applied a **Group By transformation** to aggregate the number of bikes observed per street in 5-second tumbling windows — demonstrating temporal stream processing.

- **Querying Real-Time Data with KQL**  
  Used **KQL queries** to:
  - View raw and transformed data
  - Analyze temporal windows
  - Summarize total bikes per location over time

## ✅ Outcome

At the end of the lab, I built a real-time streaming pipeline that:
- Captures continuous event data from a source
- Transforms and aggregates data as it flows
- Loads results into a queryable KQL table
- Supports fast, flexible analysis using temporal logic

This scenario simulates a use case common in **IoT, smart cities, and mobility systems**, and is directly applicable to real-time operational dashboards or alerting systems.

## 🤝 Let’s Connect

If you’re exploring real-time streaming in Microsoft Fabric or interested in event-driven architectures, I’d love to connect and exchange ideas.  
Feel free to reach out via [LinkedIn](https://www.linkedin.com/in/eyilan/) — let’s talk Eventstream and Fabric!
