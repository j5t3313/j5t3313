# Jessica Steele
###**Data Scientist** specializing in statistical modeling, simulation, and time-series analysis.
I build end-to-end analytics systems, from data pipelines and Bayesian inference to interactive dashboards. My portfolio applies these techniques to Formula 1, where telemetry data and complex decision-making create rich problems for ML and simulation.
📝 [Substack](https://formulasteele.substack.com) · 💼 [LinkedIn](https://linkedin.com/in/j5t33l3)
---
### Tech Stack
**Languages** · Python, R, SQL  
**ML/Stats** · NumPyro, JAX, scikit-learn, SciPy, statsmodels  
**Data** · Pandas, NumPy, FastF1, DuckDB, Parquet  
**Visualization** · Matplotlib, Plotly, Streamlit, Dash  
**Infrastructure** · MLflow, SQL Server, Railway
---
## Portfolio
### Bayesian Inference & Monte Carlo Simulation
| Project | Tech |
|---------|------|
| [f1-strategy-simulator](https://f1strategysim.com) | Bayesian tire degradation model (α + β·lap + γ·lap²) with compound-specific informative priors and MCMC posterior fitting from practice session data · AR(1) autocorrelated lap-time noise · Monte Carlo strategy simulation (100–2000 iterations) with head-to-head win rate analysis · FP2 data pipeline via FastF1 for race-weekend posterior updates |
| [stochasticPitSim](https://github.com/j5t3313/stochasticPitSim) | NumPyro/JAX Bayesian inference with NUTS sampler (500 warmup, 1000 samples) · Compound-specific degradation priors · Safety car probability modeling · 1000-iteration Monte Carlo with head-to-head win probabilities |
### Signal Processing & Time-Series Analysis
| Project | Tech |
|---------|------|
| [telemetryAnimation](https://github.com/j5t3313/telemetryAnimation) | Sector dominance calculation (~100 segments, average speed per driver) · Track layout optimization via rotation fitting · matplotlib FuncAnimation with LineCollection for efficient trace rendering · Dynamic z-ordering for layered visualization |
| [drivesense-ai](https://github.com/j5t3313/drivesense-ai) | Savitzky-Golay filter (window=5, poly=2) for derivative calculation · Steering jerk analysis for mistake detection (>2× baseline threshold) · Corner-level classification: mistakes vs. line variations vs. technique differences · Coefficient of variation for multi-lap consistency scoring |
| [f1-superclipping-viz](https://github.com/j5t3313/f1-superclipping-viz) | Super-clipping detection via dSpeed/dDistance gradient on FastF1 telemetry · Savitzky-Golay smoothing with run-length noise filtering · Dual-panel animated GIF: synchronized track map and speed trace · Four-state energy classification (deploy, super-clip, harvest, brake regen) |
### Survival Analysis & Statistical Inference
| Project | Tech |
|---------|------|
| [f1-season-opening-analysis](https://github.com/j5t3313/season_opening_analysis) | Kaplan-Meier survival estimation with pairwise log-rank tests (lifelines) · Coefficient of variation analysis on sector-level race pace · Kinematic super-clipping detection across PU families · 107% lap time filtering with low-sample-count flagging |
### Data Engineering & Pipelines
| Project | Tech |
|---------|------|
| [F1 Academy: Montreal 2026](https://formulasteele.substack.com/p/f1-academy-in-montreal-2026) | Live timing pipeline for the FIA feeder series (F1 Academy, F2, F3) · SignalR feed reverse-engineering · Bronze/Silver/Gold medallion ETL from raw JSONL to Parquet to normalized tables to analytics views · Incremental delta-state reconstruction across partial feed updates · DuckDB SQL aggregation · Raspberry Pi pit wall display as a portrait-mode Dash app |
### Predictive Modeling & Dashboards
| Project | Tech |
|---------|------|
| [ML_Race_Outcome](https://github.com/j5t3313/ML_Race_Outcome) | Ridge regression and Random Forest with 5-fold CV · Features: qualifying pace, sector times, historical performance, weather, team standings · StandardScaler normalization with SimpleImputer for missing data |
| [f1penalties.com](https://f1penalties.com) | Full-stack analytics dashboard for F1 penalty tracking · Automated data pipeline · Historical trend analysis and season comparisons |
### Data Visualization
| Project | Tech |
|---------|------|
| [spa-francorchamps-animation](https://github.com/j5t3313/spa-francorchamps-animation) | 3D circuit ribbon rendered at true surveyed elevation, colored by speed · Periodic cubic spline fit and uniform arc-length resampling of 3.7 Hz position telemetry · Hand-built orthographic camera with painter's-algorithm depth sorting and Lambertian shading · Lap-time-integrated animated trace (ds/v) |
| [f1-2026-race-pace-ridgelines](https://github.com/j5t3313/f1_racepace_ridge) | Per-team KDE ridgelines of race-pace distributions across rounds 1 to 11 · Green-flag accurate-lap filtering via FastF1 · Field-median-per-round normalization · Round-by-round reordering animation with tweened positions · Teammate-split variant |
---
<sub>✉️ jessica.5t3313@gmail.com</sub>
