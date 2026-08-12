
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=egg&color=0:000000,100:E63946&height=150&section=header&text=ruth&fontColor=ffffff&fontSize=50&fontAlignY=55&animation=fadeIn&desc=AI%2FML%20Engineer&descAlignY=80&descAlign=50" width="100%"/>
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=18&duration=2500&pause=1200&color=E63946&center=true&vCenter=true&width=560&lines=root%40ruth%3A~%24+whoami;building+self-correcting+systems;ex-intern+%40+quiddity" alt="terminal typing" />
</p>

<p align="center"><img src="https://img.shields.io/badge/-black?style=flat-square&color=E63946&label=%20" height="3" width="60%"/></p>

```
┌──(ruth@github)-[~]
└─$ cat about.md
```

Computer Science undergrad specializing in AI/ML at VIT-AP University. Previously interned at Quiddity in Hyderabad, building a multilingual RAG agent from parsing to retrieval.

I care about what a system does when it fails — silent failure vs. self-diagnosis and recovery. That's the thread running through everything below.

```
┌──(ruth@github)-[~]
└─$ ls stack/
```

<p align="left">
  <img src="https://img.shields.io/badge/Python-000000?style=for-the-badge&logo=python&logoColor=E63946" />
  <img src="https://img.shields.io/badge/FastAPI-000000?style=for-the-badge&logo=fastapi&logoColor=E63946" />
  <img src="https://img.shields.io/badge/Docker-000000?style=for-the-badge&logo=docker&logoColor=E63946" />
  <img src="https://img.shields.io/badge/Milvus-000000?style=for-the-badge&logo=milvus&logoColor=E63946" />
  <img src="https://img.shields.io/badge/Gemini_API-000000?style=for-the-badge&logo=googlegemini&logoColor=E63946" />
  <img src="https://img.shields.io/badge/SQL-000000?style=for-the-badge&logo=postgresql&logoColor=E63946" />
  <img src="https://img.shields.io/badge/Java-000000?style=for-the-badge&logo=openjdk&logoColor=E63946" />
  <img src="https://img.shields.io/badge/pandas-000000?style=for-the-badge&logo=pandas&logoColor=E63946" />
  <img src="https://img.shields.io/badge/pytest-000000?style=for-the-badge&logo=pytest&logoColor=E63946" />
</p>

<p align="center"><img src="https://img.shields.io/badge/-black?style=flat-square&color=E63946&label=%20" height="3" width="60%"/></p>

```
┌──(ruth@github)-[~]
└─$ ls projects/
```

### `01_developer-knowledge-assistant`
RAG-powered assistant for codebases — embeddings, vector search, FastAPI backend.

```mermaid
%%{init: {'theme':'dark', 'themeVariables': {'primaryColor':'#000000','primaryTextColor':'#ffffff','primaryBorderColor':'#E63946','lineColor':'#E63946','tertiaryColor':'#000000'}}}%%
flowchart LR
    A[Codebase] --> B[Chunk & Embed]
    B --> C[(Vector Store)]
    D[Question] --> E[Retrieve]
    C --> E
    E --> F[LLM Answer]
```
[→ repo](#)

### `02_text-to-sql-interface`
Translates natural language questions into SQL queries against a real database schema.

```mermaid
%%{init: {'theme':'dark', 'themeVariables': {'primaryColor':'#000000','primaryTextColor':'#ffffff','primaryBorderColor':'#E63946','lineColor':'#E63946','tertiaryColor':'#000000'}}}%%
flowchart LR
    A[Question] --> B[LLM + Schema]
    B --> C[SQL]
    C --> D[(Database)]
    D --> E[Result]
```
[→ repo](#)

### `03_multilingual-rag-agent`
Hybrid retrieval over multilingual, OCR'd documents — structure-aware chunking, Milvus, Gemini API.

```mermaid
%%{init: {'theme':'dark', 'themeVariables': {'primaryColor':'#000000','primaryTextColor':'#ffffff','primaryBorderColor':'#E63946','lineColor':'#E63946','tertiaryColor':'#000000'}}}%%
flowchart LR
    A[Document] --> B[OCR / Parse]
    B --> C[Translate]
    C --> D[Chunk]
    D --> E[(Milvus)]
    F[Query] --> G[Retrieve]
    E --> G
    G --> H[Gemini Answer]
```
[→ repo](#)

### `04_autonomous-coding-agent` `IN_PROGRESS`
Self-correcting code execution: generate, sandbox, observe, fix, retry. Design complete, build underway.

```mermaid
%%{init: {'theme':'dark', 'themeVariables': {'primaryColor':'#000000','primaryTextColor':'#ffffff','primaryBorderColor':'#E63946','lineColor':'#E63946','tertiaryColor':'#000000'}}}%%
flowchart TD
    A[Task] --> B[Generate Code]
    B --> C[Docker Sandbox]
    C --> D{Success?}
    D -->|no| F[Analyze Failure]
    F --> B
    D -->|yes| E[Validate]
    E --> G{Valid?}
    G -->|no| F
    G -->|yes| H[Done]
```
[→ repo](#)

<p align="center"><img src="https://img.shields.io/badge/-black?style=flat-square&color=E63946&label=%20" height="3" width="60%"/></p>

```
┌──(ruth@github)-[~]
└─$ cat contact.txt
```

LinkedIn: [add your link]
Email: [add your email]

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=egg&color=0:E63946,100:000000&height=80&section=footer" width="100%"/>
</p>

<!--
SETUP NOTES FOR RUTH (delete before publishing):
1. Save as README.md in a repo named exactly your GitHub username — GitHub renders it
   as your profile page automatically.
2. Replace every "#" with real repo URLs, and the LinkedIn/email placeholders.
3. Terminal prompt blocks (the ┌──(ruth@github)... lines) are plain text in code fences —
   edit "ruth" to your actual username if you want it to match exactly.
4. Mermaid diagrams have a dark theme init line at the top of each block so they render
   black/red instead of GitHub's default light theme — edit the boxes/arrows if your
   actual pipeline differs.
5. Banner top/bottom and typing animation are free third-party services (capsule-render,
   readme-typing-svg) — no signup needed.
-->
