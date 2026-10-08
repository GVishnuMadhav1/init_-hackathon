# CIVICFLOW AI
### AI-Powered Urban Service Demand & Resource Allocation Platform

> **Urban Operations Command Center** transforming municipal service delivery through continuous predictive intelligence, spatial clustering, and autonomous fleet optimization.

---

## 🌟 Key Architecture & Capabilities

CivicFlow AI is a software-only smart city operations platform inspired by modern command-and-control operations architectures. Unlike basic complaint-management ticketing tools, CivicFlow AI executes a **closed-loop 12-stage intelligent operational cycle**:

```
REPORT → CLASSIFY → PRIORITIZE → MAP → ANALYZE → PREDICT → ALLOCATE → RECOMMEND → DISPATCH → RESOLVE → LEARN
```

---

## 🚀 Instant Launch Instructions

You can run CivicFlow AI in two convenient ways:

### Method 1: Instant Direct Double-Click (Zero Setup)
Simply double click [`index.html`](file:///d:/new%20hackathhon/index.html) in your file explorer. It will open directly in Google Chrome, Microsoft Edge, or Mozilla Firefox with full capabilities enabled!

### Method 2: Local Web Server
```bash
node server.js
```
Then navigate in your browser to: **`http://localhost:3000`**

---

## 🏛️ Dual User Experience & Access Modes

1. **Government Operations Commander (`Gov Admin`)**:
   - Complete access to all 12 command center modules
   - Autonomous AI Fleet Reallocation solver with 1-click execution
   - Time-series demand forecasting (LSTM, Prophet, ARIMA, Baseline)
   - Real-time GIS Incident and Maintenance Fleet map
   - Hackathon stress-test scenario triggers & CSV ingestion

2. **Civil Resident Portal (`Citizen Mode`)**:
   - Real-time NLP Pre-scanning Issue Reporter (instant category & severity assessment)
   - Citizen incident tracking timeline
   - Community "Me Too / Upvote" crowd-validation to boost urgency of neighborhood problems

---

## 📊 Primary Application Modules

1. **Dashboard**: Unified Operations KPI Command Center with active, critical, pending, and resolved metrics, request trajectory trends, and sector load gauges.
2. **Map View (GIS)**: Interactive Leaflet map with custom SVG pulsing markers (🔴 Critical, 🟠 High, 🟡 Medium, 🟢 Low), DBSCAN problem hotspots, and live field team positions.
3. **Service Requests**: Detailed incident queue with search, category filtering, status updates, and interactive drawer inspection.
4. **Resources & Fleet**: Status tracking of field crews, heavy machinery (asphalt recyclers, suction tankers), and specialized equipment.
5. **AI Intelligence**: Visual 12-stage decision pipeline flowchart, NLP classification engine, multi-factor priority scoring math, and DBSCAN root cause diagnoses.
6. **Predictions**: Multi-horizon forecasting (24h, 7d, 14d, 30d, 90d) with interactive demand curves and sector risk ratings.
7. **Model Comparison**: Empirical benchmarking comparing **LSTM, Prophet, ARIMA (2,1,2), and Baseline Smoothing** across MAE, RMSE, MAPE, Accuracy, and inference latency.
8. **Autonomous AI Resource Allocation**: Mathematical optimization engine comparing Status Quo vs AI-Optimized deployment (-45.8% response time improvement).
9. **Departments**: Dedicated sub-dashboards for 7 city departments (Water, Sanitation, Roads, Drainage, Electrical, Infrastructure, Waste).
10. **Analytics & SLA**: Spatial density, temporal weekly trends, and radar SLA target performance.
11. **Notifications**: Live alert stream for critical bursts, predictive alarms, and resolution confirmations.
12. **Reports & Data Ingest**: Printable executive PDF summary and municipal CSV dataset upload/export.

---

## ⚡ Hackathon Live Simulation Scenarios

CivicFlow AI includes 5 pre-configured demo scenarios accessible via the top **⚡ Demo Scenarios** button:
- **Scenario 1**: Solid Waste Backlog in Zone 4 (Festival surge) → Triggers AI team redeployment from Zone 6 to Zone 4.
- **Scenario 2**: Industrial Main Pipe Rupture in Zone 2 → 36" trunk fracture requiring urgent emergency mobilization.
- **Scenario 3**: Flash Monsoon Storm in Zone 3 → 45mm cloudburst overloading culverts; dispatches hydro-jet suction fleet.
- **Scenario 4**: Field Team Deficit / Fleet Strike → 4 teams go offline, testing dynamic load balancing.
- **Scenario 5**: Citywide 30% Demand Peak → Multi-sector load test verifying ML forecasting capacity.
