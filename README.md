🐟 Predatory Aquaponics

Feed-Driven Nutrient Control Using piranhas (Experimental System)

---

📌 Overview

Predatory Aquaponics explores a controlled ecosystem where fish feed composition influences plant nutrition through the aquaponic nitrogen cycle.

Instead of treating fish as passive nutrient generators, this project treats feed as a tunable input signal and the system as a biological processor:

Feed → Fish metabolism → Waste → Microbial conversion → Plant uptake

The goal is to measure, model, and optimize how different feeding strategies affect:

- Plant growth rates
- Nutrient density
- System stability
- Resource efficiency

---

⚠️ Disclaimer (Read First)

This project uses non-traditional aquaponics species and is primarily experimental.

piranhas introduce:

- Aggression and territorial behavior
- Cannibalism under stress or low food conditions
- High-protein waste spikes

👉 For production systems, consider:

- tilapia
- common carp

---

🧪 Core Hypothesis

«Adjusting fish feed composition can indirectly control plant nutrient availability and growth characteristics.»

Key Variables

- Feed Composition
  
  - Protein %
  - Mineral content (Ca, Mg, Fe)
  - Organic load

- System Response
  
  - Ammonia (NH₃)
  - Nitrite (NO₂⁻)
  - Nitrate (NO₃⁻)
  - pH
  - Microbial activity

- Plant Output
  
  - Biomass
  - Growth rate
  - Nutrient profile

---

🔬 System Architecture

[ Fish Tank ]
      ↓
[ Mechanical Filter ]
      ↓
[ Biofilter (Bacteria) ]
      ↓
[ Grow Beds ]
      ↓
[ Return Loop ]

Biological Engine

- Fish produce ammonia
- Nitrifying bacteria convert:
  - NH₃ → NO₂⁻ → NO₃⁻
- Plants absorb nitrate as primary nutrient

---

🧠 Project Goals

- Build a closed-loop nutrient control system
- Quantify feed → nutrient → plant relationships
- Develop predictive models for plant growth
- Enable adaptive feeding strategies
- Explore unconventional aquaponics species dynamics

---

📁 Repository Structure

piranha-aquaponics/
├── README.md
├── docs/
│   ├── system_overview.md
│   ├── nitrogen_cycle.md
│   ├── species_comparison.md
├── hardware/
│   ├── tank_design.md
│   ├── filtration.md
│   ├── sensors.md
├── feed_profiles/
│   ├── high_protein.md
│   ├── plant_based.md
│   ├── mixed_feed.md
├── experiments/
│   ├── exp_001_feed_vs_nitrate/
│   ├── exp_002_growth_rates/
├── data/
│   ├── water_quality_logs.csv
│   ├── plant_growth_logs.csv
├── firmware/
│   ├── esp32_sensor_node/
│   ├── pump_controller/
│   ├── telemetry_server/
└── models/
    ├── nutrient_flow.ipynb

---

⚙️ Hardware Stack

- ESP32 (sensor + control nodes)
- pH sensor
- EC (electrical conductivity) sensor
- Dissolved oxygen sensor
- Temperature probes
- Water pumps + relays

---

🔄 Example Experiment

Experiment 001: Feed vs Nitrate Production

Hypothesis:
Higher protein feed increases nitrate availability → faster leafy plant growth

Procedure:

1. Establish stable system baseline
2. Apply controlled feed profiles:
   - High protein
   - Mixed omnivore
3. Measure daily:
   - NH₃ / NO₂⁻ / NO₃⁻
   - pH
   - Plant growth (mass/height)

Expected Outcome:

- Increased nitrate with high protein feed
- Potential tradeoff: water instability vs growth

---

📊 Data Collection

Track continuously:

- Water chemistry
- Feed input (mass + type)
- Fish behavior
- Plant metrics

---

🧩 Future Work

- Closed-loop automated feeding (feedback control)
- Machine learning nutrient prediction
- Species comparison benchmarks
- Optimization for specific crops (leafy vs fruiting)

---

⚖️ Ethics & Sustainability

- Avoid overstocking and stress conditions
- Maintain humane fish treatment
- Prevent invasive species release
- Design for resource efficiency and low waste

---

🤝 Contributing

Contributions welcome:

- Experimental data
- Sensor integrations
- Modeling improvements
- Alternative species testing

---

📜 License

MIT License (or choose your preferred open-source license)

---

🚀 Vision

This project aims to bridge:

- Aquaponics
- Systems engineering
- Biological optimization

Toward a future where food systems are programmable, adaptive, and efficient.

---
