<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:161b22,100:00d9ff&height=120&section=header"/>

<div align="center">
  
# HERBERT K. YEBOAH

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=3000&pause=1000&color=00D9FF&center=true&vCenter=true&multiline=true&repeat=true&width=600&height=100&lines=Software+Engineer+%7C+AI%2FML+Developer;Building+Intelligent+Systems+That+Matter;Solving+Real-World+Problems+with+AI)](https://git.io/typing-svg)

<p>
  <a href="https://github.com/devilsfave?tab=followers">
    <img src="https://img.shields.io/github/followers/devilsfave?label=Followers&style=social" alt="GitHub followers">
  </a>
  <img src="https://komarev.com/ghpvc/?username=devilsfave&label=Profile+Views&color=00d9ff&style=flat" alt="Profile views"/>
  <a href="mailto:herbertyeboah123@gmail.com">
    <img src="https://img.shields.io/badge/Email-herbertyeboah123%40gmail.com-00d9ff?style=flat&logo=gmail&logoColor=white" alt="Email"/>
  </a>
</p>

</div>

---

## 🧬 About Me
```python
class SoftwareEngineer:
    def __init__(self):
        self.name = "Herbert Kwame Yeboah"
        self.role = "Software Engineer & AI/ML Developer"
        self.location = "Ghana 🇬🇭"
        self.education = "BSc Computer Science - UENR (2024)"
        self.current_focus = "AI-powered Solutions for Real-World Impact"
        
    def get_skills(self):
        return {
            "languages": ["Python", "TypeScript", "JavaScript", "SQL", "C++", "Java"],
            "ai_ml": ["TensorFlow", "Keras", "Scikit-learn", "NumPy", "Pandas"],
            "web": ["Next.js", "React", "Node.js", "Flask", "Tailwind CSS"],
            "cloud": ["Google Cloud", "Firebase", "Docker", "Railway"],
            "databases": ["PostgreSQL", "MongoDB", "Redis", "Firestore"]
        }
    
    def get_certifications(self):
        return [
            "ALX Africa - AI Career Essentials (2024)",
            "ALX Africa - Software Engineering (2024)",
            "Udemy - SQL Masterclass (2024)"
        ]

me = SoftwareEngineer()
```

**📍 Based in Ghana 🇬🇭 | 🎓 BSc Computer Science (2024)**

I am a Software Engineer & AI/ML Developer passionate about transforming complex ideas into production-ready code. My foundation blends high-performance software engineering with expertise in Machine Learning, allowing me to build end-to-end intelligent systems that solve real-world problems and make life better through technology.

<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=devilsfave&bg_color=0d1117&color=00d9ff&line=00d9ff&point=ffffff&area=true&area_color=00d9ff&hide_border=true" width="95%"/>
</div>

---

## 🚀 Featured Projects

---

### ⭐ [DagPipe](https://github.com/devilsfave/dagpipe) — Flagship Project
**Zero-Cost, Crash-Proof LLM Orchestration Framework**

<p>
  <img src="https://github.com/devilsfave/dagpipe/actions/workflows/test.yml/badge.svg" alt="Tests" />
  <img src="https://github.com/devilsfave/dagpipe/actions/workflows/security.yml/badge.svg" alt="Security Audit" />
  <img src="https://img.shields.io/pypi/v/dagpipe-core?color=FF4500&style=flat-square" alt="PyPI Version" />
  <img src="https://img.shields.io/pypi/pyversions/dagpipe-core?style=flat-square&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/github/license/devilsfave/dagpipe?style=flat-square&color=00d9ff" alt="License" />
  <img src="https://img.shields.io/badge/MCP-Live-00d9ff?style=flat-square" alt="MCP" />
  <img src="https://img.shields.io/badge/Smithery-Listed-FF4500?style=flat-square" alt="Smithery" />
  <a href="https://www.bestpractices.dev/projects/12089"><img src="https://www.bestpractices.dev/projects/12089/badge" alt="OpenSSF Best Practices" /></a>
</p>

> NeurIPS 2025 research analyzing **1,642 real-world multi-agent execution traces** found a **41–86.7% failure rate** across 7 state-of-the-art open-source systems. The root cause: cascading error propagation. **DagPipe makes cascade failure structurally impossible.**

The reliability layer that makes AI workflows safe to ship — crash recovery, schema validation, and intelligent cost routing — in 150 lines of Python. Runs entirely on **free-tier APIs. Zero infrastructure. Zero subscription.**

```
Pipeline: research → outline → draft → edit → publish
                                  ↑
                            crashed here

Re-run → research ✓ (restored) → outline ✓ (restored) → draft (re-runs) → ...
```

**Technical Highlights:**

| 🔴 Without DagPipe | 🟢 With DagPipe |
|---|---|
| Pipeline crashes = start over from zero | **JSON checkpointing**: resume from last successful node |
| Paying for large models on every task | **Cognitive routing**: route easy tasks to free-tier models |
| LLM returns malformed JSON | **Guaranteed structured output**: auto-retry with error feedback |
| Tight coupling to one provider | **Provider-agnostic**: any Python callable works |
| Silent bad data passes through | **Semantic assertions**: catch structurally valid but wrong output |
| Complete failure context lost | **Dead Letter Queue**: every failure saved to disk automatically |

**Key Features (v0.2.0):**
- 🔁 **Crash Recovery** — JSON checkpointing per node; resume exactly where you stopped
- 🧠 **Smart Model Router** — auto-selects model by task complexity; escalates on failure/rate-limit
- 📋 **Constrained Generation** — Pydantic schema validation with auto-retry on malformed output
- 🔒 **Context Isolation** — nodes only access their declared dependencies; safe for sensitive data
- 🗂️ **Live Model Registry** — self-maintaining database of free-tier availability; refreshes every 24h
- ⚙️ **Pluggable Checkpoint Backends** — swap filesystem for Redis, S3, or any custom store
- 🌐 **MCP Server** — generate crash-proof pipelines via Claude Desktop, Cursor, or Windsurf

**Test Coverage:** 108 tests · 5 modules · 0 regressions · Python 3.12 + 3.13

**Available On:**

<p>
  <a href="https://pypi.org/project/dagpipe-core/"><img src="https://img.shields.io/badge/PyPI-dagpipe--core-FF4500?style=for-the-badge&logo=pypi&logoColor=white"/></a>
  <a href="https://smithery.ai/server/gastronomic-desk/dagpipe-generator"><img src="https://img.shields.io/badge/Smithery-MCP_Server-00d9ff?style=for-the-badge"/></a>
  <a href="https://apify.com/gastronomic_desk/pipeline-generator"><img src="https://img.shields.io/badge/Apify-Pipeline_Generator-1ABC9C?style=for-the-badge"/></a>
</p>

<p>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/Pydantic-E92063?style=flat-square&logo=pydantic&logoColor=white"/>
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/>
<img src="https://img.shields.io/badge/Groq-FF4500?style=flat-square&logoColor=white"/>
<img src="https://img.shields.io/badge/Gemini-4285F4?style=flat-square&logo=google&logoColor=white"/>
<img src="https://img.shields.io/badge/MCP-Live-00d9ff?style=flat-square"/>
<img src="https://img.shields.io/badge/MIT-License-green?style=flat-square"/>
</p>

```bash
pip install dagpipe-core
```

---

<table>
<tr>
<td width="50%" valign="top">

### 🔬 [DermaVision AI](https://github.com/devilsfave/Dermavision_AI)
**AI-Powered Skin Disease Classification System**

Deep learning platform democratizing dermatological care across Africa using advanced neural networks.

**Technical Highlights:**
- MobileNetV2 + Spatial Transformer Network
- 87.27% validation accuracy (HAM10000)
- TensorFlow Lite mobile deployment
- Full-stack telemedicine platform

<p>
<img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white"/>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white"/>
<img src="https://img.shields.io/badge/GCP-4285F4?style=flat-square&logo=googlecloud&logoColor=white"/>
</p>

</td>
<td width="50%" valign="top">

### 🎰 [Frankenstein](https://github.com/devilsfave/Frankenstein)
**Algorithmic Trading & Risk Management Engine**

Production-ready system demonstrating advanced mathematical optimization and real-time data processing.

**Technical Highlights:**
- Real-time probability calculations
- Async architecture (asyncio/aiohttp)
- Multi-layered risk assessment
- Docker + Railway deployment

<p>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/>
<img src="https://img.shields.io/badge/asyncio-3776AB?style=flat-square&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/Railway-0B0D0E?style=flat-square&logo=railway&logoColor=white"/>
</p>

</td>
</tr>
</table>

---

## 🛠️ Technology Arsenal

<div align="center">

### Languages & Core
<p>
<img src="https://skillicons.dev/icons?i=python,typescript,javascript,java,cpp,cs&theme=dark" />
</p>

### AI/ML & Data Science
<p>
<img src="https://skillicons.dev/icons?i=tensorflow,pytorch,sklearn&theme=dark" />
<img src="https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white"/>
<img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white"/>
<img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white"/>
</p>

### Web Development
<p>
<img src="https://skillicons.dev/icons?i=nextjs,react,nodejs,flask,tailwind,html,css&theme=dark" />
</p>

### Cloud & DevOps
<p>
<img src="https://skillicons.dev/icons?i=gcp,firebase,docker,git,linux,bash&theme=dark" />
</p>

### Databases
<p>
<img src="https://skillicons.dev/icons?i=postgres,mongodb,redis&theme=dark" />
</p>

</div>

---

## 📊 GitHub Analytics


<div align="center">
  <img src="https://nirzak-streak-stats.vercel.app/?user=devilsfave&theme=react&background=0d1117&ring=00d9ff&fire=00d9ff&currStreakLabel=00d9ff&border=30363d" alt="GitHub Streak"/>
</div>

<br/>


---

## 📜 Certifications & Education

<div align="center">

| 🎓 Credential | 🏛️ Institution | 📅 Year |
|:-------------:|:-------------:|:-------:|
| **BSc Computer Science** | University of Energy & Natural Resources | 2024 |
| **AI Career Essentials** | ALX Africa | July 2024 |
| **Software Engineering** | ALX Africa | June 2024 |
| **SQL Masterclass** | Udemy | 2024 |

</div>

---

## 📈 Weekly Development Breakdown

<!--START_SECTION:waka-->
```text
Python       12 hrs 45 mins  ███████████░░░░░░░  45.2%
TypeScript   8 hrs 30 mins   ███████░░░░░░░░░░░  30.1%
JavaScript   3 hrs 15 mins   ███░░░░░░░░░░░░░░░  11.5%
SQL          2 hrs 10 mins   ██░░░░░░░░░░░░░░░░   7.7%
Other        1 hr 30 mins    █░░░░░░░░░░░░░░░░░   5.5%
```
<!--END_SECTION:waka-->

---

## 🌐 Connect With Me

<div align="center">
  
<a href="mailto:herbertyeboah123@gmail.com">
  <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail"/>
</a>
<a href="https://linkedin.com/in/herbert-yeboah">
  <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
</a>
<a href="https://instagram.com/devlin_39">
  <img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram"/>
</a>
<a href="https://reddit.com/user/39th_Demon">
  <img src="https://img.shields.io/badge/Reddit-FF4500?style=for-the-badge&logo=reddit&logoColor=white" alt="Reddit"/>
</a>
<a href="https://github.com/devilsfave">
  <img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
</a>

</div>

---

<div align="center">
  
### 💡 *"Using AI to solve real-world problems and make life better"*

<img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=algolia" alt="Dev Quote"/>

</div>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:161b22,100:00d9ff&height=120&section=footer"/>
