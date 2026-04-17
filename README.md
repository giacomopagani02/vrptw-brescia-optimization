# Vehicle Routing Problem with Time Windows (VRPTW) – Brescia Case Study

## Project Overview
This project analyzes and solves a real-world Vehicle Routing Problem with Time Windows (VRPTW) in the Brescia 2 area.

The goal is to optimize delivery routes by minimizing total travel time while respecting customer availability constraints.

## Problem Description
- 200 customers
- Single depot
- Time windows for each customer
- Objective: minimize total travel time

## Methodology
The project uses the **VRP Spreadsheet Solver (Excel-based)** to:
- Model the routing problem
- Simulate different delivery strategies
- Compare performance across scenarios

## Scenarios Analyzed
1. **Two-vehicle routing (baseline)**
2. **Geographical clustering (zone responsible)**
3. **Time-window clustering**
4. **Time-window start clustering**

## Key Results
- Best strategy: **time-window clustering**
- Delivery time reduced from ~8 hours to **~3h 45min**
- Significant efficiency improvement vs geographic grouping

## Key Insights
- Time constraints are more important than geography
- Waiting times heavily impact efficiency
- Smart clustering drastically improves routing

## Tools Used
- Excel
- VRP Spreadsheet Solver
- Optimization modeling (VRPTW)

## Full Report
See `thesis.pdf` for full details.

## Author
Giacomo Pagani
