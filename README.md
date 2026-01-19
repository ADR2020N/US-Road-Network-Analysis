# US Road Network Analysis Using Graph Databases (Neo4j)

## Project Overview
This project analyzes the United States road network using graph database technology (Neo4j).  
Intersections are modeled as nodes, roads as relationships, and graph analytics techniques are applied to study connectivity, shortest paths, degree distribution, and centrality measures.

The dataset contains:
- **87,575 intersections**
- **121,961 unique roads**

The analysis demonstrates how graph-based modeling is effective for large-scale transportation networks.

## Repository Structure

US-Road-Network-Analysis/
│
├── data/
│ ├── intersections.csv
│ └── roads.csv
│
├── neo4j/
│ └── usroadnetworkdb.dump
│
├── notebooks/
│ ├── analysis.ipynb
│ └── analysis.html
│
├── report/
│ └── US_Road_Network_Report.pdf
│
├── README.md
└── .gitignore

## Tools and Technologies
- Neo4j (Graph Database)
- Cypher Query Language
- Python
- Jupyter Notebook
- Plotly (Data Visualization)

## How to Run the Project

### 1. Neo4j Database
- Restore the database using the provided `.dump` file: from here:https://drive.google.com/file/d/1oygL_uENCAtJ0cvFZAzBAyxEvGeY9Ct0/view?usp=sharing
  ```bash

###2. Jupyter Notebook

- Open the notebook located in notebooks/analysis.ipynb
- Or open analysis.html for a ready-to-view version with all outputs and visualizations.

##Key Analyses Performed

- Total number of intersections and roads
- Shortest path between intersections
- Degree distribution analysis
- Top 10 most connected intersections
- Betweenness centrality 
- Visual analytics dashboard using Plotly
