# Jessica Steele

**Data Scientist** specializing in statistical modeling, simulation, and time-series analysis.

I build end-to-end analytics systems, from data pipelines and Bayesian inference to interactive dashboards. My portfolio applies these techniques to Formula 1, where telemetry data and complex decision-making create rich problems for ML and simulation.

📝 [Substack](https://formulasteele.substack.com) · 💼 [LinkedIn](https://linkedin.com/in/j5t33l3)

---

## Tech Stack

**Languages** · Python, R, SQL  
**ML/Stats** · NumPyro, JAX, scikit-learn, SciPy, statsmodels  
**Data** · Pandas, NumPy, FastF1  
**Visualization** · Matplotlib, Plotly, Streamlit  
**Infrastructure** · MLflow, SQL Server, Railway

---

## Portfolio

### Bayesian Inference & Monte Carlo Simulation

| Project | Tech |
|---------|------|
| [f1-strategy-simulator](https://github.com/j5t3313/f1-strategy-simulator) | Mixed-effects regression with driver random effects for tire degradation · Quadratic degradation model (linear + squared tire age + fuel load) · Monte Carlo strategy simulation (100-200 iterations) with counterfactual analysis |
| [f1-strategy-sim-pro](https://github.com/j5t3313/f1-strategy-sim-pro) | Race-specific and compound-specific model fitting · Exhaustive grid search over pit windows · Regret calculation comparing actual vs optimal strategies · Safety car and undercut/overcut impact analysis |
| [stochasticPitSim](https://github.com/j5t3313/stochasticPitSim) | NumPyro/JAX Bayesian inference with NUTS sampler (500 warmup, 1000 samples) · Compound-specific degradation priors · Safety car probability modeling · 1000-iteration Monte Carlo with head-to-head win probabilities |

### Signal Processing & Time-Series Analysis

| Project | Tech |
|---------|------|
| [telemetryAnimation](https://github.com/j5t3313/telemetryAnimation) | Sector dominance calculation (~100 segments, average speed per driver) · Track layout optimization via rotation fitting · matplotlib FuncAnimation with LineCollection for efficient trace rendering · Dynamic z-ordering for layered visualization |
| [drivesense-ai](https://github.com/j5t3313/drivesense-ai) | Savitzky-Golay filter (window=5, poly=2) for derivative calculation · Steering jerk analysis for mistake detection (>2× baseline threshold) · Corner-level classification: mistakes vs. line variations vs. technique differences · Coefficient of variation for multi-lap consistency scoring |

### Predictive Modeling & Dashboards

| Project | Tech |
|---------|------|
| [ML_Race_Outcome](https://github.com/j5t3313/ML_Race_Outcome) | Ridge regression and Random Forest with 5-fold CV · Features: qualifying pace, sector times, historical performance, weather, team standings · StandardScaler normalization with SimpleImputer for missing data |
| [f1penalties.com](https://f1penalties.com) | Full-stack analytics dashboard for F1 penalty tracking · Automated data pipeline · Historical trend analysis and season comparisons |

---

<sub>✉️ jessica.5t3313@gmail.com</sub>
