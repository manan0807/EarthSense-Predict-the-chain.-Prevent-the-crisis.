# 🌍 EarthSense
### Don't Wait for the Last Domino.

**Real-Time Prediction of Cascading Risks Across the United Nations Sustainable Development Goals**

EarthSense is an environmental intelligence platform designed to connect live global events, identify their potential cascading consequences, and map those risks to relevant Sustainable Development Goals (SDGs). By connecting the dots between environmental events, EarthSense aims to help decision-makers explore what could happen next and identify opportunities for early intervention.

---

## 🚨 The Problem

Environmental events rarely occur in isolation. A drought can lead to water stress, agricultural losses, food insecurity, and livelihood disruption. Yet, existing approaches often leave three critical gaps.

### 1. The SDG Data Lag
SDG dashboards often rely on periodically updated indicators, making it difficult to understand the immediate implications of rapidly evolving environmental events.

### 2. The Disconnected Event
Live event trackers show what is happening now, but do not necessarily connect events to their potential downstream consequences or the SDGs they could affect.

### 3. The Missed Domino Effect
Decision-makers may react after the consequences escalate rather than identifying potential risks early enough to explore preventive action.

**The challenge:** Connect real-time environmental signals with cascading-risk pathways, SDG implications, and potential interventions.

---

## 💡 Our Solution

EarthSense aims to bring environmental event monitoring and cascading-risk analysis into one connected platform.

Unlike systems that focus primarily on displaying current events, EarthSense is designed to explore how one event could trigger another, creating a chain of potential environmental, social, and economic consequences.

Our core idea is simple:

**Detect the first domino. Understand the next. Act before the chain escalates.**

---

## 🔄 How It Works

EarthSense follows a four-stage workflow:

1. **Fetch Global Events** — Collect environmental and other relevant event information from available data sources.
2. **Tag SDGs and Severity** — Use an AI-assisted process to categorize events by potential SDG relevance and severity.
3. **Connect the Dominoes** — Link events using defined cause-and-effect rules to represent potential cascading risks.
4. **Predict Downstream Risks** — Explore potential next events, including possible locations, probabilities, and timing where the model and available data support such estimates.

The platform is intended to transform isolated event information into a connected view of potential future risks.

---

## 🌐 Key Features

- **Live Global Event Monitoring:** Bring together environmental events from multiple sources.
- **Interactive Risk Map:** Visualize event locations and connected risk pathways.
- **AI-Assisted SDG Tagging:** Categorize events by relevant SDGs and severity.
- **Cascading-Risk Engine:** Connect events through explicit cause-and-effect rules.
- **Downstream Risk Exploration:** Investigate what an initial event could trigger next.
- **Early-Warning System:** Highlight potentially escalating risk chains.
- **SDG Impact Mapping:** Explore which development goals may be affected by a risk pathway.
- **Scalable Architecture:** Support the future addition of datasets, hazards, and geographic regions.

*Features described as planned or proposed are not necessarily implemented in the current prototype.*

---

## 🌾 Example: It's Never Just a Drought

A drought is not only a weather event. It can initiate a sequence of connected risks.

```text
Reduced Rainfall
       ↓
   Water Stress
       ↓
 Agricultural Stress
       ↓
 Food Supply Pressure
       ↓
Livelihood Disruption
       ↓
 Increased Poverty Risk
```

EarthSense aims to make this potential chain visible, helping users investigate downstream risks and explore possible interventions.

The actual outcomes depend on local conditions, available resources, adaptation measures, and other factors. This example illustrates a potential pathway rather than a guaranteed prediction.

---

## 🧠 Under the Hood: Technology Stack

The proposed architecture combines environmental data sources, event processing, AI-assisted tagging, persistent storage, a cascading-risk engine, and a web interface.

| Component | Technology or source | Purpose |
|---|---|---|
| Earthquake data | USGS | Retrieve earthquake event information |
| Environmental events | NASA EONET | Access relevant natural-event information |
| Wildfires | NASA FIRMS | Access available fire observations |
| Weather | Open-Meteo | Retrieve weather information |
| Global news | GDELT | Identify potentially relevant reported events |
| Backend | Python FastAPI or Node.js | Fetching, processing, and serving data |
| AI tagging | Gemini | Assist with SDG categorization and severity tagging |
| Database | Supabase / PostgreSQL with PostGIS | Store events and geographic information |
| Frontend | React or Next.js with MapLibre | Display the map, event feed, and risk panel |

The exact technologies and integrations should reflect the implementation actually used in the repository. Data availability, API access, and source limitations must be documented.

---

## 🎯 Impact, SDG Alignment and Scalability

EarthSense is designed to support 13 selected Sustainable Development Goals through environmental-risk mapping and connected-event analysis.

| SDG | Goal |
|---|---|
| 1 | No Poverty |
| 2 | Zero Hunger |
| 3 | Good Health and Well-being |
| 6 | Clean Water and Sanitation |
| 7 | Affordable and Clean Energy |
| 8 | Decent Work and Economic Growth |
| 9 | Industry, Innovation and Infrastructure |
| 10 | Reduced Inequalities |
| 11 | Sustainable Cities and Communities |
| 12 | Responsible Consumption and Production |
| 13 | Climate Action |
| 14 | Life Below Water |
| 15 | Life on Land |

### Expected Impact

- Identify potential cascading risks before crises peak.
- Provide a connected view for decision-makers.
- Support earlier investigation of risks affecting livelihoods, health, water, and food.
- Help users understand how a single event may affect multiple SDGs.

### Scalability Roadmap

- **Prototype:** Demonstrate event collection, SDG tagging, and rule-based cascading-risk analysis.
- **Regional Pilots:** Test the approach across selected regions and hazard types.
- **National and Global Expansion:** Add data sources, hazards, and geographic coverage as the system develops.

These are intended outcomes and development directions, not claims of measured impact or completed global coverage.

---

## 👥 Who Benefits?

EarthSense is intended to support:

- **Governments:** Explore emerging risks and potential response priorities.
- **NGOs:** Understand possible cascading effects on vulnerable communities.
- **Researchers:** Investigate connections between environmental events and sustainable development.

The platform is designed as a decision-support tool, not a replacement for official warnings, scientific assessment, or expert judgment.

---

## 📊 Data Transparency and Limitations

EarthSense distinguishes between:

- **Observed events:** Information retrieved from documented data sources.
- **AI-assisted tags:** Categories and severity assessments generated with AI assistance.
- **Rule-based relationships:** Explicitly defined connections between events.
- **Scenario outputs and predictions:** Estimates that depend on model assumptions and available evidence.

A connection between two events does not automatically establish causation. Predicted event locations, probabilities, and timing should be presented only when supported by an implemented method and suitable data.

The platform should not present simulated results as live observations or claim validated prediction accuracy without evidence.

---

## 🔮 Future Roadmap

Potential future enhancements include:

- More environmental data integrations.
- Improved causal relationships and validation.
- Better uncertainty estimation for downstream risks.
- Additional hazards, regions, and datasets.
- Historical event-chain analysis.
- Intervention comparison and response planning.
- More advanced predictive models, trained and evaluated using appropriate data.

---

## 🚀 Getting Started

Setup instructions depend on the technologies implemented in the repository.

For a React/Vite frontend, a typical workflow is:

```bash
git clone <YOUR_REPOSITORY_URL>
cd <YOUR_REPOSITORY_DIRECTORY>
npm install
npm run dev
```

For a FastAPI backend, a typical workflow is:

```bash
pip install -r requirements.txt
uvicorn app.main:app --reload
```

These commands are examples. Replace placeholders and adjust the backend entry point and setup instructions to match your actual project files.

---

## 🤝 Contributing

Contributions are welcome.

1. Fork the repository.
2. Create a feature branch.
3. Make and test your changes.
4. Commit with a descriptive message.
5. Open a pull request explaining your contribution.

---

## 👨‍💻 Team AntiCoders

- **Team Leader:** Shiv Bhardwaj
- **Members:** Viraj, Manan Bhatia
- **Institution:** VIPS, GGSIPU
- **Programme:** B.Tech, AI & Data Science — Second Year
- **Event:** Pitch // Break — The Survival Arena

---

## 🌍 Our Vision

Today, the alarm often rings when the last domino falls. EarthSense aims to help decision-makers recognize the first domino, understand the chain it could trigger, and explore action before the consequences escalate.

**EarthSense — Don't Wait for the Last Domino.**
