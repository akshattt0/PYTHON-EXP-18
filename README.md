# Experiment 18: Real-World and Interactive Visualizations

---

## Title

Implementation of Real-World and Interactive Data Visualization Techniques using Plotly and Python

---

## Aim

To study and implement real-world and interactive visualization techniques for better understanding of complex datasets.

---

## Objectives

- To understand interactive data visualization  
- To create treemaps for hierarchical data representation  
- To perform clustering visualization using dendrograms  
- To represent set relationships using Venn diagrams  
- To visualize flow data using Sankey diagrams  
- To analyze multi-dimensional data using 3D scatter plots  
- To represent performance metrics using radar charts  

---

## Theory

Real-world data visualization involves representing complex datasets in an intuitive and interactive way.

Interactive visualizations allow users to explore data dynamically.

Libraries used:

- **Plotly:** For interactive and dynamic visualizations  
- **Matplotlib:** For basic plotting  
- **SciPy:** For hierarchical clustering  
- **matplotlib-venn:** For Venn diagrams  

Common plots used:

- **Treemap:** Displays hierarchical data as nested rectangles  
- **Dendrogram:** Shows hierarchical clustering relationships  
- **Venn Diagram:** Represents set intersections  
- **Sankey Diagram:** Visualizes flow between stages  
- **3D Scatter Plot:** Shows relationships among three variables  
- **Radar Chart:** Displays multivariate data in a circular form  

---

## Datasets Used

### 1. Company Budget Dataset
- Columns: Department, Budget  
- Used for treemap visualization  

### 2. Clustering Dataset
- Numeric 2D data points  
- Used for dendrogram  

### 3. Set Data
- Two sets (A and B)  
- Used for Venn diagram  

### 4. Student Flow Data
- Stages: Admission → First Year → Second Year → Placed  
- Used for Sankey diagram  

### 5. Student Performance Dataset
- Columns: Study_Hours, Marks, Attendance  
- Used for 3D scatter plot  

### 6. Skill Dataset
- Skills: Python, ML, DBMS, DSA, Communication  
- Used for radar chart  

---

## Problem Statements

### 1. Treemap

Visualize department-wise budget distribution.

**Concepts Used:** px.treemap()

---

### 2. Dendrogram

Perform hierarchical clustering and visualize relationships.

**Concepts Used:** linkage(), dendrogram()

---

### 3. Venn Diagram

Show intersection between two sets.

**Concepts Used:** venn2()

---

### 4. Sankey Diagram

Visualize flow of students through different stages.

**Concepts Used:** go.Sankey()

---

### 5. 3D Scatter Plot

Analyze relationship between study hours, marks, and attendance.

**Concepts Used:** px.scatter_3d()

---

### 6. Radar Chart

Visualize skill levels in different areas.

**Concepts Used:** go.Scatterpolar()

---

## Error Observed

While using Plotly or external libraries:

```python
ModuleNotFoundError: No module named 'plotly'
```

**Reason:**
- Required library not installed  

**Solution:**
```bash
pip install plotly matplotlib-venn scipy
```

---

## Result

Successfully implemented real-world and interactive visualizations including treemap, dendrogram, Sankey diagram, 3D scatter plot, and radar chart.

---

## Conclusion

This experiment demonstrated how interactive visualizations help in better understanding complex and multi-dimensional data. Tools like Plotly make visual analysis more dynamic and insightful.

---
