<!--
========================================================================
│  README.md  ◇  James "JD" Davis — Associate Director, AI Platform Engineering
│  Last refresh: September 2026
========================================================================
-->

<!-- Dynamic typing header ------------------------------------------------>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&duration=3000&pause=1000&center=true&width=680&lines=Associate+Director%2C+AI+Platform+Engineering;Finance+AI+%7C+Agentic+Systems+%7C+MCP+%7C+Skills;Python+%E2%80%A2+TypeScript+%E2%80%A2+R+%E2%80%A2+Kubernetes+%E2%80%A2+Fabric;Ships+on+Fridays.+And+Tuesdays.+%F0%9F%9A%80" alt="Typing SVG" />
</p>

<h1 align="center">Hi, I'm James Davis 👋</h1>
<h3 align="center">Associate Director — Finance AI Implementation @ Eli Lilly</h3>
<h4 align="center">Enterprise AI platforms • Agentic systems • Cloud-native ML • Regulated pharma</h4>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=jdavis-EliLilly&label=Profile+views&color=0e75b6" alt="profile views" />
  <img src="https://img.shields.io/badge/Role-Associate%20Director-0e75b6?style=flat-square" alt="Role" />
  <img src="https://img.shields.io/badge/Focus-Finance%20AI-success?style=flat-square" alt="Focus" />
  <img src="https://img.shields.io/badge/Stack-Fabric%20%7C%20Kubernetes%20%7C%20MCP-blueviolet?style=flat-square" alt="Platform" />
  <img src="https://img.shields.io/badge/Status-Shipping-orange?style=flat-square" alt="Status" />
</p>

---

## 🚀 About Me

I lead AI platform engineering on the **Finance AI Implementation Team** at Eli Lilly, building the systems that move pharmaceutical finance from reactive reporting to **agentic, conversational intelligence**. The work spans the whole stack — certified semantic models and DAX-on-behalf-of-the-user, a multi-persona Next.js + FastAPI platform, MCP servers on enterprise Kubernetes, and the agent tooling that makes the rest of the team faster.

Before this: 2.5 years in Global Statistics delivering **72 projects at a 96% completion rate**, including org-wide observability for 100+ Shiny apps and a 10,000× AWS image-processing pipeline for clinical endpoints.

- 🛠️ **Shipping today** — IRIS / Finance Intelligence Hub, ARIA, MCP servers, batch safety signals, BD milestone early-warning
- ✍️ **Writing** — Claude Code **skills** and plugins so a whole team inherits the good version of a workflow
- 🏗️ **Scaling** — an enterprise AI platform roadmap targeting **2,000+ users** and **$50M+ ROI**
- 💬 **Ask me about** — MCP on enterprise K8s, Fabric semantic modeling in regulated environments, persona-gated multi-tenant platforms, LLM evaluation for finance, or how to migrate a Shiny fleet without losing your mind
- 📫 **Reach me** — [LinkedIn](https://www.linkedin.com/) · davis_james_nathan@lilly.com

---

## 🔥 What I'm Shipping Right Now

> *September 2026 — close commentary, price/rate/volume, and the platform that carries them*

| | Project | What it does | Where it's at |
|---|---|---|---|
| 🌸 | **IRIS** *(Finance Intelligence Hub)* | Lilly's finance-wide reporting, anomaly-detection and journal-entry platform. Next.js 16 + FastAPI + SAP S/4HANA + Fabric. One chrome, **11 personas**, each AD-gated with its own pages, data and tools. | **In production.** ~410 API endpoints, 64 ADRs, 1,800+ commits and 430+ merged PRs in 2026 |
| 💬 | **Close Commentary** | Analysts comment on any dashboard, KPI tile or table row; an LLM extracts root cause, impact direction and tags; four-eyes approval; OneLake Delta is the system of record. | Shipped Sept 2026 across every persona |
| 📈 | **Price / Rate / Volume** | PVM decomposition and tie-out for brand revenue — the variance question execs actually ask, answered from certified models. | Shipped Sept 2026 |
| 🧠 | **ARIA** | *Applied Reasoning & Insight Analyst* — turns Claude Desktop into an enterprise financial analyst. Fabric lakehouses + semantic models, staged E1–E5 methodology, DuckDB/Parquet cache, full audit trail, board-ready dashboards. | v13 → v17, distributed as a signed desktop extension |
| 🧪 | **TBSS — Traceability-Based Safety Signals** | Batch-level adverse-event disproportionality attributed to the *correct manufacturing stage* (DS / SF-DP / FIN-DP) across a many-to-many genealogy DAG. MGPS Gamma-Poisson mixture, not raw PRR. | Runs end-to-end; flip one flag for real SAP/MES data |
| 💸 | **BD Milestone Tracker** | Links *what we owe* from signed BD contracts to *when the trigger happens* — weekly diff, timestamped alerts, dollar exposure attached before the expense accrues. | Weekly cron in operation |
| ☸️ | **Platform / CATS** | MCP servers, agent runtimes and AI microservices on EKS + Fargate with Crossplane, ArgoCD and workload identity. | Reusable pattern adopted across Finance AI |

---

## ✍️ Skills, Plugins & Agent Tooling

Half of platform engineering in 2026 is **making the agent good at your codebase**. These are the reusable Claude Code skills I've authored and ship to the team:

| Skill | What it does |
|---|---|
| 🛡️ `security-deepprobe` | Pre-scan recon — maps attack surface and traces untrusted input to dangerous sinks *before* SAST/SCA/DAST. Exploitability, not pattern-matching |
| ☸️ `hangar-deploy` | Deployment manifests, Crossplane and ArgoCD for Lilly's enterprise Kubernetes platform |
| 🏗️ `hangar-cats-platform` | Generates namespace, RDS/Postgres, Redis, external-secrets and ingress YAML from platform conventions |
| 🔐 `hangar-bouncer` · `hangar-cats-bouncer` | AuthN/AuthZ via the BouncerHostConfig CRD and OPA policy, plus the legacy migration path |
| ✅ `build-check` · `linting` | Type-check → production build → fix; ESLint + Prettier + tsc, all the way to green |
| 📐 `coding-standards` | Strict typing, naming and quality rules enforced while the code is being written |
| 🧪 `review-tests` | Coverage gaps, edge cases and test quality — language and framework agnostic |

Plus **MCP servers** (FastMCP) for Fabric semantic models, and the ARIA plugin that packages the whole analyst workflow as an installable extension.

---

## 🏆 Career Impact

```
2026     Finance AI Platform Engineering
├─ IRIS / Finance Intelligence Hub — finance-wide, 11 personas, production
│  ├─ Reporting rail: Canon → certified semantic model → DAX on behalf of user
│  ├─ Close commentary + four-eyes approval, OneLake as system of record
│  ├─ Price/Rate/Volume, consolidated balance sheet, JE guardrails
│  └─ 64 architecture decision records, ~410 endpoints
├─ ARIA — enterprise analyst extension for Claude Desktop (v13 → v17)
├─ TBSS — batch-genealogy safety signals (MGPS, stage attribution)
├─ BD Milestone Tracker — contract $ × live milestone timing, weekly
├─ Claude skills + MCP servers for the platform team
└─ Contract Defense RL Gen 2 (PyTorch, multi-agent adversarial)

2025     Finance AI Implementation (Aug → )
├─ 4 production Fabric data agents (CFO-level intelligence)
├─ Enterprise Kubernetes MCP server
├─ AI Platform Strategy — $50M ROI roadmap adopted by leadership
├─ CFO Staff AI Quick Wins — adopted by 100+ finance staff
└─ Fort Knox Revenue Guardian — deep RL contract defense

2023–25  Global Statistics — Principal Software Developer
├─ 57 projects delivered · 96% completion rate
├─ VAANa clinical trial automation (multi-study, global)
├─ Shiny Usage Platform — 100+ apps, 75,000+ interactions tracked
├─ CLUWE eSign, FileLister, Admiral RAG, Digital Twins
└─ AWS Lambda pipeline — 10,000× image-processing speedup
```

**Cumulative:** 500+ users across Finance, Statistics and Clinical Ops · $11M+ documented automation value · 25+ production systems · 3 generations of RL research.

---

## 🛠️ Tech Stack

<p>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="40" height="40" alt="Python"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="40" height="40" alt="TypeScript"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/r/r-original.svg" width="40" height="40" alt="R"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nextjs/nextjs-original.svg" width="40" height="40" alt="Next.js"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" width="40" height="40" alt="React"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/fastapi/fastapi-original.svg" width="40" height="40" alt="FastAPI"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg" width="40" height="40" alt="Node.js"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/kubernetes/kubernetes-plain.svg" width="40" height="40" alt="Kubernetes"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg" width="40" height="40" alt="Docker"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/azure/azure-original.svg" width="40" height="40" alt="Azure"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/amazonwebservices/amazonwebservices-original-wordmark.svg" width="40" height="40" alt="AWS"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pytorch/pytorch-original.svg" width="40" height="40" alt="PyTorch"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postgresql/postgresql-original.svg" width="40" height="40" alt="PostgreSQL"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pandas/pandas-original.svg" width="40" height="40" alt="Pandas"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/tailwindcss/tailwindcss-original.svg" width="40" height="40" alt="Tailwind"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" width="40" height="40" alt="Git"/>
</p>

**Languages & runtimes** — Python · TypeScript · R · Node.js · SAS · Bash · DAX  
**AI & agents** — Anthropic / Claude · MCP (FastMCP) · Claude Code skills & plugins · Azure OpenAI · LangChain · Langfuse · PyTorch · FAISS · pgvector  
**Data & analytics** — Microsoft Fabric · OneLake / Delta · Direct Lake · Power BI semantic models · Databricks · SAP S/4HANA · DuckDB · Pandas · Aurora  
**Cloud & platform** — Kubernetes · EKS · Fargate · Crossplane · Helm · ArgoCD · Azure Workload Identity · AWS Lambda · Posit Connect  
**Frontend** — Next.js 16 · React · Vite · Tailwind · Shiny (R & Python)  
**DevOps** — Docker · GitHub Actions · uv · renv · pre-commit

---

## 📈 GitHub Stats

<p align="center">
  <img src="https://github-readme-streak-stats.demolab.com?user=jdavis-EliLilly&count_private=true&theme=tokyonight" />
  <br>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=jdavis-EliLilly&layout=compact&count_private=true&theme=tokyonight" />
</p>

<p align="center"><sub>Most of the real volume lives behind the enterprise org — the green squares are the tip of the iceberg. 🧊</sub></p>

---

## 🧰 Code Snippets & Patterns

<details>
<summary>🤖 <b>TypeScript — Agentic tool-call router (platform pattern)</b></summary>

```ts
import type { Tool, AgentResponse } from "./types";

interface RouteDecision {
  tool: Tool;
  confidence: number;
  reasoning: string;
}

export async function routeAgentCall(
  userQuery: string,
  availableTools: Tool[],
  context: { userRole: string; dataset?: string }
): Promise<AgentResponse> {
  const decision = await classifyIntent(userQuery, availableTools);

  if (decision.confidence < 0.65) {
    return { status: "clarify", prompt: decision.reasoning };
  }

  // Governance gate — role-based tool access
  if (!canInvoke(context.userRole, decision.tool)) {
    return { status: "denied", reason: "role not authorized" };
  }

  const result = await decision.tool.invoke(userQuery, context);

  return {
    status: "ok",
    tool: decision.tool.name,
    data: result,
    trace: { confidence: decision.confidence, path: decision.reasoning },
  };
}
```

</details>

<details>
<summary>🔐 <b>Python — DAX on behalf of the user (RLS survives the hop)</b></summary>

```python
"""The whole point: the platform must NOT be able to see more than the user can.
We exchange the caller's token for a Power BI token (OBO) so row-level security
in the certified semantic model applies to *them*, not to a service principal."""

import httpx

PBI_SCOPE = "https://analysis.windows.net/powerbi/api/.default"

async def query_as_user(user_assertion: str, dataset_id: str, dax: str) -> dict:
    async with httpx.AsyncClient(timeout=60) as http:
        # 1. On-behalf-of exchange — the user's identity carries forward
        tok = await http.post(
            f"https://login.microsoftonline.com/{TENANT}/oauth2/v2.0/token",
            data={
                "grant_type": "urn:ietf:params:oauth:grant-type:jwt-bearer",
                "client_id": CLIENT_ID,
                "client_secret": CLIENT_SECRET,
                "assertion": user_assertion,
                "scope": PBI_SCOPE,
                "requested_token_use": "on_behalf_of",
            },
        )
        tok.raise_for_status()

        # 2. Execute — RLS is enforced server-side against the real user
        res = await http.post(
            f"https://api.powerbi.com/v1.0/myorg/datasets/{dataset_id}/executeQueries",
            headers={"Authorization": f"Bearer {tok.json()['access_token']}"},
            json={"queries": [{"query": dax}], "serializerSettings": {"includeNulls": True}},
        )
        res.raise_for_status()
        return res.json()["results"][0]["tables"][0]
```

</details>

<details>
<summary>🐍 <b>Python — FastMCP server over a Fabric semantic model</b></summary>

```python
from fastmcp import FastMCP
from azure.identity import DefaultAzureCredential
import requests

mcp = FastMCP("Fabric Data Agent")

@mcp.tool()
def query_semantic_model(dataset_id: str, dax_query: str) -> dict:
    """Execute a DAX query against a Fabric semantic model."""
    token = DefaultAzureCredential().get_token(
        "https://analysis.windows.net/powerbi/api/.default"
    )
    resp = requests.post(
        f"https://api.powerbi.com/v1.0/myorg/datasets/{dataset_id}/executeQueries",
        headers={
            "Authorization": f"Bearer {token.token}",
            "Content-Type": "application/json",
        },
        json={"queries": [{"query": dax_query}]},
        timeout=30,
    )
    resp.raise_for_status()
    return resp.json()

if __name__ == "__main__":
    mcp.run()
```

</details>

<details>
<summary>🧪 <b>Python — Attribute a safety signal to the right manufacturing stage (TBSS)</b></summary>

```python
"""A drug-substance cause shows up BROADLY across a batch's finished descendants.
A packaging or storage cause shows up in ONE lot. That asymmetry is the signal."""

def localize(node, level_stats, descendants, min_breadth=0.6):
    finished = descendants[node]
    elevated = [d for d in finished if level_stats[d].eb05 > 2.0]
    breadth  = len(elevated) / max(len(finished), 1)

    if breadth >= min_breadth:
        # consistent across descendants → blame the upstream node
        return Implication(level=level_stats[node].level, node=node,
                           breadth=breadth, verdict="upstream")

    if len(elevated) == 1:
        # one lot only → packaging / storage / handling, not the substance
        return Implication(level="FIN_DP", node=elevated[0],
                           breadth=breadth, verdict="terminal")

    return None  # noise — shrinkage already told us not to chase it
```

</details>

<details>
<summary>🧠 <b>PyTorch — Deep Q-learning agent (Contract Defense RL)</b></summary>

```python
import torch, random
import torch.nn as nn
from collections import deque

class QNetwork(nn.Module):
    def __init__(self, state_size, action_size, hidden=64):
        super().__init__()
        self.net = nn.Sequential(
            nn.Linear(state_size, hidden), nn.ReLU(),
            nn.Linear(hidden, hidden),     nn.ReLU(),
            nn.Linear(hidden, action_size),
        )
    def forward(self, x): return self.net(x)

class Agent:
    def __init__(self, s, a, lr=1e-3, gamma=0.95):
        self.q = QNetwork(s, a)
        self.opt = torch.optim.Adam(self.q.parameters(), lr=lr)
        self.buf = deque(maxlen=10_000)
        self.gamma = gamma

    def act(self, state, eps=0.1):
        if random.random() < eps:
            return random.randint(0, self.q.net[-1].out_features - 1)
        with torch.no_grad():
            return self.q(torch.FloatTensor(state)).argmax().item()

    def learn(self, batch=32):
        if len(self.buf) < batch: return
        s, a, r, ns, d = zip(*random.sample(self.buf, batch))
        s, ns = torch.FloatTensor(s), torch.FloatTensor(ns)
        a, r, d = torch.LongTensor(a), torch.FloatTensor(r), torch.FloatTensor(d)
        q  = self.q(s).gather(1, a.unsqueeze(1)).squeeze()
        tq = r + (1 - d) * self.gamma * self.q(ns).max(1)[0].detach()
        loss = nn.MSELoss()(q, tq)
        self.opt.zero_grad(); loss.backward(); self.opt.step()
```

</details>

<details>
<summary>🔄 <b>Python — Retry with exponential backoff & jitter</b></summary>

```python
import time, random, functools

def retry(errors=(Exception,), tries=4, base=1, cap=30):
    def deco(fn):
        @functools.wraps(fn)
        def wrapper(*a, **kw):
            for attempt in range(tries):
                try:
                    return fn(*a, **kw)
                except errors as e:
                    if attempt == tries - 1: raise
                    delay = min(cap, base * 2 ** attempt) * random.uniform(0.8, 1.2)
                    print(f"⚠️  {type(e).__name__}: {e} — retry in {delay:.1f}s")
                    time.sleep(delay)
        return wrapper
    return deco
```

</details>

---

## 🎯 Focus Areas

- 🧠 **Agentic systems** — tool-use governance, orchestration, model routing
- ✍️ **Agent enablement** — skills, plugins and MCP servers that make a team's agent *good at their repo*
- 📊 **Semantic modeling** — Fabric Direct Lake tuning and certified models in regulated environments
- 🛡️ **AI safety & governance** — OBO/RLS, four-eyes approval, auditability, RBAC
- 🤖 **Statistical ML in pharma** — disproportionality, Bayesian shrinkage, multi-agent RL
- ☁️ **Platform engineering** — K8s-native developer experience for AI teams

---

## 🧭 Things I Believe About Building This Stuff

> ### 🪦 The hill I will die on
>
> **People should always be aiming to have LLMs figure out the logic of something once — or as few times as possible — and then turn that into reviewable and automatable code.**

- **Build the demo to be the product.** Wire the auth, the RLS and the audit trail on day one, and the demo *is* the thing you ship.
- **Write the code.** An LLM reasoning its way to the same answer on every run is a cost and a coin flip; the answer, written down as code, is a diff someone can review.
- **Shrink before you shout.** A signal that survives shrinkage is worth a phone call; a raw ratio is worth a shrug.
- **Ship quick, stay agile my friends.** 430 merged PRs beats one heroic branch.

---

<p align="center"><i>"Any fool can write code that a computer can understand. Good programmers write code that humans can understand." — Martin Fowler</i></p>

<p align="center">
  <b>Thanks for stopping by.</b><br>
  <sub>Building the enterprise AI platform that pharmaceutical finance actually deserves — one merged PR at a time. 🚀</sub>
</p>
