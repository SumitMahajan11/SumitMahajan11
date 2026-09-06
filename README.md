<div align="center">

# Sumit Mahajan
### Building distributed systems & ML at project scale

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/sumit-mahajan-142903324)
[![Gmail](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:sumitnmahajann11@gmail.com)
[![Portfolio](https://img.shields.io/badge/AutoCure-Live_Product-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://autocure.in)

</div>

---

### `whoami`

CS undergraduate at **Pimpri Chinchwad University, Pune** (CGPA 8.1/10, graduating Mar 2028). I took a client from zero to a live, payment-integrated e-commerce platform in 5 weeks, solo — and I build systems-heavy, formal-methods-backed projects the rest of the year. Right now I'm splitting time between two active builds and preparing an open-source contribution track for **GSoC 2027**.

\`\`\`txt
current_focus     = ["GSoC 2027 prep (CNCF / Kubeflow / KubeVirt)", "Lumina Clinical — SIH 2026", "Echo — agentic OS layer"]
oss_runway        = "Aug 2026 → Feb 2027"
languages         = ["TypeScript", "Python", "Rust", "SQL", "C#"]
currently_open_to = ["SWE internships", "OSS collaboration"]
\`\`\`

---

### 🛠️ Stack

<div align="center">

![Stack](https://skillicons.dev/icons?i=ts,js,py,rust,react,nextjs,fastify,django,flask,pytorch,tensorflow,kafka,redis,postgres,prisma,docker,grafana,git,vercel,supabase)

</div>

---

### 🚀 Featured builds

<table>
<tr>
<td width="50%" valign="top">

**🔗 [Ratify](https://github.com/SumitMahajan11/Ratify)** — distributed systems / formal verification
Raft consensus implemented from scratch with Jepsen-style linearizability verification. TLA+ model-checked with zero invariant violations across 5 safety properties. Reproduces real historical Raft bugs; custom linearizability checker at 100% Porcupine parity plus a negative-case proof; RL/bandit fault-injection fuzzer driven by real cluster telemetry, not a lookup table.
\`Rust\` \`Tokio\` \`TLA+/TLC\` \`tonic\`

</td>
<td width="50%" valign="top">

**🔒 [z3-iac-verifier](https://github.com/SumitMahajan11/TODO-add-slug)** — formal verification / infra security
Terraform/K8s config verifier using Z3 SMT solving. 1.0 precision/recall across 27 ground-truth cases (AWS + Azure). Proves cross-account privilege-escalation *reachability* — not single-rule lint matches — with UNSAT-core minimal-fix generation and formal proof certificates. Live K8s ValidatingAdmissionWebhook verified against a real kind cluster.
\`Python\` \`Z3 SMT\` \`python-hcl2\`

</td>
</tr>
<tr>
<td width="50%" valign="top">

**🌐 [AutoCure](https://autocure.in)** — live client product
Solo-built e-commerce platform in 5 weeks: auth, cart, wishlist, order-tracking across 5 categories. Live Razorpay payments (KYC'd), 16 production issues closed through client handoff.
\`Next.js\` \`TypeScript\` \`Supabase\` \`Razorpay\`

</td>
<td width="50%" valign="top">

**⚙️ [Edge-Cloud Orchestrator](https://github.com/SumitMahajan11/edge-cloud-orchestrator)** — distributed systems
8-service platform: Kafka + Saga/Outbox patterns for cross-store consistency, backed by a 546-test suite. ML scheduler (TensorFlow.js) hitting 508ms P99 across 1,000 simulated placements. Rust edge agent on Tokio.
\`Kafka\` \`Rust\` \`TensorFlow.js\` \`PostgreSQL\`

</td>
</tr>
</table>

#### All projects

| Project | What it is | Status |
|---|---|---|
| [ReelClaim](https://github.com/SumitMahajan11/TODO-add-slug) | Audits promotional reel/ad claims against actual website content — Gemini extraction + crawler + 3-pass trust-score engine | 96% accuracy on a 50-case labeled benchmark; auth, persistence, BYOK all shipped — not yet pushed to origin |
| Lumina Clinical (SIH 2026) | Offline-capable maternal triage app for ASHA health workers | Soft-voting ensemble (XGBoost+RF+LightGBM), 85.51% CV accuracy / 91.53% high-risk recall; separate fetal classifier at 93.66% |
| Echo | Locally-run agentic OS layer — voice/vision perception, local STT/TTS, vector memory | Private repo, active development |
| [Soybean Leaf Disease Classifier](https://github.com/SumitMahajan11/soyabean-leaf-disease-classifier) | YOLOv8 + EfficientNet-B4/ResNet152 ensemble, 17 disease classes | 92.96% test accuracy / 92.29% F1 |
| [EcoVision](https://github.com/SumitMahajan11/Waste-Classification-System) | 4-model ensemble waste classifier, 9 categories | 91.79% val accuracy (best model) |

---

### 📊 GitHub stats

<div align="center">

<img height="165" src="https://streak-stats.demolab.com/?user=SumitMahajan11&theme=github-dark&hide_border=true" />

<img src="https://github-readme-activity-graph.vercel.app/graph?username=SumitMahajan11&theme=github-compact&hide_border=true" width="100%" />

<br><br>

<img src="https://raw.githubusercontent.com/SumitMahajan11/SumitMahajan11/output/github-contribution-grid-snake-dark.svg" width="100%" alt="GitHub contribution snake animation" />

</div>

### 🎯 GSoC 2027 — build in public

| | |
|---|---|
| **Target orgs** | CNCF · Kubeflow · KubeVirt |
| **Strongest fit** | Kubeflow Training V2 / gang-scheduling · KServe Models Web App · Kubeflow Docs Agent (RAG) |
| **Phase (now)** | Git/PR fundamentals → real-org contributions |
| **Timeline** | Org list ~Feb 2027 → Proposal Mar 2027 → Results ~Apr 2027 |

---

### 📜 Certifications

\`Red Hat RH124 & RH134\` · \`Red Hat OpenShift (DO101)\` · \`Meta: Django Web Framework\` · \`Meta: Version Control\` · \`Codio: Intro to Operating Systems\`

**Verified (HackerRank):** Python ★★★★★ · Problem Solving ★★★★

---

<div align="center">
<sub>Building in public. Reach out if you're working on distributed systems, ML infra, or open source.</sub>
</div>
