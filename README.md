<h1 align="center">John Mikel Regida</h1>

<p align="center">
  <b>Principal Platform Architect</b> — data platforms, schema &amp; data contracts, and on-device AI<br>
  London, United Kingdom · 10+ years shipping data-intensive systems
</p>

<p align="center">
  <a href="https://www.johnmikelregida.com">Portfolio</a> ·
  <a href="https://www.johnmikelregida.com/labs">Labs</a> ·
  <a href="https://www.linkedin.com/in/johnmikelregida/">LinkedIn</a> ·
  <a href="https://martinfowler.com/articles/strangler-fig-mobile-apps.html">Writing</a> ·
  <a href="mailto:johnmikelregida@gmail.com">Email</a>
</p>

---

I work at the seam between **data and AI** — building pipelines and platforms that make data trustworthy, schemas that fail loudly *before* production rather than quietly after, and AI tooling that runs on the edge. Currently Lead Data Architect at **Thoughtworks**, where I've worked on the UK Department for Transport's **NaPTAN** national dataset and led mobile micro-frontend platforms serving 100k+ users.

### 🧪 Labs — original tools that run entirely in your browser

No servers, no API keys; the compute is yours. Live at **[johnmikelregida.com/labs](https://www.johnmikelregida.com/labs)**.

| Tool | What it does | Live | Code |
|---|---|---|---|
| **Ontology Explorer (3D)** | A national dataset re-expressed as an interactive 3D knowledge graph (three.js / WebGL) | [demo](https://www.johnmikelregida.com/labs/ontology) | [repo](https://github.com/johnmikel/ontology-explorer) |
| **Data Copilot** | A real LLM running fully in-browser via WebGPU — nothing leaves the device | [demo](https://www.johnmikelregida.com/labs/copilot) | [repo](https://github.com/johnmikel/data-copilot) |
| **Data-Quality Hub** | On-device embeddings: infer schema *meaning*, measure *drift*, flag *breaking* changes | [demo](https://www.johnmikelregida.com/labs/ai) | [repo](https://github.com/johnmikel/data-quality-hub) |
| **Semantic Lint** | Embeddings catch the data errors rules can't — near-dupes, outliers, mislabels | [demo](https://www.johnmikelregida.com/labs/semantic-lint) | [repo](https://github.com/johnmikel/semantic-lint) |
| **NaPTAN Explorer** | All 435,029 UK transport stops, queryable in-browser with DuckDB-WASM | [demo](https://www.johnmikelregida.com/labs/naptan) | [repo](https://github.com/johnmikel/naptan-explorer) |
| **MCP Tool Forge** | Lints an MCP / agent tool schema the way an LLM reads it — data contracts for agents | [demo](https://www.johnmikelregida.com/labs/mcp-forge) | [repo](https://github.com/johnmikel/mcp-tool-forge) |

### 🔧 Open source

A through-line: **make data trustworthy before anyone consumes it** — contracts, schemas, and metrics enforced as CI gates, not caught after the fact.

- **[dataproduct-kit](https://github.com/johnmikel/dataproduct-kit)** — CLI + GitHub Action that turns data-product trust (contracts, quality, freshness, semantics, policy) into a CI gate. *Python · DuckDB · on PyPI · 80 tests.*
- **[zeno-mobile-runner](https://github.com/johnmikel/zeno-mobile-runner)** — agent-native mobile UI automation: one Zig binary drives real iOS/Android devices over MCP / JSON-RPC and emits replayable trace evidence. *~16.5k lines of Zig · on npm.*
- **[metricspec](https://github.com/johnmikel/metricspec)** — unit tests for business metrics: pin a SQL query's expected result as a versioned contract and fail CI on a row-level diff. *Python · DuckDB · 100 tests · `mypy --strict`.*
- **[seip](https://github.com/johnmikel/seip)** — Schema Evolution Intent Protocol: a Git-native protocol + zero-dependency CLI/Action that makes breaking schema changes explicit, reviewable, and enforceable in CI. *Node · 45 tests.*

### 🏗️ Selected work

- **Thoughtworks** — NaPTAN / DfT data work and an alpha ontology generator for GDS; mobile micro-frontend platform (100k+ users).
- **Five Faces** — patient check-in kiosk platform deployed across 100+ hospitals.
- **Good Law Software** — case-management platform handling 15k+ legal cases.
- **COVID-19 vaccination platform** — supported the rollout to 5M+ residents.

### ✍️ Writing

- [Using the Strangler Fig Pattern with Mobile Apps](https://martinfowler.com/articles/strangler-fig-mobile-apps.html) — martinfowler.com (co-authored with Matthew Foster).

### 📜 Credentials

5× **Google Cloud Professional** — Cloud Architect · Data Engineer · ML Engineer · Cloud Database Engineer · Cloud Developer.
MSc Computer Science, Arizona State University (in progress).

---

<p align="center"><i>Striving for the best-case imperfection.</i></p>
