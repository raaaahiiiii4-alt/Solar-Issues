# Topics to Be Studied — Kerala Solar Surplus Crisis Project
## Chronological Learning Path: Beginner → Advanced (20-Week Program)

**Project:** Kerala Solar Surplus Crisis — System Integration & Flexibility Ecosystem Design  
**Date:** 2026-11-20 (IST)  
**Scope:** Complete knowledge base required before initiating solution design, implementation planning, or policy work  
**Source Basis:** `Problem_Statement.md`, `Problem-Self_Identified.md`, `Problem-General_World.md` (80+ sources)  
**Method:** Chronological progression — each week builds on previous weeks

---

## WEEK 1: MATHEMATICAL & PHYSICAL FOUNDATIONS (Prerequisites)

### 1.1 Mathematics & Data Science Basics
- [ ] Linear algebra: matrices, eigenvalues, eigenvectors (for power flow, modal analysis)
- [ ] Calculus: derivatives, integrals, differential equations (for dynamics, optimization)
- [ ] Probability & statistics: distributions, hypothesis testing, confidence intervals (for forecasting, reliability)
- [ ] Time series analysis: ARIMA, seasonal decomposition, stationarity (for load/solar forecasting)
- [ ] Optimization theory: linear programming, convex optimization, KKT conditions (for dispatch, sizing)
- [ ] Numerical methods: Newton-Raphson, Gauss-Seidel, sparse matrices (for power flow)

### 1.2 Physics & Electrical Engineering Basics
- [ ] AC circuit theory: phasors, impedance, power factor, complex power (P, Q, S)
- [ ] Three-phase systems: balanced/unbalanced, symmetrical components, per-unit system
- [ ] Electromagnetic theory: Faraday's law, inductance, capacitance, skin effect
- [ ] Thermodynamics: Carnot efficiency, heat engines, exergy (for thermal plants, storage)
- [ ] Electrochemistry basics: redox reactions, Nernst equation, Faraday's laws (for batteries, hydrogen)
- [ ] Semiconductor physics: p-n junctions, MOSFETs, IGBTs (for inverters, converters)

### 1.3 Programming & Data Analysis Fundamentals
- [ ] Python: NumPy, Pandas, Matplotlib, SciPy (data manipulation, visualization)
- [ ] SQL: queries, joins, time-series databases (InfluxDB, TimescaleDB)
- [ ] Version control: Git, GitHub (collaboration, reproducibility)
- [ ] Jupyter Notebooks: literate programming, documentation
- [ ] Virtual environments: conda, pip, requirements.txt (reproducibility)
- [ ] Basic ML: scikit-learn, train/test split, cross-validation (for forecasting)

### 1.4 Economics & Finance Fundamentals
- [ ] Time value of money: PV, FV, annuity, perpetuity, NPV, IRR
- [ ] Capital budgeting: payback, profitability index, sensitivity analysis
- [ ] Cost of capital: WACC, CAPM, risk-free rate, equity risk premium, beta
- [ ] Project finance: DSCR, LLCR, PLCR, debt sculpting, cash flow waterfalls
- [ ] Risk & return: VaR, Monte Carlo, scenario analysis
- [ ] Electricity market economics: merit order, marginal pricing, locational marginal pricing (LMP)

### 1.5 Legal & Regulatory Fundamentals
- [ ] Constitutional basis: Union/State/Concurrent lists (Electricity in Concurrent)
- [ ] Statute hierarchy: Act → Rules → Regulations → Orders → Guidelines
- [ ] Regulatory bodies: CERC, SERCs, CEA, POSOCO, RPCs, APC
- [ ] Judicial review: APTEL, High Courts, Supreme Court
- [ ] Contract law basics: offer/acceptance, consideration, force majeure, change in law
- [ ] Administrative law: natural justice, speaking orders, reasoned decisions

### 1.6 Environmental & Climate Science Basics
- [ ] Climate science: greenhouse effect, carbon cycle, IPCC scenarios (SSP/RCP)
- [ ] Hydrology: water cycle, monsoon dynamics, reservoir operations, evaporation
- [ ] Ecology basics: biodiversity, ecosystem services, EIA process
- [ ] Land use: classification, conversion, forest rights, rehabilitation
- [ ] Kerala geography: Western Ghats, 44 rivers, 44 reservoirs, monsoon patterns

### 1.7 Project Management & Data Science Basics
- [ ] Project lifecycle: initiation, planning, execution, monitoring, closure
- [ ] Risk management: identification, assessment (probability×impact), mitigation
- [ ] Data quality: completeness, accuracy, timeliness, consistency, granularity
- [ ] Documentation: technical reports, regulatory filings, executive summaries
- [ ] Stakeholder analysis: RACI, power/interest grid, communication plans

---

## WEEK 2: POWER SYSTEM FUNDAMENTALS (Core Theory)

### 2.1 AC Power System Theory
- [ ] Per-unit system: base selection, impedance conversion, advantages
- [ ] Symmetrical components: positive/negative/zero sequence, fault analysis
- [ ] Power flow equations: P-Q-V-θ relationships, Jacobian matrix
- [ ] Generator modeling: synchronous machine (d-q axis, transient/subtransient reactance)
- [ ] Transformer modeling: equivalent circuit, tap changing, phase shift
- [ ] Line modeling: π-model, surge impedance loading, voltage regulation

### 2.2 Grid Frequency Control
- [ ] Swing equation: rotor dynamics, inertia constant H, damping D
- [ ] Primary response: governor droop, deadband, response time (0-30 sec)
- [ ] Secondary response: AGC, ACE, bias setting, tie-line control (30 sec–15 min)
- [ ] Tertiary response: economic dispatch, rescheduling (>15 min)
- [ ] Frequency containment: RoCoF, nadir, steady-state deviation limits (IEGC: 49.90–50.05 Hz)
- [ ] Inertia estimation: measurement, synthetic inertia, fast frequency response (FFR)

### 2.3 Voltage Control & Reactive Power
- [ ] Reactive power sources: generators, synchronous condensers, SVC/STATCOM, capacitors/reactors, OLTC, inverters
- [ ] Voltage stability: PV curves, QV curves, voltage collapse proximity
- [ ] Voltage control hierarchy: primary (AVR), secondary (VVC), tertiary (dispatch)
- [ ] CEA Grid Standards voltage bands (765kV: 728–800, 400kV: 380–420, 220kV: 198–245, 132kV: 122–145, 110kV: 99–121)
- [ ] Reactive power planning: static vs dynamic, centralized vs distributed

### 2.4 System Stability Fundamentals
- [ ] Transient stability: equal area criterion, critical clearing time, CCT
- [ ] Small-signal stability: eigenvalue analysis, damping ratio, oscillatory modes
- [ ] Voltage stability: saddle-node bifurcation, continuation power flow
- [ ] Frequency stability: under-frequency load shedding (UFLS), df/dt relays
- [ ] Sub-synchronous resonance (SSR): torsional interaction, countermeasures
- [ ] Protection coordination: overcurrent, distance, differential, islanding detection

### 2.5 Short-Circuit Analysis & System Strength
- [ ] Short-circuit calculation: IEC 60909, symmetrical/asymmetrical current
- [ ] Short-circuit ratio (SCR): SCR = S_sc / S_rated, weighted SCR for multiple IBRs
- [ ] Strong/weak/very weak grid: SCR >3 / <2 / <1.5
- [ ] Grid-forming vs grid-following inverter requirements by SCR
- [ ] Synchronous condenser deployment: sizing, siting, control modes

---

## WEEK 3: RENEWABLE ENERGY BASICS (Solar & Wind)

### 3.1 Solar PV Fundamentals
- [ ] PV physics: p-n junction, bandgap, Shockley-Queisser limit, temperature coefficient
- [ ] Module technologies: mono/poly PERC, TOPCon, HJT, bifacial, degradation modes
- [ ] Irradiance components: GHI, DNI, DHI, plane-of-array (POA) irradiance
- [ ] Temperature models: NOCT, Sandia, Faiman (cell temperature from ambient/wind)
- [ ] Inverter topologies: string, central, microinverter, power optimizer
- [ ] MPPT algorithms: perturb & observe, incremental conductance, fractional VOC/ISC

### 3.2 Wind Power Fundamentals
- [ ] Aerodynamics: Betz limit, power coefficient Cp(λ,β), tip-speed ratio
- [ ] Turbine types: fixed-speed (SCIG), variable-speed (DFIG, PMSG), gearless
- [ ] Power curve: cut-in, rated, cut-out, power coefficient Cp(λ,β)
- [ ] Wake effects: Jensen, Park, Ainslie models; wind farm layout optimization
- [ ] Wind resource assessment: Weibull distribution, WAsP, CFD (WindSim, OpenFOAM)

### 3.3 Power Electronics for RE Integration
- [ ] Inverter topologies: 2-level, 3-level NPC, MMC, CHB (for utility-scale)
- [ ] Grid-following (GFL) vs Grid-forming (GFM) vs Grid-supporting control
- [ ] PLL design: SRF-PLL, DSOGI-PLL, dynamic response, weak grid stability
- [ ] Current control: PI in dq-frame, PR control, resonance suppression
- [ ] LCL filter design: resonance damping, grid impedance variation

### 3.4 RE Resource Assessment & Forecasting Basics
- [ ] Solar resource: satellite (NSRDB, SARAH), reanalysis (ERA5, MERRA-2), ground stations
- [ ] Wind resource: mesoscale (WRF), microscale (WAsP, CFD), long-term correction
- [ ] Forecasting horizons: nowcasting (0-1hr), intra-day (1-6hr), day-ahead, week-ahead
- [ ] Error metrics: MAE, RMSE, MAPE, nMAE, nRMSE, pinball loss (probabilistic)
- [ ] Uncertainty quantification: ensembles, quantile regression, prediction intervals

---

## WEEK 4: GRID INTEGRATION OF VARIABLE RENEWABLE ENERGY (VRE)

### 4.1 VRE Integration Physics
- [ ] Net load concept: Net Load = Demand - (Solar + Wind)
- [ ] Duck curve: midday belly, evening neck, ramp magnitude/duration
- [ ] California duck curve evolution: 2015→2025, 6 GW belly → 24 GW neck
- [ ] Curtailment definition: technical vs economic vs operational vs commercial
- [ ] System Non-Synchronous Penetration (SNSP): Ireland 75% limit, India implicit limit

### 4.2 Curtailment Mechanisms & Classification
| Type | Trigger | Kerala Relevance |
|------|---------|------------------|
| Technical (System-wide) | Frequency >50.05 Hz, SNSP limit, reserve shortage | High — freq >50.05 Hz 4+ hrs |
| Technical (Local/Constraint) | Line loading >95%, voltage >limits, ICT overload | High — pooling station overvoltage |
| Economic | Negative prices, merit order | Emerging — G-DAM ₹2.7–4.2/kWh |
| Operational | Forecast error, maintenance | High — 8 GW/hr cloud ramps |

### 4.3 Grid Stability with High IBR Penetration
- [ ] Inverter types: Grid-following (GFL) vs Grid-forming (GFM) vs Grid-supporting
- [ ] Fault Ride-Through (FRT): LVRT (0.15 pu/250ms), HVRT (1.2 pu/500ms), reactive current injection (2%/1% V dip)
- [ ] Frequency ride-through: 47.5–52 Hz operation, RoCoF withstand
- [ ] Oscillation modes: sub-synchronous (2-4 Hz torsional), low-freq (0.03-0.1 Hz power swing)
- [ ] Voltage oscillations: switching transients (0.15 pu peak-peak)

### 4.4 Kerala VRE Context
- [ ] Solar 1,519.66 MW (34.4% capacity), 26.2% of peak — IEA Phase 4 threshold
- [ ] 1,223.63 MU non-KSEB rooftop (64% of solar) — invisible to grid operator
- [ ] 57 major RE loss events (Jan 2022–Jun 2024): 6,157 MW loss (Aug 2022), 4,870 MW (Apr 2024)
- [ ] Frequency >50.05 Hz for 4+ hours during solar hours — insufficient down reserves

---

## WEEK 5: ENERGY STORAGE FUNDAMENTALS

### 5.1 Battery Energy Storage Systems (BESS) — Core Theory
- [ ] Battery electrochemistry: Li-ion (LFP, NMC, LTO), redox reactions, SEI formation
- [ ] Cell formats: cylindrical, prismatic, pouch — thermal/mechanical implications
- [ ] Module/pack design: series/parallel, BMS architecture (centralized/distributed/modular)
- [ ] PCS (Power Conversion System): bidirectional inverter, transformer, isolation
- [ ] BMS functions: SOC/SOH estimation (Kalman filter, coulomb counting), cell balancing, thermal mgmt
- [ ] EMS (Energy Management System): dispatch optimization, grid interface, revenue stacking

### 5.2 BESS Chemistries & Degradation
| Parameter | LFP | NMC | LTO |
|-----------|-----|-----|-----|
| Energy density | 120–160 Wh/kg | 150–220 Wh/kg | 70–80 Wh/kg |
| Cycle life (80% DoD) | 4,000–6,000 | 2,000–3,000 | 15,000–20,000 |
| Thermal stability | Excellent (270°C) | Moderate (210°C) | Excellent |
| Cost ($/kWh, 2024) | ~$100–120 | ~$110–130 | ~$300–400 |
| Kerala preference | **LFP** | — | — |

- [ ] Degradation: calendar (time, temp, SOC), cycling (throughput, DoD, C-rate), lithium plating, SEI growth
- [ ] Safety: thermal runaway (CO, H₂, VOC detection), fire suppression (Novec 1230, water mist), deflagration vents

### 5.3 Pumped Hydro Energy Storage (PHES) — Core Theory
- [ ] Configurations: open-loop (river-connected), closed-loop (off-stream), hybrid (existing + new)
- [ ] Turbine types: Francis (fixed/variable speed), ternary (separate pump/turbine), Pelton
- [ ] Variable-speed (DFIG/FSM): ±30% speed, fast frequency response, inertia emulation
- [ ] Closed-loop advantages: no river diversion, flexible siting, minimal water consumption
- [ ] Water balance: evaporation (1.5–2 m/yr), seepage (0.5–1%), make-up water

### 5.4 Emerging/Long-Duration Storage
- [ ] Flow batteries: vanadium redox (70–75% RTE), iron-flow (70% RTE, low cost)
- [ ] CAES: adiabatic (60–70% RTE), isothermal; geographic constraints
- [ ] Thermal storage: molten salt (CSP), sand/concrete, ice (cooling)
- [ ] Gravity storage: Energy Vault, Gravitricity (80–85% RTE)
- [ ] Hydrogen: underground caverns, pipelines, ammonia/LOHC carriers (35–45% RT)

### 5.5 Storage Sizing & Value Stacking
- [ ] Duration optimization: 2-hr (peak shave) vs 4-hr (solar shift) vs 6-hr (full belly) vs 8-hr (seasonal)
- [ ] Revenue streams: energy arbitrage, frequency regulation, capacity/RA, T&D deferral, black start, voltage support
- [ ] Degradation-aware optimization: throughput limits, SOC window, temperature constraints
- [ ] Multi-year planning: weather uncertainty, demand growth, fuel price scenarios

---

## WEEK 6: DEMAND-SIDE FLEXIBILITY & DER FUNDAMENTALS

### 6.1 Demand Response (DR) Theory
- [ ] DR typology: direct load control, price-based (TOU, CPP, RTP), incentive-based (capacity, ancillary)
- [ ] Load flexibility characterization: shiftable, shedable, shapeable, time-critical
- [ ] Sectoral potential: industrial (process, cooling), commercial (HVAC, lighting), residential (WH, AC), agricultural (pumping)
- [ ] DR program design: TOU tariffs, critical peak pricing, direct load control, capacity bidding, emergency DR
- [ ] Measurement & verification (M&V): baseline methods (high-X-of-Y, regression, control group)

### 6.2 EV Smart Charging & V2G
- [ ] Charging levels: L1 (1.4 kW), L2 (7–19 kW), DCFC (50–350 kW), wireless
- [ ] Smart charging: TOU optimization, grid signal response, solar alignment
- [ ] V2G: CHAdeMO, CCS2, ISO 15118-20, OCPP 2.0.1, battery degradation from V2G cycling
- [ ] Fleet optimization: depot, opportunity, destination charging; freight corridors (Delhi-Jaipur)

### 6.3 Rooftop PV & BTM Solar Integration
- [ ] Hosting capacity: voltage rise, reverse flow, thermal limits, phase unbalance
- [ ] Smart inverter functions: Volt-VAr, Volt-Watt, frequency-watt, ramp rate, LVRT/HVRT
- [ ] Standards: IEEE 1547-2018 (adopted BIS 2023), CSIP-AUS (Australia), CEA connectivity
- [ ] Net metering vs net billing vs gross metering vs feed-in tariff
- [ ] BTM battery: self-consumption, backup, grid services, virtual net metering

### 6.4 Flexible Thermal Loads
- [ ] Water heating: heat pump WH (COP 3–4), resistance, solar thermal, thermal storage tanks
- [ ] Space cooling: ice storage, chilled water, PCM (18–22°C), building pre-cooling/pre-heating
- [ ] Industrial thermal: cold storage (ice/PCM), process heat (steam accumulators), cement/steel limitations
- [ ] District heating/cooling integration: thermal networks as flexibility assets

---

## WEEK 7: HYDROPOWER FLEXIBILITY & RESERVOIR OPERATIONS

### 7.1 Conventional Hydro Re-operation Theory
- [ ] Reservoir operating rules: guide curves, rule curves, hedging rules, minimum release
- [ ] Daily/weekly cycling vs seasonal storage trade-offs
- [ ] Environmental flow constraints: minimum release, ramping limits, fish passage
- [ ] Multi-reservoir optimization: cascade, parallel, pumped-storage hybrid (DP, SDP, RL)
- [ ] Monsoon management: flood control vs storage maximization, forecast-informed operations

### 7.2 PHES Integration with Existing Hydro
- [ ] Retrofitting: Francis reversible (single unit), ternary (separate pump+turbine), variable-speed
- [ ] Upper/lower reservoir pairing: existing + new, both new, quarry reuse (Manjappara)
- [ ] Closed-loop vs open-loop: environmental permitting, water rights, ecology
- [ ] Water balance: evaporation (1.5–2 m/yr), seepage (0.5–1%), consumptive use

### 7.3 Kerala Hydro Context
- [ ] KSEB portfolio: Idukki (780 MW), Sabarigiri (340 MW), Sholayar (54 MW), Kuttiyadi (225 MW), Poringal (36 MW), 12 small hydro (92 MW)
- [ ] Idukki: 780 MW, large live storage, head ~650 m, tourism/env constraints
- [ ] Sabarigiri: 340 MW, Pamba/Kakki/Anathode cascade, inter-state (TN)
- [ ] Daily cycling potential: 500–1,000 MW untapped (12 PM→6 PM storage, 6–10 PM generation)
- [ ] Monsoon variability: ±30% YoY generation, dry season storage conservation

---

## WEEK 8: TRANSMISSION & DISTRIBUTION INFRASTRUCTURE

### 8.1 Transmission Planning for High VRE
- [ ] RE zone identification: resource quality, land, water, evacuation corridor
- [ ] Corridor planning: RE-rich to load-center (Rajasthan→Delhi, Gujarat→North, TN→Kerala/KA)
- [ ] Dynamic Line Rating (DLR): ambient-adjusted ampacity (10–20% gain)
- [ ] FACTS: SVC/STATCOM (voltage), TCSC (power flow), SVG, synchronous condenser
- [ ] HVDC: VSC-HVDC (weak grid, black start), LCC-HVDC (long distance), multi-terminal
- [ ] Sub-synchronous resonance (SSR): torsional interaction, NGH damping, FACTS mitigation

### 8.2 System Strength & Grid-Forming Inverters
- [ ] SCR calculation: IEC 60909, weighted SCR for multiple IBRs
- [ ] Synchronous condenser: sizing, siting, control modes (voltage, inertia, damping)
- [ ] Grid-forming inverters: virtual synchronous machine (VSM), droop, matching control
- [ ] Dynamic voltage stability: PV curves, QV curves, continuation power flow

### 8.3 Kerala Transmission Context
- [ ] KSEB network: 400 kV (8 substations, 1,200 ckm), 220 kV (35, 3,500 ckm), 110 kV (120, 8,000 ckm), 66/33 kV (300+, 15,000+ ckm)
- [ ] Inter-state: Kerala→TN (2×400 kV + 220 kV), Kerala→KA (400+220 kV), ISTS via PGCIL SR
- [ ] Constraints: Kerala→TN thermal/n-1, Kerala→KA voltage stability, ISTS SR regional congestion
- [ ] GEC-I (intra-state) & GEC-II (inter-state): 500 GW by 2030, 600 GW by 2032

### 8.4 Distribution Grid Modernization
- [ ] ADMS/DMS/SCADA integration, Volt/Var optimization (VVO), CVR
- [ ] FLISR: fault location, isolation, service restoration
- [ ] DERMS: rooftop PV, BESS, EV control, Volt-VAr, Volt-Watt
- [ ] AMI: 250M smart meters (NSGM), 15-min data, TOU billing, remote connect/disconnect
- [ ] Kerala status: <15% DT metering live (5.25M RDSS), OPGW/MPLS comms, DERMS not deployed

---

## WEEK 9: MARKET DESIGN, REGULATORY & CONTRACTUAL FRAMEWORKS

### 9.1 Indian Power Market Structure
- [ ] Long-term PPAs: Section 62 (regulated tariff), Section 63 (competitive bidding)
- [ ] Short-term markets: DAM (day-ahead), RTM (real-time 15-min), GTAM (green term-ahead), G-DAM (green day-ahead), HP-DAM (hydro peak)
- [ ] DSM evolution: 2014 (15% tol) → 2022 (5%/10%) → 2023 relaxation (10%/15%) → 2024 current → **Apr 2026: Solar 5%, Wind 10%, 200% penalty**
- [ ] Ancillary services: FRAS (primary), SRAS (secondary), TRAS (tertiary), black start
- [ ] Green markets: GTAM, G-DAM (8,320 MU IEX 2024-25), REC

### 9.2 Contractual Frameworks for VRE & Storage
- [ ] Must-run status: IEGC 2010/2023, APTEL 197/2019, operational violations (verbal curtailment)
- [ ] PPA structures: fixed tariff, indexed, hybrid, FDRE (firm dispatchable RE), RTC (round-the-clock)
- [ ] Storage contracts: capacity payments (₹/MW/mo), energy payments (₹/kWh), availability bonus/penalty
- [ ] Hybrid solar+storage PPAs: capacity allocation, dispatch priority, SOC management
- [ ] Curtailment compensation: **TNERC 2024 model** — Solar 100%, Wind 50%, Hybrid 100% (economic curtailment)

### 9.3 Market Design for Flexibility
- [ ] Scarcity pricing: operating reserve demand curves (ORDC), price caps
- [ ] Co-optimization: energy + reserves + regulation (PJM, CAISO model)
- [ ] Negative pricing: causes, management, curtailment signals
- [ ] Regional coordination: WEIM/EDAM (CAISO), single balancing area (SA), Southern Region coordination (5.4% savings)
- [ ] Cross-border trade: India-Bhutan, Nepal, Bangladesh; GEC corridors

### 9.4 Kerala Regulatory Context
- [ ] KSERC Draft RE Regulations 2025: hosting capacity 90% DT, smart inverter+storage mandatory, BtM option
- [ ] Draft Kerala PSP Policy 2024: 6+ GW target, EMC nodal agency, KSEB right of first refusal
- [ ] Agencies: KSEB (gen/trans/dist/procurement), SLDC (scheduling), ANERT (RE promo), KSERC (tariff/regulation), EMC (PSP/efficiency)
- [ ] Gap: No cross-agency task force operational, SLDC no authority over DISCOM demand-side

---

## WEEK 10: FORECASTING, EMS & DIGITAL GRID OPERATIONS

### 10.1 Renewable Energy Forecasting
- [ ] Horizons: nowcasting (0-1hr, sky imaging), intra-day (1-6hr, satellite+NWP), day-ahead (NWP+ML), week-ahead
- [ ] Methods: NWP (GFS, WRF, IMD), satellite (GOES, INSAT, Himawari), sky imaging, ML/AI (CNN, LSTM, Transformer)
- [ ] Data sources: REMC, satellite (GOES/INSAT/Himawari), sky imagers, ground stations, NWP (GFS, WRF, IMD)
- [ ] Probabilistic: ensembles, quantile regression, prediction intervals, pinball loss
- [ ] Metrics: MAE, RMSE, MAPE, nMAE, nRMSE, pinball loss, CRPS (continuous ranked probability score)

### 4.2 Grid-India AI Initiatives (2025)
- [ ] Load forecasting: XGBoost, LSTM, MAPE 2–5% (national)
- [ ] RE forecasting: ML + satellite + NWP (Rajasthan pilot, Open Climate Fix)
- [ ] RE data cleaning: IIT Kanpur, 250 MW plant, 200 features (non-updating inverters, missing weather)
- [ ] Storage dispatch optimization: AI for BESS charge/discharge, peak shaving, ancillary services

### 4.3 EMS & SCADA Architecture
- [ ] SCADA: RTU, PMU, IED → data concentrator → EMS server
- [ ] Applications: State Estimation (SE), RTCA, SCED, AGC, VRE forecasting, storage dispatch, WAMS
- [ ] Wide-area monitoring: PMU (30–60 samples/sec), WAMS, oscillation detection
- [ ] Digital twin: real-time simulation, contingency analysis, operator training

### 4.3 AI/ML for Grid Operations
- [ ] Load forecasting: XGBoost, LSTM, Transformer, attention (MAPE 2–5%)
- [ ] VRE forecasting: CNN (satellite), physics-informed ML, physics-informed neural networks (PINN)
- [ ] Anomaly detection: autoencoders, isolation forests (cyber, equipment)
- [ ] Storage dispatch: RL (SAC, PPO), MPC, stochastic programming
- [ ] Grid-forming control: VSM, droop, matching, virtual oscillator
- [ ] Cyber-physical security: adversarial ML, model poisoning, data integrity

---

## WEEK 11: FINANCIAL MODELING, INVESTMENT & RISK MANAGEMENT

### 11.1 BESS Financial Model (Kerala)
- [ ] CAPEX breakdown: modules (40–45%), PCS (15–20%), BMS/EMS (5–8%), thermal (8–12%), civil/BOP (10–15%), EPC (8–12%) → **₹8,500–11,000/kWh**
- [ ] Revenue stack: energy arbitrage (₹25–35k/kW/yr), FRAS (₹8–12k), capacity (₹15–20k), T&D deferral (₹5–10k) → **₹53–77k/kW/yr**
- [ ] VGF impact: VGF-I (13.8 GWh, ₹3,760 Cr, 40% CAPEX), VGF-II (30 GWh, ₹5,400 Cr PSDF)
- [ ] ISTS waiver: co-located BESS till Jun 2028, standalone phased reduction

### 11.2 PHES Financial Model
- [ ] CAPEX: Mudirapuzha (100 MW/600 MWh, ₹573 Cr, ₹9,500/kWh), Manjappara (30 MW/150 MWh, ₹180 Cr, ₹12,000/kWh), Idukki PSP (700 MW, ₹3,083 Cr, ₹7,300/kWh)
- [ ] Revenue: energy arbitrage (6-hr, ₹40–55k/kW/yr), FRAS (₹10–15k), inertia/voltage (₹5–10k), capacity (₹15–20k), black start (₹2–5k) → **₹72–110k/kW/yr**

### 11.2 Project Finance & Risk
- [ ] Debt sizing: DSCR (1.2–1.4x), LLCR, PLCR, debt sculpting to match cash flows
- [ ] Equity returns: project IRR 12–18%, equity IRR 15–22%, payback 5–8 years
- [ ] DISCOM counterparty risk: payment security (LC, escrow), state guarantee, ₹7.26L Cr national debt
- [ ] Risk premiums: policy/regulatory (+200–400 bps), construction (+100–200 bps), technology (+50–100 bps)

### 11.3 DISCOM Financial Health & Tariff Design
- [ ] FY 2024-25: PAT +₹2,701 Cr, but -₹11,270 Cr excl. regulatory; Net Worth -₹1.03L Cr; Debt ₹7.26L Cr
- [ ] AT&C losses: 15.04% (improving), ACS-ARR gap: -₹0.03/kWh (crossed zero)
- [ ] Green tariff: avg cost ₹7.47/kWh vs tariff ₹6.50/kWh = **15% loss/unit** (CSEP study)
- [ ] Open access migration: C&I exodus → cross-subsidy erosion → tariff hikes for remaining
- [ ] Kerala: power purchase >₹7/unit, BESS 1,500 MWh by 2026, PHES Mudirapuzha ₹573 Cr + Manjappara ₹180 Cr

---

## WEEK 12: ENVIRONMENTAL, LAND & SOCIAL ASPECTS

### 12.1 EIA & Clearance Processes
- [ ] EIA process: screening → scoping → ToR → draft EIA → public hearing → final EIA → appraisal → EC
- [ ] PHES-specific: aquatic ecology, terrestrial ecology, water quality, sediment transport
- [ ] BESS: fire risk, chemical contamination, recycling (Li, Co, Ni recovery)
- [ ] Solar: land use, biodiversity, avian collision, glare, heat island
- [ ] Climate resilience: flood (Wayanad 2024), landslide, cyclone, heatwave

### 12.2 Forest & Wildlife Clearance
- [ ] Forest (Conservation) Act 1980: procedure, 2023 notification exemptions (exploration ≤100 trees, ≤25 boreholes/10km²)
- [ ] FAC 2024: exploratory drilling for hydro/PSP = "forest activity" → exempt
- [ ] Wildlife clearance: NBWL, state board, corridor impact, linear projects
- [ ] Compensatory afforestation: CAMPA, degraded land, advance CA, net present value (NPV)
- [ ] Kerala: Wayanad landslides (2024) → stricter EC/FC, 3-season data mandated

### 12.3 Land Acquisition & PHES Advantages
- [ ] RFCTLARR Act 2013: consent (70–80%), SIA, compensation (2–4× market), R&R
- [ ] Government land: assignment, lease, forest diversion (FC required)
- [ ] Kerala: density 860/km², limited non-forest land
- [ ] PHES advantage: abandoned quarries (Manjappara), existing reservoirs (Idukki, Sabarigiri)
- [ ] Closed-loop PHES: minimal land, no new reservoir, often B2 category (reduced EIA)

### 12.4 Water Resources & Inter-State Issues
- [ ] Inter-state disputes: Cauvery, Mullaperiyar, Chambal, Mahanadi
- [ ] Ecological flow: minimum release, seasonal variation, fish migration
- [ ] PHES water balance: evaporation (1.5–2 m/yr), seepage (0.5–1%), make-up water
- [ ] Kerala: monsoon variability ±30%, inter-state (Cauvery, Mullaperiyar), drinking water priority

---

## WEEK 13: GREEN HYDROGEN & SECTOR COUPLING (Niche Role)

### 13.1 Green Hydrogen Production
- [ ] Electrolyzers: alkaline (mature, 60–70% LHV), PEM (flexible, 65–75%), SOEC (high temp, 80%+), AEM (emerging)
- [ ] Efficiency: stack (70–80%), system (60–70%), balance of plant (10–15% loss)
- [ ] Renewable supply: dedicated (higher CUF, lower LCOH) vs grid-connected (firming cost)
- [ ] CUF vs LCOH trade-off: oversizing RE (2× electrolyzer) → 60%+ CUF → lower LCOH

### 13.2 Storage & Transport
- [ ] Compressed: 350/700 bar, Type I–IV vessels, compression energy 10–15%
- [ ] Liquid: -253°C, boil-off 0.1–0.5%/day, liquefaction 30% energy penalty
- [ ] Pipeline: blending ≤20% H₂ (embrittlement), dedicated new build, repurposing
- [ ] Carriers: ammonia (NH₃, -33°C), LOHC (dibenzyltoluene), methanol, methane (Sabatier)

### 13.3 India Green Hydrogen Policy
- [ ] NGHM: 5 Mt by 2030, SIGHT scheme (VGF for electrolyzer + RE)
- [ ] Incentives: VGF, ISTS waiver, PLI (electrolyzer), customs duty exemption
- [ ] Standards: green H₂ definition (well-to-gate), certification, tracking (blockchain)
- [ ] Demand creation: mandates (refining 25%, fertilizer 15%, steel 10%), bids (SECI)

### 13.4 Kerala Context
- [ ] Target: Kochi assessment only (FACT, BPCL, HOC, Cochin Shipyard)
- [ ] Industrial offtake: 20-yr fixed price contracts only (Jindal/Asahi model)
- [ ] Water: monsoon surplus, dry season constraint
- [ ] Land: limited, high cost
- [ ] **Verdict:** Only with firm 20-yr offtake — not default surplus sink

---

## WEEK 14: CYBERSECURITY & GRID RESILIENCE

### 14.1 OT/IT Convergence & Attack Surface
- [ ] Purdue model: Level 0 (process) → Level 5 (enterprise), zones/conduits
- [ ] Smart inverters/PPCs: foreign OEM firmware, supply chain risk
- [ ] SCADA/EMS protocols: IEC 61850 (GOOSE, SV), DNP3, Modbus/TCP, ICCP
- [ ] Smart meters: 250M endpoints (NSGM), HES, MDM, RF/PLC/cellular comms
- [ ] VPP/DER aggregation: distributed control, lateral movement risk

### 14.2 Threat Landscape (India 2024-25)
- [ ] APT/state-sponsored: 200,000+ attacks thwarted (May 2025 India-Pak tensions)
- [ ] Ransomware: Mumbai 2021 outage, Colonial Pipeline, IT→OT pivot
- [ ] Supply chain: Chinese inverter imports (Bloomberg Jul 2025 "malware/backdoor")
- [ ] Legacy OT: unpatched systems now network-connected
- [ ] Insider threat: privileged access, credential theft, phishing

### 14.3 Regulatory Framework
- [ ] CEA Cyber Security Regulations 2021 (critical utilities)
- [ ] Draft CEA Cyber Security Regulations 2025: entire ecosystem (RE generators, exchanges, OEMs, vendors)
- [ ] Mandatory (proposed Apr 2026): board policy, CISO, NCIIPC alignment, supply chain security
- [ ] Kerala: Centralized End Point Protection at SLDC (PIB 2024)

### 14.4 Resilience & Disaster Recovery
- [ ] Black start: restoration plans, cranking paths, islanding, GFM inverters for black start
- [ ] Physical resilience: cyclone, flood (Wayanad 2024), landslide, heatwave
- [ ] Cyber-physical: coordinated attacks, cascading failures, simulation exercises
- [ ] Business continuity: BCM, DR, backup, redundancy, cyber range exercises

---

## WEEK 15: KERALA-SPECIFIC DEEP DIVE (Data-Driven)

### 15.1 Critical Data Acquisition (Must Obtain Before Design)
| Data Set | Source | Priority |
|----------|--------|----------|
| 8760-hr solar profile (utility + rooftop) | KSEB, SLDC, REMC | **CRITICAL** |
| 8760-hr demand profile | KSEB, SLDC | **CRITICAL** |
| Hourly hydro generation + reservoir levels | KSEB | **CRITICAL** |
| Hourly curtailment + reason codes | SLDC, KSEB | **CRITICAL** |
| Substation-level load curves | KSEB | **HIGH** |
| DT-level reverse flow | KSEB (RDSS) | **HIGH** |
| Transmission corridor hourly flows | SLDC, PGCIL | **HIGH** |
| Thermal min gen, ramp rates | KSEB, generators | **HIGH** |

### 15.2 Kerala Rooftop PV Analytics
- [ ] Feeder-level hosting capacity: OpenDSS/CYME per 11 kV feeder → DT upgrade map
- [ ] Phase unbalance index: smart meter data → single-phase clustering map
- [ ] Reverse flow duration curve: DT meter data → storage/DR sizing per feeder
- [ ] Voltage violation frequency: smart meter voltage → Volt-VAr/Volt-Watt settings
- [ ] Protection coordination: relay settings + reverse flow → relay updates needed

### 15.3 Kerala Hydro Flexibility Assessment
- [ ] Reservoir simulation: HEC-ResSim/custom → daily cycling capacity (MW for 12 PM→6 PM)
- [ ] Multi-reservoir optimization: Idukki-Sabarigiri cascade (LP/DP/SDP)
- [ ] Pumping retrofit feasibility: turbine OEM study + civil → cost/timeline/efficiency
- [ ] Environmental flow compliance: hydrological model + mandate check

### 15.4 Kerala Market & Financial Analysis
- [ ] G-DAM/RTM participation: Kerala net buyer (1,625 MU @ ₹6.28/kWh)
- [ ] DSM charges: deviation, frequency, voltage components
- [ ] Curtailment patterns: hourly, substation, reason codes (technical vs economic)
- [ ] Green tariff adoption: HT consumer uptake, revenue impact
- [ ] KSEB finances: power purchase >₹7/unit, demand 30,083→38,636 MU (2029-30)

---

## WEEK 16: ADVANCED MODELING & OPTIMIZATION

### 16.1 Production Cost Modeling (PyPSA/GenX/PLEXOS)
```python
# Kerala network model structure
network = pypsa.Network()
# Buses: 400kV, 220kV, 110kV, 66kV, 33kV, 11kV
# Generators: Thermal (min_gen, ramp), Hydro (reservoir, min_flow), Solar, Wind
# Storage: BESS (4hr), PHES (6-8hr), Hydro (pumping)
# Loads: Hourly demand, DR potential, EV charging, Industrial flexibility
# Links: Transmission (thermal limits), ISTS interfaces

# Objective: Minimize total system cost
# Constraints: Power balance, generator limits, hydro reservoir balance, 
#              storage SOC, transmission limits, frequency constraints (proxy)
```

### 16.2 Distribution Hosting Capacity (OpenDSS)
```python
# Per 11 kV feeder
dss = opendssdirect.DSS
dss.Text.Command = "Compile feeder.dss"
# Add PV at DT locations (from RDSS data)
# Run daily quasi-static (96×15-min)
# Outputs: voltage profile, reverse flow, DT loading, losses
# Sensitivity: Add BESS at substation, smart inverter Volt-VAr, DT upgrade
```

### 16.3 Stochastic & Robust Optimization
- [ ] Scenario generation: weather (solar/wind), demand, fuel prices, outages
- [ ] Two-stage stochastic: here-and-now (capacity) vs wait-and-see (dispatch)
- [ ] Robust optimization: uncertainty sets, budget of uncertainty
- [ ] Distributionally robust: Wasserstein ambiguity, moment-based

### 16.4 Degradation-Aware Storage Optimization
- [ ] Battery degradation models: rainflow counting, equivalent cycles, Arrhenius temperature
- [ ] Throughput limits: contractual (MWh/yr), warranty (MWh total)
- [ ] SOC window optimization: 20–80% vs 10–90% trade-off (life vs revenue)
- [ ] Temperature management: HVAC sizing, passive cooling, Kerala climate (25–35°C, 80%+ RH)

---

## WEEK 17: ADVANCED GRID STABILITY & PROTECTION

### 17.1 IBR-Dominated Grid Stability
- [ ] Grid-forming control: VSM (swing equation emulation), droop, matching, dispatchable virtual oscillator (DVOC)
- [ ] Stability metrics: RoCoF, frequency nadir, settling time, voltage recovery
- [ ] Synchronous condenser: inertia emulation (H = 2–4 s), fast voltage support
- [ ] Wide-area damping control: PSS, FACTS-based damping, WAMS-based

### 17.2 Protection Coordination for High IBR
- [ ] Fault current: IBR limited to 1.1–1.2× rated vs synchronous 5–10×
- [ ] Adaptive protection: settings groups based on IBR penetration, topology
- [ ] Traveling wave fault location: PMU-based, sub-cycle accuracy
- [ ] Islanding detection: passive (ROCOF, vector shift) + active (impedance, frequency drift)

### 17.3 Sub-Synchronous Oscillation (SSO) Mitigation
- [ ] Torsional interaction: Type I (series cap), Type II (HVDC), Type III (IBR control)
- [ ] Damping: supplementary damping controller (SDC), FACTS (TCSC, STATCOM)
- [ ] IBR control tuning: PLL bandwidth, current controller, virtual impedance

---

## WEEK 18: CASE STUDIES & GLOBAL BEST PRACTICES (Synthesis)

### 18.1 California (CAISO) — Duck Curve Taming
| Factor | Detail | Kerala Application |
|--------|--------|-------------------|
| CPUC mandate | 11.5 GW + 4 GW BESS by 2026 | KSEB/state mandate needed |
| Hybrid tenders | Solar+BESS default | KSEB: mandate BESS with new solar |
| WEIM/EDAM | Regional market (8 states) | Push Southern Region UC+dispatch |
| VPP | 535 MW aggregated (Jul 2025) | Pilot KSEB VPP with BTM batteries |
| Curtailment | 3.4 TWh (2024), declining | Track Kerala curtailment hourly |

### 18.2 Germany — Solar Peak Act (Feb 2025)
| Measure | Detail | Kerala Application |
|---------|--------|-------------------|
| 60% feed-in limit | New PV without smart meter | Mandate for new rooftop >10 kW |
| No negative price compensation | New installs | KSERC: adopt in tariff |
| Dynamic tariffs | §14a EnWG, variable grid fees | KSERC: ToD distribution tariffs |
| 80% residential PV+battery | Market-driven | Subsidy for BTM storage |

### 18.3 South Australia — World-Leading VRE
| Innovation | Detail | Kerala Application |
|------------|--------|-------------------|
| Flexible exports (DOEs) | CSIP-AUS, dynamic envelopes | **Adapt CSIP-AUS for Kerala** |
| BTM batteries | 435 MW (66k units), 1/3 in VPP | **KSEB VPP pilot** |
| Hot water load shift | 800 MW, solar sponge tariffs | **KSEB ToD + heat pump program** |
| EnergyConnect | 800 MW interconnector | **Push SR inter-regional capacity** |

### 18.4 Karnataka — Indian Mirror
| Problem | Detail | Kerala Lesson |
|---------|--------|---------------|
| 492 hr deficit FY27 | LoLP 5.6% vs 0.2% | **Act before deficit hits** |
| Thermal inflexibility | 75-85% min gen vs 55% norm | **Enforce CEA flexibility norms** |
| Storage gap | 1 GW/2hr BESS vs 6-8 GWh needed | **Size for 4-6 hr, not 2 hr** |
| Regional coordination | 5.4% cost reduction | **Push Southern Region UC+dispatch** |

### 18.5 Tamil Nadu — Curtailment Management
| Innovation | Detail | Kerala Application |
|------------|--------|-------------------|
| TNERC 2024 Guidelines | Written curtailment, compensation | **Adopt for Kerala** |
| Curtailment hierarchy | Thermal→Hydro→RE (last) | **Adopt in SLDC procedures** |
| Reason codes | Published, transparent | **Mandate for Kerala SLDC** |

---

## WEEK 19: IMPLEMENTATION PLANNING & PROJECT EXECUTION

### 19.1 PHES Stage-Gate Process (Kerala)
| Gate | Criteria | Timeline | Kerala Status |
|------|----------|----------|---------------|
| Gate 1: Site Validation | Resource, geology, env screening | 3–6 mo | Mudirapuzha, Manjappara passed |
| Gate 2: PFR Approval | Technical, economic, env viability | 6–12 mo | **Approved May 2024** |
| Gate 3: DPR & Clearances | FC, EC, land, water, grid | 2–3 yr | Mudirapuzha: PFR→DPR |
| Gate 4: Financial Close | PPAs, debt, equity, VGF | 6–12 mo | Pending |
| Gate 5: Construction | EPC award, mobilization | — | Pending |
| Gate 6: COD | Performance test passed | 4–6 yr from Gate 3 | **Target 2031–2032** |

### 19.2 BESS Deployment Timeline
| Milestone | Target | Dependencies |
|-----------|--------|--------------|
| VGF-II allocation | 2025-26 | MoP, PSDF |
| Site identification | 2025-26 | KSEB, SLDC, substation space |
| Tender & award | 2026 | KSEB procurement |
| Supply & delivery | 2026-27 | 12–18 months (LFP) |
| Installation & commissioning | 2027 | 6–12 months |
| **COD (1,500 MWh)** | **2027-28** | Grid connectivity, EMS integration |

### 19.3 Risk Register (Top 10)
| Risk | Probability | Impact | Mitigation | Owner |
|------|-------------|--------|------------|-------|
| Data access delays | High | High | MoUs at Gate 0, legal fallback | Program Director |
| PHES clearance delays | High | High | Prioritize no-forest sites, parallel FC/EC | EMC |
| BESS underbidding | Medium | High | Realistic VGF, milestone payments, guarantees | KSEB Procurement |
| DISCOM payment risk | High | High | LC/escrow, state guarantee | Finance |
| Grid connectivity delays | Medium | High | Advance grid studies, PGCIL coordination | PGCIL Liaison |

---

## WEEK 20: SYNTHESIS — SOLUTION DESIGN & POLICY ROADMAP

### 20.1 Kerala Flexibility Portfolio (2028 Target)
| Resource | Current | 2028 Target | Gap | Lead Time |
|----------|---------|-------------|-----|-----------|
| BESS (4-hr) | 0 MW | 1,000–2,000 MW | 100% | 2–3 yr |
| PHES (6-8 hr) | 0 MW | 130 MW + 500 MW | 100% | 7–15 yr |
| Hydro daily cycling | 0 MW | 500–1,000 MW | 100% | 1–2 yr (study+ops) |
| DR (industrial/commercial) | 0 MW | 500+ MW | 100% | 2–3 yr |
| EV smart charging | Policy only | 40%+ solar-hr share | 100% | 2–3 yr |
| Rooftop controllability | 0% | 100% new / 50% retrofit | 100% | 3–5 yr |

### 20.2 Policy & Regulatory Roadmap
| Action | Authority | Timeline | Precedent |
|--------|-----------|----------|-----------|
| Adopt TNERC curtailment compensation framework | KSERC | 2025 | Tamil Nadu |
| Mandate smart inverters (CSIP-AUS) for new rooftop >10 kW | KSERC | 2025 | Germany Solar Peak Act, SA CSIP-AUS |
| Implement ToD distribution tariffs (solar hrs discount) | KSERC | 2025 | MoP guidelines, Germany §14a |
| Mandate BESS (4-hr min) with new utility solar >50 MW | KSERC/KSEB | 2026 | CA CPUC mandate |
| Operationalize cross-agency task force (monthly) | Energy Dept | 2025 | Policy Report recommendation |
| Publish hourly curtailment data with reason codes | SLDC/KSERC | 2025 | TNERC, CAISO |

### 20.3 Institutional Reform
- [ ] **Single accountability:** Designate "Flexibility Coordinator" (SLDC or new entity) with authority over storage dispatch, DR activation, curtailment decisions
- [ ] **Data transparency:** Real-time dashboard (curtailment, storage SOC, hydro scheduling, frequency)
- [ ] **Performance-based regulation:** KPI-linked incentives for KSEB/SLDC (curtailment reduction, peak shaving, cost savings)
- [ ] **Workforce development:** TPSDI Wayanad expansion (BESS, PHES, EMS, cybersecurity tracks)

---

## DELIVERABLES CHECKLIST (Post-Study)

| Deliverable | Description | Format |
|-------------|-------------|--------|
| **Data Inventory** | All Kerala data sources, gaps, access MoUs | Spreadsheet + MoUs |
| **Model Repository** | Calibrated PyPSA/OpenDSS models | Git repo + docs |
| **Technology Assessment** | BESS/PHES/DR/V2G/H₂ comparison for Kerala | Report + Excel |
| **Regulatory Roadmap** | KSERC/CERC/CEA filing calendar, evidence | Calendar + matrix |
| **Financial Model** | CAPEX/OPEX/revenue for portfolio | Excel + Monte Carlo |
| **Implementation Plan** | Stage-gate schedule, resources, risk register | MS Project + risk reg |
| **Stakeholder Map** | KSEB/SLDC/ANERT/EMC/KSERC roles, MoUs | Org chart + RACI |
| **KPI Dashboard** | Curtailment, storage dispatch, DR activation, savings | Grafana/PowerBI spec |

---

**Total Topics: 250+** across 20 weeks chronological progression  
**Prerequisite for Solution Design:** Complete Weeks 1–10 minimum  
**Full Program Duration:** 20 weeks (full-time) / 40 weeks (part-time)