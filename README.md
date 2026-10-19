# Hi, I'm Caroline 👋

**Biostatistics × quantitative research × applied AI.** Harvard biostatistics graduate who likes turning a messy question into a reproducible analysis, and checking whether the answer actually holds up.

- 📊 Biostatistics: survival and longitudinal analysis, causal inference with propensity scores, clinical trial workflows (CDISC SDTM → ADaM → TLFs)
- 🔬 Quant research: factor research, market microstructure, event studies
- 🤖 Applied AI: LLM agents, retrieval and eval harnesses that measure reliability, not just demos
- 🧪 Research roots: cardiovascular wet-lab work at Sydney (co-authored 3 papers), ML thesis at Harvard
- 🌏 Australian citizen (E-3 visa eligible) · open to biostatistician, data scientist, quant researcher and AI engineering roles

---

## Biostatistics & clinical data

### 💊 [clinical-trial-adam-tlf](https://github.com/carol-747/clinical-trial-adam-tlf)
End-to-end safety analysis of the CDISC pilot trial, following the pharmaceutical workflow: a pre-specified SAP, ADaM datasets (ADSL, ADAE, ADTTE) built with admiral, **independent double-programming QC** (0 mismatches across 254 patients), then tables, listings and figures, with Kaplan–Meier and Cox analysis of time to first dermatologic adverse event.
`R` · `admiral` · `CDISC SDTM/ADaM` · `TLFs` · `survival analysis`

### 📈 [survival-longitudinal-casebook](https://github.com/carol-747/survival-longitudinal-casebook)
Three reproducible analysis reports on public clinical cohorts:
- **competing risks:** ignoring death triples the estimated risk of MGUS progression
- **propensity-score weighting:** overlap, ESS and SMD diagnostics show when IPTW fails and overlap weights succeed
- **GEE vs. GLMM:** why marginal and conditional odds ratios differ

`R` · `survival` · `Fine–Gray` · `IPTW` · `GEE` · `lme4`

### 🦠 [final-project](https://github.com/carol-747/final-project)
COVID-19 pandemic waves and state-level outcomes in the U.S. (2020–2023), built from CDC and Census APIs: wave segmentation, state death-rate heatmaps, case-fatality trends and vaccination coverage.
`R` · `Quarto` · `public health data` · `APIs`

## Quantitative research

### 📉 [intraday-factor-research](https://github.com/carol-747/intraday-factor-research)
Intraday microstructure factor research on US equities, built from scratch. FFT detection of algorithmic order splitting, OLS neutralization to sector / size / beta, Rank IC and decay analysis, and a cost-aware long-short backtest with a strict out-of-sample split. Partitioned Parquet + DuckDB so it scales past memory.
`Python` · `DuckDB` · `factor research` · `backtesting`

### 🎲 [prediction-market-event-study](https://github.com/carol-747/prediction-market-event-study)
Do prediction markets lag traditional assets? An event study of Polymarket probabilities around crude-oil and Treasury shocks: two-way lead-lag tests, adjustment-speed estimation, and an out-of-sample, cost-aware trading test at 0 / 1 / 2 h execution delay.
`Python` · `event study` · `market microstructure`

## Applied AI

### 🧬 [biometa-agent](https://github.com/carol-747/biometa-agent)
Full-stack microbe–metabolite literature agent (FastAPI + PostgreSQL + React) with a **measured** NLP pipeline: hand-labeled extraction benchmarks and an agent-groundedness eval that run in CI. Pair-scoped relationship extraction lifted triple-F1 from 0.59 → 0.97, and citation precision from 0.46 → 1.00. Ships an MCP server exposing the literature DB to Claude.
`Python` · `FastAPI` · `LLM agents` · `evals` · `MCP`

### 🧠 [caroline-nanda-agent](https://github.com/carol-747/caroline-nanda-agent) · [caroline-crewai-agent](https://github.com/carol-747/caroline-crewai-agent)
CrewAI agents deployed to the agentic web via the NANDA adapter (AWS EC2, custom domain, SSL), as experiments in multi-agent systems and agent interoperability.
`Python` · `CrewAI` · `multi-agent`

---

## Background

- 🎓 **Harvard T.H. Chan School of Public Health**: MS Biostatistics; ML thesis combining clinical, metabolomic and immune data for asthma-outcome prediction (analysis in R)
- 💼 **Tencent**: solution architect, overseas healthcare AI (pre-sales across Europe, the Middle East, SE Asia and Latin America)
- 📊 **Chow Tai Fook Enterprises**: quantitative research intern (A-share microstructure, factor research in DolphinDB)
- 🧫 **University of Sydney, Snow-Ju Lab**: cardiovascular mechanobiology; co-authored 3 papers

📫 [LinkedIn](https://www.linkedin.com/in/caroline-song-29786617a/) · caroline747shr@gmail.com
