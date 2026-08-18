<div align="center">

# Hey there, I'm Divyasri 👋

<!-- Animated typing text -->
<a href="#">
  <img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&weight=500&size=22&duration=3000&pause=1000&color=FF69B4&center=true&vCenter=true&width=700&lines=Software+%2F+ML+Engineer+%26+Graduate+Researcher;Building+production-grade+RAG+%26+agent+systems;Data+engineering+across+cloud+%26+health-data;Applied+AI+in+quantitative+finance" alt="Typing SVG" />
</a>

<!-- Pink badges: followers / stars / profile views -->
<p align="center">
  <img src="https://img.shields.io/github/followers/K-Divyasri?label=Followers&style=flat-square&color=FF69B4&labelColor=1a1a1a" alt="Followers"/>
  <img src="https://img.shields.io/github/stars/K-Divyasri/K-Divyasri?label=Stars&style=flat-square&color=EF93C4&labelColor=1a1a1a" alt="Stars"/>
  <img src="https://komarev.com/ghpvc/?username=K-Divyasri&label=Profile+Views&color=F8BBD0&style=flat-square" alt="Profile Views"/>
</p>

</div>

<br/>

## 💫 About Me

<table>
<tr>
<td width="65%" valign="top">

Software/ML engineer and graduate researcher building production-grade ML, data, and systems platforms across quantitative finance, health-data, and applied AI.

- 🔭 Currently building: **production RAG & multi-agent systems** — retrieval, evaluation harnesses, and cost-optimized LLM infrastructure
- 🌱 Learning: **durable agent orchestration** and **MCP-based tool integration**
- 🎓 Background: **MSc Medical Biophysics**, University of Toronto (2024–present) · **BEng Computer Science Engineering**, SSN College of Engineering, Chennai (2020–2024)
- 📄 **6 peer-reviewed publications**
- 💬 Ask me about: **RAG & agent evaluation, data engineering pipelines, health-data interoperability (FHIR/HL7), quant systems**
- 📫 Reach me: **divyasrikrishnakumar@gmail.com**
- ⚡ Fun fact: filed a patent for a BLE/GPS/WebSocket-authenticated IoT smart lock I built as my undergrad capstone

</td>
<td width="35%" valign="top" align="center">
<img src="https://github.com/K-Divyasri.png" width="100%" style="border-radius: 12px;" alt="Divyasri"/>
</td>
</tr>
</table>

<br/>

## 🔬 Featured Work

✔ **Production RAG Platform** — hybrid BM25 + vector search (Qdrant) with reciprocal-rank fusion and cross-encoder reranking, lifting retrieval MRR **0.472 → 0.933**; eval-gated CI harness blocks any deploy that regresses it.

✔ **MRSI Reconstruction Pipeline** *(Sunnybrook Research Institute)* — rewrote the core signal-processing step of a multi-nuclear MRSI pipeline, cutting reconstruction time **~100x** (tens of minutes → seconds); validated sub-pixel accuracy against two independent reference pipelines; extends tools cited 500+ times and used by ~500 researchers.

✔ **Agent Trajectory Evaluation Harness** — scores whole agent transcripts (tool-call correctness, task completion, error recovery, step efficiency) instead of a single answer, combining programmatic metrics with an LLM-as-judge pass.

✔ **MCP Server + Client** — a real Model Context Protocol server exposing tools/resources (SQLite/FTS5 search, live weather), wired into Claude as a client over stdio and HTTP.

✔ **LLM Cost & Latency Optimization** — a model router + semantic cache cutting LLM spend **56%** ($0.0125 → $0.0055/request) at full accuracy.

✔ **Health-Data Interoperability & Privacy** — HIPAA Safe-Harbor de-identification (18-identifier redaction/date-shift) and an HL7 v2-to-FHIR converter mapping messages to LOINC-coded resources.

✔ **Change-Data-Capture & Cloud Data Lake** — dual-track CDC (Debezium/Kafka Connect + watermark sync) into an idempotent Postgres warehouse; AWS data lake (S3/Glue/IAM) provisioned via modular Terraform with GitHub Actions CI.

✔ **Pairs-Trading Stat-Arb Engine** — cointegration (Engle-Granger/Johansen) and Kalman-filter hedge ratios, gated by an LLM that reads news to veto trades on structural breaks; walk-forward backtested with transaction costs.

<br/>

<div align="center">

## 🛠️ Tech Stack

<img src="https://skillicons.dev/icons?i=python,cpp,r,java,js,pytorch,tensorflow,fastapi,docker,kubernetes,aws,gcp,azure,postgres,git,github&theme=light" alt="Tech Stack"/>

</div>

**Languages:** Python, MATLAB, SQL, C/C++, R, Java, JavaScript, Bash
**Machine Learning & AI:** PyTorch, TensorFlow, Scikit-learn, LangChain/LangGraph, RAG & hybrid search, LLM fine-tuning (LoRA/PEFT), federated learning, OpenCV
**Data Engineering & Cloud:** Apache Spark, Kafka, Airflow, Dagster, dbt, Debezium/CDC, Docker, Kubernetes, Terraform, AWS (S3, Glue, Athena), GCP, Azure (Databricks, Data Factory, Synapse)
**Domain, Tools & Standards:** FHIR/HL7, HIPAA compliance, FastAPI, REST APIs, Git, Power BI, Tableau, ROS, CUDA

<br/>

<div align="center">

## 📊 GitHub Stats

<img src="https://github-readme-streak-stats.herokuapp.com/?user=K-Divyasri&hide_border=true&background=00000000&ring=FF69B4&fire=EF93C4&currStreakLabel=FF69B4&sideLabels=FF69B4&dates=F8BBD0" width="48%" alt="GitHub Streak"/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=K-Divyasri&theme=react-dark&hide_border=true&bg_color=00000000&color=FF69B4&line=EF93C4&point=F8BBD0&area=true&area_color=F8BBD0" width="95%" alt="Activity Graph"/>

<br/>

## 🐍 Contribution Snake

<img src="https://raw.githubusercontent.com/K-Divyasri/K-Divyasri/output/pink-snake.svg" alt="Contribution Snake"/>

<sub>(renders after the "Generate Snake" Action runs once — see <code>.github/workflows/snake.yml</code> in this repo)</sub>

</div>

<br/>

## 🚀 Currently Exploring

✔ Durable, checkpointed multi-step agents with human-in-the-loop approval gates
✔ Cross-model evaluation and frontier-model benchmarking (cost, latency, accuracy)

<br/>

## ✨ Featured Repositories

🔎 **Production RAG Platform** — [09-rag-real-knowledge-base](https://github.com/K-Divyasri/09-rag-real-knowledge-base)
🔌 **MCP Server + Client** — [24-mcp-server-client](https://github.com/K-Divyasri/24-mcp-server-client)
🧭 **Agent Trajectory Eval Harness** — [38-agent-trajectory-eval-harness](https://github.com/K-Divyasri/38-agent-trajectory-eval-harness)
🏥 **HIPAA De-Identification** — [01_hipaa_deidentification](https://github.com/K-Divyasri/01_hipaa_deidentification)
📈 **Pairs-Trading Stat-Arb Engine** — [01-pairs-trading-statarb](https://github.com/K-Divyasri/01-pairs-trading-statarb)
🧠 **Python FID-A MRSI Reconstruction** — [python-fida](https://github.com/K-Divyasri/python-fida)

<div align="center">

<br/>

## 🤝 Connect With Me

<p align="center">
  <a href="https://linkedin.com/in/divyasri-krishnakumar"><img src="https://img.shields.io/badge/LinkedIn-FF69B4?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:divyasrikrishnakumar@gmail.com"><img src="https://img.shields.io/badge/Email-F8BBD0?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
</p>

<br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:F8BBD0,100:FF69B4&height=150&section=footer&text=Thanks%20for%20visiting!&fontColor=ffffff&fontSize=24&animation=fadeIn" width="100%" alt="Footer Wave"/>

</div>
