# Urban Mobility &amp; Economic Productivity Analysis in LATAM  Cities

**Skills and technology used:** ![Static Badge](https://img.shields.io/badge/Python-yellow?style=plastic&logo=python&logoColor=white&logoSize=auto&labelColor=black)
![Static Badge](https://img.shields.io/badge/Pandas-pink?style=plastic&logo=pandas&logoColor=white&logoSize=amg&labelColor=black)
![Static Badge](https://img.shields.io/badge/NumPy-lightblue?style=plastic&logo=numpy&logoColor=white&logoSize=amg&labelColor=black)
![Static Badge](https://img.shields.io/badge/Seaborn-blue?style=plastic)
![Static Badge](https://img.shields.io/badge/Matplotlib-blue?style=plastic)

## 📋 CONTEXT

Analyzed traffic congestion and economic data from 16 Latin American cities 
to evaluate whether urban infrastructure affects economic productivity. 

Objective: identify which cities have optimization opportunities and where 
investment could yield highest returns.

**Data sources:** TomTom Traffic Index (tomtom_traffic.csv) + OECD Cities database (oecd_city_economy.csv)

**Analysis period:** 2024

**Cities analyzed:** Bogotá, Lima, México City, São Paulo, Monterrey, Fortaleza, 
Brasília, Recife, Belo Horizonte, Curitiba, Salvador, Manaus, Belém, Montevideo, 
Santiago, La Paz

## 🔍 Findings
### Inverse Correlation: GDP vs Congestion
**Key Pattern:** Lower GDP per capita correlates with HIGHER traffic congestion

<img width="656" height="544" alt="image" src="https://github.com/user-attachments/assets/d9a07122-f7fc-4ecc-bfaa-827b3d0b2e2f" />

**Interpretation:** Wealthier cities manage congestion better; poorer cities 
suffer severe congestion.

### Critical Anomalies Identified

#### 1. Mexico City
- GDP: $21,111 (high)
- Congestion: 2,833 jams_delay minutes (extreme)
- Expected: Low congestion (based on GDP)
- **Issue:** Possible urban planning failure despite economic capacity
- **Impact:** Productivity loss, business inefficiency, pollution

#### 2. São Paulo
- GDP: $14,703 (moderate-high)
- Congestion: 1,729 jams_delay minutes (very high)
- Expected: Moderate congestion
- **Issue:** Likely infrastructure gap or population density mismatch

### Data Quality Issue
- **Representation:** 13 Brazilian cities vs 3 from other countries
- **Bias:** Dataset heavily skewed toward Brazil
- **Impact:** Findings may not be representative of full LATAM market
- **Recommendation:** Collect additional data from other countries

## 💡 IMPLICATIONS

### What This Means for Investment & Policy

1. **Prioritize Investment in Bogotá & Lima**
   - These cities have maximum efficiency gains
   - Current: Poor infrastructure + high congestion
   - With investment: Could increase productivity
   - **Recommendation:** Infrastructure improvements in public transit

2. **Audit Mexico City Immediately** (Critical)
   - Has wealth to solve congestion but hasn't
   - Possible causes: Political barriers, poor planning, lack of enforcement
   - **Recommendation:** Policy review + infrastructure redesign

3. **Investigate São Paulo**
   - Similar to Mexico City but slightly less severe
   - **Recommendation:** Infrastructure capacity audit

4. **Use Montevideo & Santiago as Benchmarks**
   - These cities manage congestion effectively
   - **Recommendation:** Study their urban planning strategies
   - **Expected impact:** Template for other cities
