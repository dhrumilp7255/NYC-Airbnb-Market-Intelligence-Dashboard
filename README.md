# 🏙 NYC Airbnb Market Intelligence Dashboard

## 📊 Project Overview

This project presents an interactive Tableau dashboard suite analyzing the NYC Airbnb marketplace. The analysis explores listing supply distribution, pricing patterns, neighborhood segmentation, and host concentration behavior to uncover key market dynamics.

The dashboard is designed to provide both high-level executive insights and detailed segmentation analysis.

---

## 🎯 Objectives

- Understand geographic clustering of Airbnb listings across NYC
- Analyze pricing variations by neighborhood and property type
- Evaluate room-type distribution across boroughs
- Identify host concentration and multi-listing behavior
- Quantify market dominance by top hosts

---

## 📈 Dashboard Components

### 1️⃣ Executive Market Overview
- Total Listings
- Total Hosts
- Total Beds
- Average Price Per Listing
- Listings by Room Type
- Neighborhood Overview Map

### 2️⃣ Geographic Supply Distribution
- Listing Density Map
- Listings by Neighborhood
- Total Listings by Area

### 3️⃣ Property Type Pricing & Capacity Analysis
- Average Price by Property Type
- Average Beds by Property Type

### 4️⃣ Room Type Segmentation
- Room Type Distribution
- Room Type vs Property Type Relationship

### 5️⃣ Host Concentration & Market Dominance
- Top 10 Hosts by Number of Listings
- Average Listings per Host
- Unique Hosts per Neighborhood
- Hosts by Room Type and Neighborhood

### 6️⃣ Host Activity & Pricing Trends Over Time
- Number of Hosts by Neighborhood
- Average Price Trends Over Years

---

## 🧮 Key Calculations Used

- FIXED LOD: Total Listings per Neighborhood
- FIXED LOD: Unique Hosts per Neighborhood (COUNTD)
- Average Listings per Host = COUNT(Listings) / COUNTD(Host ID)
- Average Price per Neighborhood (FIXED LOD)
- Rounded Average Beds per Property Type

---

## 🔍 Key Insights

- Manhattan shows highest pricing concentration.
- Listing density is unevenly distributed across boroughs.
- Entire homes dominate supply in premium neighborhoods.
- A small group of hosts control a disproportionate share of listings.
- Property type strongly influences both capacity and pricing.

---

## 🛠 Tools Used

- Tableau
- Excel / CSV Data Source
- Calculated Fields
- LOD Expressions
- Geospatial Mapping
- Dashboard Filters & Interactive Controls

---

## 📂 Files Included

- `NYC_Airbnb_Market_Intelligence.twbx` – Packaged Tableau Workbook
- Dashboard Screenshots
- README Documentation

---

## 🚀 How to View

Go to: (link)

---

## 💡 Project Type

Business Intelligence (BI) / Exploratory Data Analysis (EDA)

This project demonstrates dashboard design, data segmentation, geospatial analysis, calculated fields, and business storytelling using Tableau.
