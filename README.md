1. Team
- Lucía González Dávila
- Ignacio Miguel Landaluce Gortázar
- Javier Larrabe Valdivia
- Santiago Robles Peñamaría
- Isabel Rodríguez Viader


2. Demo
https://github.com/luciagonzadavi-code/Inteligencia-empresarial-II/deployments/github-pages

3. Project Overview

This project builds an agentic Competitive Intelligence (CI) system to support Inditex's strategic decision regarding the expansion of Lefties.

The system automates part of the CI pathway (Early Warning System – Phase 6) by monitoring key competitive and regulatory signals and transforming them into actionable alerts.


4. Indicators Monitored

The agent tracks three key indicators:

A) Shein Pricing Pressure
   - Based on average price of basic t-shirts

B) Competitor Operational Expansion
   - Based on job postings in logistics and operations

C) Regulatory Risk (EU Tariffs)
   - Based on policy delays and status


5.  How the System Works

1. Data is collected from structured CSV files (OSINT simulation)
2. Python processes the data and computes indicators
3. Thresholds generate alerts (GREEN / YELLOW / RED)
4. Output is stored in `alerts.json`
5. A web interface displays results using GitHub Pages


6. How to Run Locally

1. Open terminal
2. Navigate to project folder:
cd '/Users/luciagonzalezdavila/Library/CloudStorage/OneDrive-UFV/Archivos de Santiago Robles Peñamaría - scripts'
3. Run Python script
python main. py
4. Launch local server
python -m http.server 8000
5. Open browser
http://localhost:8000
