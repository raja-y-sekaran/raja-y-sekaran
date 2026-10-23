## Rajayoganandha Sekaran (Raja)

**Industrial AI & Digital Solutions Engineer | 21 yrs process control & functional safety**

- 21+ years in Saudi petrochemical and fertilizer plants as a DCS/SIS and reliability engineer: safety instrumented systems, functional safety (IEC 61511), reliability.
- I work as an **AI validator**: I decide which AI/ML technique fits which plant problem, own the workflow, build end to end with Claude Code, and check every output against the engineering and the source data.
- Python, SQL, Power Query, Power BI, scikit-learn, XGBoost, LightGBM. In training: deep learning and agentic AI (LangChain, LangGraph, CrewAI, RAG).

### Industrial AI projects

| Project | What it does | Result on sample data |
|---|---|---|
| [sis-safety-text-analytics](https://github.com/rajapune-create/sis-safety-text-analytics) | Links incident narratives to SIFs and initiating events and flags where plant history disagrees with the LOPA, for EHSS review | 7 of 7 flags correct; classifier macro F1 0.95 vs 0.56 for a keyword filter |
| [pid-to-hazop-scenarios](https://github.com/rajapune-create/pid-to-hazop-scenarios) | Reads vector P&IDs and drafts a HAZOP worksheet: causes from the topology, safeguards traced to tags, gaps flagged | 440 / 440 draft rows match the true drawing content; on hard drawings no gap is hidden |
| [valve-limit-switch-alerts](https://github.com/rajapune-create/valve-limit-switch-alerts) | Operator alerts from valve limit-switch timing: slow-stroke trends, sticking, failure to move, chattering switches | 20 / 20 faults found, slow strokes flagged weeks before the DCS limit, a fifth of the alarms |
| [maintenance-log-nlp-pdm](https://github.com/rajapune-create/maintenance-log-nlp-pdm) | NLP over work orders, rounds and incident reports to flag assets likely to break down in 30 days | 93 of 97 warned breakdowns flagged, median 24 days ahead; 7x better than random |
| [mtbf-maintenance-scheduler](https://github.com/rajapune-create/mtbf-maintenance-scheduler) | MTBF and Weibull analysis with suspensions, turned into a dated replacement plan only where it pays | Fleet cost 38% below current practice, within 1.3% of the optimum |

Every project uses **synthetic or simulated data only**: no employer data of any kind. Each is a public re-implementation of a personal prototype and has not been deployed at a plant. Each README explains how the results were validated and where the method stops working.

*Built with Claude Code; design, requirements and validation by Raja.*

Contact: instruraja@outlook.com
