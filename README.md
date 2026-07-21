# 🏏 T20 Match Dynamics Analyzer

An exploratory data analysis (EDA) and data visualization pipeline built in Python to analyze ball-by-ball T20 cricket data. 

## 🎯 Objective
To extract actionable match-up dynamics, phase-based team intent, and individual batter profiles from raw delivery datasets using advanced Pandas aggregation and Plotly visualizations.

## 🛠️ Tech Stack
* **Language:** Python
* **Data Processing:** Pandas, NumPy
* **Visualization:** Plotly (Express & Graph Objects), Seaborn

## 📊 Key Features & Visualizations
1. **Game Phase Intent:** Calculates strike rates across Powerplay, Middle, and Death overs.
2. **Outcome Profiling:** Stacked bar analysis of Boundary % vs. Dot Ball % per batter.
3. **Dual-Axis Match Progression:** Over-by-over timeline tracking cumulative runs against wickets lost.
4. **Normalized Radar Charts:** Multi-metric player profiling (Strike Rate, Dot %, Boundary %) normalized to a 100-point scale for comparative analysis.

## ⚙️ Data Integrity
The pipeline includes domain-specific cleaning, such as ignoring 'wides' during ball-faced calculations, ensuring 100% accuracy in official strike rate metrics.
