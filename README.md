<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:1f6feb,100:8957e5&height=140&section=header&text=UTTAM&fontColor=ffffff&fontSize=52&fontAlignY=40&desc=AI%20%2F%20ML%20ENGINEER&descAlignY=62&descSize=16" width="100%" alt="header"/>

### `"I teach machines to read, see and reason."`

</div>

```text
┌──────────────────────────────────────────────────────────────────────────┐
│  uttam@ai-lab:~$ ./boot --profile                                        │
│                                                                          │
│        o───o───o            ┌─ READ ────► NLP · LLMs · RAG               │
│       ╱│╲ ╱│╲ ╱│╲           ├─ SEE ─────► CNNs · OpenCV · Vision         │
│      o─┼─o─┼─o─┼─o  ──►     ├─ REASON ──► Agents · Tools · Memory        │
│       ╲│╱ ╲│╱ ╲│╱           └─ ACT ─────► FastAPI · Docker · Shipping    │
│        o───o───o                                                         │
│                                                                          │
│  [OK] intelligence_engine ....... online                                 │
│  [OK] perception_engine ......... online                                 │
│  [OK] language_engine ........... online                                 │
│  [OK] autonomous_systems ........ online                                 │
│  [..] learning_loop ............. running (never terminates)            │
└──────────────────────────────────────────────────────────────────────────┘
```

<div align="center">

![Role](https://img.shields.io/badge/ROLE-AI%20%2F%20ML%20ENGINEER-1f6feb?style=for-the-badge&labelColor=0d1117)
![Focus](https://img.shields.io/badge/FOCUS-AGENTIC%20AI%20·%20LLMs%20·%20VISION-8957e5?style=for-the-badge&labelColor=0d1117)
![Status](https://img.shields.io/badge/STATUS-BUILDING-2ea043?style=for-the-badge&labelColor=0d1117)

</div>

---

## `// 01` &nbsp; ENGINEERING IDENTITY

I build intelligent systems that do something useful once they leave the notebook.

My work sits where **language models meet real software**: RAG pipelines that ground answers in data, agents that call tools and keep memory, and LLM applications wrapped in clean APIs. Alongside that, I work in **computer vision** and **NLP**, teaching models to interpret images and text with the same rigor I apply to everything else: measure, iterate, ship.

- 🔬 I treat every project as an experiment: hypothesis, baseline, evaluation, iteration.
- 🧱 I care about the engineering around the model: APIs, containers, data layers, reproducibility.
- 🔁 I'm always in learning mode. The stack changes quickly, so the fundamentals and the feedback loop matter most.

---

## `// 02` &nbsp; SIGNATURE IDENTITY &nbsp;`identity.py`

```python
from dataclasses import dataclass, field
from typing import Callable

@dataclass
class Engineer:
    name: str = "Uttam"
    mission: str = "Teach machines to read, see and reason."
    languages: tuple = ("Python", "C++")

    # what I give my agents -> and what I try to live by
    tools: dict[str, Callable] = field(default_factory=lambda: {
        "search_papers":  lambda q: f"read everything about {q}",
        "build_prototype": lambda idea: f"{idea} -> working demo",
        "evaluate":        lambda model: f"measure {model}, don't guess",
        "ship":            lambda app: f"FastAPI + Docker -> {app}",
    })

    memory: dict = field(default_factory=lambda: {
        "short_term": "current sprint & open bugs",
        "long_term":  ["RAG", "agents", "CV", "NLP", "RL"],
        "episodic":   "every failed experiment taught me something",
    })

    principles: tuple = (
        "baseline before brilliance",
        "ground the model in data",
        "if it can't be evaluated, it can't be improved",
        "a demo is a hypothesis, production is the proof",
    )

    def reason(self, problem: str) -> str:
        plan = ["understand", "retrieve context", "prototype",
                "evaluate", "iterate", "deploy"]
        return f"{problem} -> " + " -> ".join(plan)

    def learn(self):
        while True:                 # the only infinite loop I approve of
            self.read(); self.build(); self.break_it(); self.fix_it()


if __name__ == "__main__":
    Engineer().learn()
```

---

## `// 03` &nbsp; AI ENGINEERING DIVISIONS

> **Status key** &nbsp; 🟢 `PRACTICED` hands-on, used in projects &nbsp;·&nbsp; 🟡 `BUILDING` actively developing &nbsp;·&nbsp; 🔵 `EXPLORING` research and experiments

### ▸ DIVISION 01 — INTELLIGENCE ENGINE &nbsp;`🟢 PRACTICED`
*Where models are trained, tuned and judged.*

![ML](https://img.shields.io/badge/Machine%20Learning-0d1117?style=flat-square&logo=scikitlearn&logoColor=F7931E)
![DL](https://img.shields.io/badge/Deep%20Learning-0d1117?style=flat-square&logo=pytorch&logoColor=EE4C2C)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)

### ▸ DIVISION 02 — AUTONOMOUS SYSTEMS &nbsp;`🟢 PRACTICED`
*Agents that plan, call tools, remember, and act.*

![Agentic AI](https://img.shields.io/badge/Agentic%20AI-8957e5?style=flat-square)
![LLMs](https://img.shields.io/badge/LLMs-0d1117?style=flat-square&logo=openai&logoColor=white)
![RAG](https://img.shields.io/badge/RAG-1f6feb?style=flat-square)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![Agno](https://img.shields.io/badge/Agno-000000?style=flat-square)
![Tool Calling](https://img.shields.io/badge/Tool%20Calling-2ea043?style=flat-square)
![Memory Systems](https://img.shields.io/badge/Memory%20Systems-d29922?style=flat-square)

### ▸ DIVISION 03 — PERCEPTION ENGINE &nbsp;`🟢 PRACTICED`
*Teaching models to see.*

![Computer Vision](https://img.shields.io/badge/Computer%20Vision-0d1117?style=flat-square&logo=opencv&logoColor=5C3EE8)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![CNNs](https://img.shields.io/badge/CNNs-1f6feb?style=flat-square)
![Neural Networks](https://img.shields.io/badge/Neural%20Networks-8957e5?style=flat-square)
![Image Processing](https://img.shields.io/badge/Image%20Processing-0d1117?style=flat-square)

### ▸ DIVISION 04 — LANGUAGE ENGINE &nbsp;`🟡 BUILDING`
*Teaching models to read and write.*

![NLP](https://img.shields.io/badge/NLP-0d1117?style=flat-square&logo=huggingface&logoColor=FFD21E)
![Transformers](https://img.shields.io/badge/Transformers-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![T5](https://img.shields.io/badge/T5-1f6feb?style=flat-square)
![Summarization](https://img.shields.io/badge/Text%20Summarization-0d1117?style=flat-square)
![GenAI](https://img.shields.io/badge/Generative%20AI-8957e5?style=flat-square)

### ▸ DIVISION 05 — ENGINEERING CORE &nbsp;`🟢 PRACTICED`
*The foundation that turns models into products.*

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

### ▸ DIVISION 06 — DATA SYSTEMS &nbsp;`🟢 PRACTICED`
*Where every experiment begins.*

![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=flat-square)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white)

### ▸ ON THE RESEARCH HORIZON &nbsp;`🔵 EXPLORING`

![RL](https://img.shields.io/badge/Reinforcement%20Learning-0d1117?style=flat-square)
![Multi-agent](https://img.shields.io/badge/Multi--Agent%20Systems-0d1117?style=flat-square)
![Multimodal](https://img.shields.io/badge/Multimodal%20Models-0d1117?style=flat-square)

---

## `// 04` &nbsp; RESEARCH LAB MAP

```text
                         ┌────────────────────┐
                         │   UTTAM AI LAB     │
                         └─────────┬──────────┘
        ┌───────────────┬──────────┴────────┬────────────────┐
        ▼               ▼                   ▼                ▼
 ┌─────────────┐ ┌─────────────┐   ┌───────────────┐ ┌───────────────┐
 │INTELLIGENCE │ │ PERCEPTION  │   │   LANGUAGE    │ │  AUTONOMOUS   │
 │  SYSTEMS    │ │  SYSTEMS    │   │   SYSTEMS     │ │   SYSTEMS     │
 ├─────────────┤ ├─────────────┤   ├───────────────┤ ├───────────────┤
 │ ML · DL     │ │ CV · CNNs   │   │ NLP · T5      │ │ Agents · RAG  │
 │ PyTorch     │ │ OpenCV      │   │ Transformers  │ │ LangChain     │
 │ TensorFlow  │ │ Image Proc. │   │ GenAI         │ │ Agno · Memory │
 └─────────────┘ └─────────────┘   └───────────────┘ └───────────────┘
        └───────────────┴──────────┬────────┴────────────────┘
                                   ▼
                      ┌──────────────────────────┐
                      │    ENGINEERING CORE      │
                      │ Python · C++ · FastAPI   │
                      │ Docker · SQL · Git       │
                      └──────────────────────────┘
```

---

## `// 05` &nbsp; EXPERIMENT LOG &nbsp;*(featured projects)*

> Replace the placeholders below with your real repositories.

| ID | Project | Division | What it does | Stack |
|:--:|:--------|:--------:|:-------------|:------|
| `EXP-001` | [**Your RAG Project**](https://github.com/YOUR_USERNAME/REPO) | 02 | Retrieval-augmented Q&A grounded in your documents | `LangChain` `FastAPI` `SQL` |
| `EXP-002` | [**Your Agent Project**](https://github.com/YOUR_USERNAME/REPO) | 02 | Tool-calling agent with persistent memory | `Agno` `Python` `Supabase` |
| `EXP-003` | [**Your Vision Project**](https://github.com/YOUR_USERNAME/REPO) | 03 | Image classification / detection pipeline | `PyTorch` `OpenCV` |
| `EXP-004` | [**Your Summarizer**](https://github.com/YOUR_USERNAME/REPO) | 04 | Text summarization with a fine-tuned T5 | `Transformers` `Streamlit` |

---

## `// 06` &nbsp; BUILD PIPELINE

```text
 IDEA ──► DATA ──► BASELINE ──► MODEL ──► EVALUATE ──► API ──► CONTAINER ──► SHIP
   │                                          ▲                                │
   └──────────────────────── iterate ─────────┴──────────── feedback ◄─────────┘
```

---

## `// 07` &nbsp; CURRENT SYSTEM STATE

```yaml
now:
  building:   agentic workflows with tool calling and memory
  refining:   RAG retrieval quality and evaluation
  studying:   reinforcement learning, multimodal models
  sharpening: problem solving, C++ fundamentals, system design
open_to:
  - AI/ML engineering roles & internships
  - open-source collaboration
  - interesting problems that need a model that can read, see or reason
```

---

<div align="center">

### `> ping uttam`

[![GitHub](https://img.shields.io/badge/GitHub-0d1117?style=for-the-badge&logo=github&logoColor=white)](https://github.com/YOUR_USERNAME)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/YOUR_HANDLE)
[![Email](https://img.shields.io/badge/Email-8957e5?style=for-the-badge&logo=gmail&logoColor=white)](mailto:YOUR_EMAIL)

<sub>`while alive: read(); see(); reason(); build()`</sub>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:8957e5,50:1f6feb,100:0d1117&height=90&section=footer" width="100%" alt="footer"/>

</div>
