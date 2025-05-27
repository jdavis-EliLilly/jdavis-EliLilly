<!--
========================================================================
│  README.md  ◇  James “JD” Davis – Principal Software Developer
========================================================================
-->

<!-- Dynamic typing header ------------------------------------------------>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&duration=3000&pause=1000&center=true&width=435&lines=Principal+Software+Developer;Python+%7C+R+%7C+ML+Engineer;Welcome+to+my+GitHub+Profile+%F0%9F%91%8B" alt="Typing SVG" />
</p>


<h1 align="center">Hi there 👋, I'm James Davis</h1>
<h3 align="center">Principal Software Developer | Python &amp; R Enthusiast | Data Automation &amp; ML</h3>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=jdavis-EliLilly&label=Profile+views&color=0e75b6" alt="profile views" />
</p>

---

## 🚀 About Me

- 🔭 **Currently shipping**
  - 🐍 **TFL Finder** – a Python Shiny + FAISS search tool for clinical TFL PDFs
  - 🔧 **CLUWE Cron Scheduler** – R Shiny app that inserts/edits cron jobs inside the “CLUWE block” on our HPC
  - 📧 **VAANa** – R automation that emails sites about upcoming patient visits (now in production)
  - 📊 **Usage-Analytics Dashboard** – R Shiny + ApexCharts, upgrading to R 4.4.2
  - 🤖 **Code Gen** – generative-AI assistant that turns study specs into R/SAS code

- 🌱 **In the lab**
  - Vector search with **FAISS** & **pgvector**
  - **LangChain** agent patterns for regulated environments
  - Designing **secure / high-perf / cost-opt** serverless on AWS (Lambda + Aurora + Gateway) – *studying for SAA-C03 retake*

- 💬 Ping me about:
  - Python & R automation, Shiny (both flavors), CI/CD on Posit, LLM evaluation in pharma
  - AWS Glue, PySpark, and data lake ETL
  - “Can I weld a dove-blind on tractor hydraulics?” – yes, that too 😄

- 📫 **davis_james_nathan@lilly.com**

---

<h3 align="left">🛠️ Languages and Tools:</h3>
<p>
  <!-- Python -->
  <a href="https://www.python.org" target="_blank" rel="noreferrer">
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg"
         width="40" height="40" alt="Python"/>
  </a>

  <!-- R -->
  <a href="https://www.r-project.org" target="_blank" rel="noreferrer">
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/r/r-original.svg"
         width="40" height="40" alt="R"/>
  </a>

  <!-- AWS -->
  <a href="https://aws.amazon.com" target="_blank" rel="noreferrer">
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/amazonwebservices/amazonwebservices-original-wordmark.svg"
         width="40" height="40" alt="AWS"/>
  </a>

  <!-- PostgreSQL -->
  <a href="https://www.postgresql.org" target="_blank" rel="noreferrer">
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postgresql/postgresql-original.svg"
         width="40" height="40" alt="PostgreSQL"/>
  </a>

  <!-- Pandas -->
  <a href="https://pandas.pydata.org" target="_blank" rel="noreferrer">
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pandas/pandas-original.svg"
         width="40" height="40" alt="Pandas"/>
  </a>

  <!-- Posit / Python Shiny -->
  <a href="https://shiny.posit.co/py/" target="_blank" rel="noreferrer">
    <img src="https://vectorlogo.zone/logos/rstudio/rstudio-icon.svg"
         width="40" height="40" alt="Posit Shiny"/>
  </a>

  <!-- Vector (Timber Vector) -->
  <a href="https://vector.dev" target="_blank" rel="noreferrer">
    <img src="https://raw.githubusercontent.com/vectordotdev/vector/master/website/static/img/vector-logo.svg"
         width="40" height="40" alt="Vector"/>
  </a>
</p>

---

## 📈 GitHub Stats

<p align="center">
  <img src="https://github-readme-streak-stats.demolab.com?user=jdavis-EliLilly&count_private=true&theme=dark" />
  <br>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=jdavis-EliLilly&layout=compact&theme=dark" />
</p>

---

## 🔔 Latest Metrics
<p align="center">
  <img src="https://metrics.lecoq.io/jdavis-EliLilly?template=classic&base.header=0&gists=1&lines=1&config.timezone=America%2FChicago" />
</p>

---

## 🧰 Cool Tricks & Snippets
<details>
<summary>🌗 R Shiny – one-click Dark / Light toggle (Flatly ↔ Darkly)</summary>

```r
library(shiny)
library(shinyswatch)
ui <- fluidPage(
  tags$head(
    # Sun/Moon button
    tags$style("#modeBtn{position:fixed;top:10px;right:10px;font-size:24px;border:none;background:transparent;}")),
  actionButton("modeBtn", "", icon = icon("moon")),
  h2("Hello world")
)

server <- function(input, output, session){
  current <- reactiveVal("flatly")  # default
  observeEvent(input$modeBtn,{
    new <- if (current()=="flatly") "darkly" else "flatly"
    current(new); shinyswatch::theme_switch(new)
    updateActionButton(session, "modeBtn",
                       icon = icon(if (new=="flatly") "moon" else "sun"))
  })
}

shinyswatch::run_with_themer(ui, server, theme = "flatly")
````

</details>

<details>
<summary>⚙️ Git – create a <code>POSIT_DEPLOY</code> branch tracking <code>origin/dev</code></summary>

```bash
git switch --track -c POSIT_DEPLOY origin/dev
git push -u origin POSIT_DEPLOY
```

*Perfect for your Posit Connect deployments.*

</details>

<details>
<summary>🐍 Python – quick “retry with exponential backoff” decorator</summary>

```python
import time, functools, random

def retry(errors, tries=4, cap=30):
    """Retry `errors` up to `tries` with jittered exponential back-off."""
    def deco(fn):
        @functools.wraps(fn)
        def inner(*a, **kw):
            delay = 1
            for attempt in range(tries):
                try:
                    return fn(*a, **kw)
                except errors as e:
                    if attempt == tries-1:
                        raise
                    sleep = min(cap, delay * 2 ** attempt) * random.uniform(0.8, 1.2)
                    print(f"⚠️  {e} – retrying in {sleep:.1f}s")
                    time.sleep(sleep)
        return inner
    return deco

# Usage
@retry((ConnectionError, TimeoutError))
def fetch(url): ...
```

</details>

---

<p align="center"><i>"Code is like humor. When you have to explain it, it’s bad." – Cory House</i></p>
<p align="center"><b>Thanks for stopping by!</b></p>
