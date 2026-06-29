# 👋 Hello, I'm an Independent Researcher & Research Software Engineer (RSE)

### 🔬 Bio: Open Science, Computational Ethology & Animal Welfare Infrastructure

I am an independent researcher bridging an academic background in **Law** with data engineering, focusing on building reproducible open-science infrastructure. My current work tackles the ongoing replication crisis in applied canine ethology by transforming fragmented, subjective narratives into deterministic data pipelines. 

By replacing institutional appeals to authority and anthropomorphic "storytelling" with strict validation engines and international biodiversity standards, my objective is to establish traceably verified, physical realities for animal welfare research and policy.

---

### 🛠️ Active Research & Engineering Projects

#### 🐕 [EthoPipe](https://github.com/sothiss/ethopipe) — Standardized Ethological Data Ingestion Pipeline
An open-science, Python-based Extract, Transform, Load (ETL) pipeline and web API engineered to serve as a strict digital gatekeeper for ethological data.
* **The Problem:** Field notes, handler reports, and shelter incident observations are heavily trapped in qualitative, subjective silos (e.g., labeling an animal as "stubborn" or "angry" instead of documenting objective physical motor sequences).
* **The Architecture:** * **Data Modeling & Validation:** Implements Pydantic v2 (`strict=True`) to enforce strict type casting and clamp physiological vitals to veterinary-validated clinical limits (e.g., canine heart rates restricted between $30$ and $250$ BPM).
    * **Semantic Data Parsing:** Leverages state-of-the-art LLMs (`gemini-2.5-pro`) hosted securely in Google Cloud Platform, constrained strictly to a temperature threshold of `0.0` paired with explicit JSON schemas to strip out human emotional narrative and isolate sterile behavioral syllables.
    * **Informatics Interoperability:** Maps objective behavioral facts natively onto international **Darwin Core (DwC)** metadata schemas (binding fields to `dwc:measurementType` and `dwc:measurementValue`), isolating `HumanObservation` from `MachineObservation`.
    * **Persistence & DevOps:** Validated records serialize into Google Cloud Firestore. Environment drift is eliminated via Docker Dev Containers and checked by automated `pytest` suites via GitHub Actions CI.

---

### 🧰 Computational Tech Stack & Ecosystems

* **Languages & Core Frameworks:** Python, Pydantic v2, Pandas, FastAPI, Pytest
* **Cloud & Enterprise Infrastructure:** Google Cloud Platform (GCP), Firebase/Firestore, Docker / Dev Containers, GitHub Actions CI/CD
* **Advanced Developer Sandbox Access:** * Google Developers Program (Advanced Semantic Parsing Sandbox & Google AI Studio)
    * NVIDIA Developer Ecosystem & Community (Targeting future work scaling text parsing into local compute acceleration and computer-vision kinematic tracking)

---

### 🪪 Academic Identity & Verification

To maintain complete transparency and rigorous integration within the peer-reviewed scientific ecosystem, my software contributions are traceably mapped straight to my official records:

* **ORCID iD:** 🆔 [0009-0003-0048-8982](https://orcid.org/0009-0003-0048-8982)
* **DOIs & Citations:** Integrated automated release pipelines connecting GitHub tags to **Zenodo** to push verified open-source software data straight to citable records.
* **Manuscript Compliance:** Embedded metadata schemas matching **JOSS (Journal of Open Source Software)** automated compilation criteria for imminent review.

---

### 📬 Connect & Collaborate

If you are an open-source architect, data engineer, testing enthusiast, or veterinary epidemiologist interested in moving behavioral science away from dogmatic assertions and toward transparent code, let's connect:

* 🌐 **Global Dashboard:** [thetransparencyproject.me](https://thetransparencyproject.me)
* 💬 **DEV Community:** [@sothiss]
* ✨ **Support the Mission:** Find my open-science infrastructure grant tiers on [Patreon](https://www.patreon.com/cw/Sothiss) 
