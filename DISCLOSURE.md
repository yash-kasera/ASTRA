# Disclosure: AI tools, libraries and models

This file lists every outside tool, library and model used in ASTRA, with attribution. It is updated whenever something is added.

## AI assistants
| Tool | Used for |
|---|---|
| Claude Code (Anthropic) | Research, document drafting, the design prototype, and code assistance |

## Planned open-source libraries and tools
| Name | Licence | Purpose |
|---|---|---|
| React, Vite, TypeScript | MIT / Apache-2.0 | Exam app and dashboards |
| Dexie (IndexedDB) | Apache-2.0 | Saving answers in the browser |
| FastAPI, Uvicorn | MIT / BSD | Centre and control-room services |
| SQLite, PostgreSQL | Public domain / PostgreSQL licence | Databases |
| LightGBM, scikit-learn, SHAP | MIT / BSD / MIT | Prediction and anomaly detection |
| Google OR-Tools | Apache-2.0 | Planning seat moves |
| PyNaCl, @noble/ed25519 | Apache-2.0 / MIT | Digital signatures |
| MediaMTX, FFmpeg, OpenCV | MIT / LGPL-GPL / Apache-2.0 | CCTV streaming, recording, tamper alerts |
| Ollama | MIT | Running the local language model |

## Models
| Model | Licence | Purpose |
|---|---|---|
| Laya (ConvAI Innovations) | Apache-2.0 | Fast offline decisions, e.g. reading invigilator reports |
| A small open-weight language model via Ollama (to be finalised; licence checked before use) | Model-specific | Explanations and message drafts |

## Data
- `data/incidents.csv`: compiled from the published news reports linked in each row.
- All other data (centres, candidates, questions, messages) is simulated and written by the team.
