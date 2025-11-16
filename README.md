<!-- README.md for github.com/SidratEvan -->

<h1 align="center">Hey, I'm SK Sidratul Islam Priyo </h1>

<p align="center">
  Computer Science @ University of Saskatchewan • Building tools that actually help people 
</p>

---

### What I’ve built

Here are some projects I’m proud of — each one started with a real problem I wanted to solve.

####  Vulnerability Tracker
<sub><i>Python, Flask, SQLite, HTML/CSS</i></sub>  
A lightweight web app to log IT assets and track security vulnerabilities.
- Keep a clean inventory of assets and their risk levels
- Score and track vulnerabilities by severity & status
- Simple UI so even non-technical teammates can use it

 `Repo:` `vuln-tracker` (on my GitHub)

---

#### Mine Safety Sensor Monitor
<sub><i>C, File I/O, Logging, Continuous Monitoring</i></sub>  
A C program that simulates underground mine safety sensors (temperature, methane, equipment load).
- Continuously monitors sensor readings
- Triggers alerts when conditions become hazardous
- Logs everything with timestamps for auditing & analysis

Built to feel like something a real operations team could rely on.

---

#### Shipment Optimizer
<sub><i>Java, OOP, CSV Logging, Git</i></sub>  
A console-based logistics optimizer for potash/uranium shipment planning.
- Compares rail, truck, and ship based on cost and time
- Supports “normal” vs “urgent” priorities with best-option recommendations
- Exports logs to CSV for later review

 Repo: `shipment-optimizer`  
This project is very close to my heart because it’s my first serious attempt to mix domain logic + clean Java design.

---

#### Internship Assistant Webapp
<sub><i>Python, Streamlit, Flask, BeautifulSoup, Pandas</i></sub>  
A web app to make internship hunting less painful.
- Fetches live job postings from ATS platforms (Ashby, Greenhouse, etc.)
- Lets you filter by role, location, and keyword
- Includes a simple application tracker and a cover-letter generator with PDF export

Built for students like me who are juggling school, work, and applications at the same time.

---

#### Travel Budget Planner
<sub><i>Python, Streamlit, Pandas, JSON</i></sub>  
A budgeting app for planning trips within a specific budget.
- Lets you plan by city, days, budget, and transport
- Uses a custom JSON dataset of Canadian cities with travel, lodging & food costs
- Generates a day-by-day itinerary and lets you experiment with “what if” scenarios

---


#### Population-Level Mask Use Simulation (AnyLogic, CMPT 394)
<sub><i>AnyLogic • Agent-Based Modelling • Epidemiology • Team Project (5 members)</i></sub>

This is one of the most meaningful and technically complex projects I’ve worked on. With a team of five, I helped build a full **agent-based epidemiological simulation** in AnyLogic to study how **population-level mask use changes the trajectory of a communicable disease outbreak**.

### What the model simulates
- A dynamic population placed randomly in a square environment  
- Realistic disease progression: **Susceptible → Exposed → Infectious → Recovered → Vaccinated**  
- Immunity waning + exogenous infections  
- Continuous-time simulation over a full year  
- COVID-like transmission parameters (based on literature review)

### Masking Mechanics
Masking is represented with adjustable probabilities:
- Only infectious person masked  
- Only susceptible person masked  
- Both masked (effects stack multiplicatively)

These directly influence the probability that an exposure becomes an infection.

### Network-Based Spread
Agents infect through a chosen AnyLogic network structure (team-configurable).  
This allows us to simulate different social structures and connectivity patterns.

###  Outputs & Analysis
Every run generates:
- Daily infection counts  
- Counts of each disease state  
- Number of exposures prevented by masks  
- Full CSV export for analysis  
- A live visualization of population and infection dynamics  

Across multiple runs:
- **2D histogram of incident infections**  
- **Infection-chain reconstruction** (including masking status of every infective–susceptible pair)

### Research Questions We Answer
- Is there a **critical masking level or mask effectiveness threshold** that changes outbreak behaviour?  
- What fraction of infections occur in masked vs unmasked individuals?  
- How does masking shift outbreak peaks, durations, and total infections?

### Why this project matters to me
It’s not just a simulation — it’s a blend of:
- software engineering  
- epidemiology  
- data analysis  
- teamwork  
- and real-world impact  

Working with AnyLogic and designing a fully parameterized, flexible model taught me a lot about systems thinking and collaborative development.

---


### Tech I use

**Languages:** Python, Java, C, JavaScript, HTML/CSS, Bash/Shell, SQL  
**Frameworks & Platforms:** Streamlit, Flask, FastAPI, Node.js, WordPress, JUnit  , Anylogic
**Tools & Libraries:** pandas, NumPy, Matplotlib, scikit-learn, BeautifulSoup, Requests, Jinja2, Git, GitHub, Docker, Linux/Unix, SQLite  

I’m always happy to learn something new if it helps solve a real problem.

---

### What I care about (beyond code)

- Writing **clear, honest READMEs** so anyone can get started without guessing  
- Building things that are **practical**, not just flashy  
- Collaborating and communicating like a real teammate, not just “someone who commits code”

---

### 📫 Let’s connect

- 💼 LinkedIn: [sk-sidratul](https://www.linkedin.com/in/sk-sidratul)  
- 🧑‍💻 GitHub: [@SidratEvan](https://github.com/SidratEvan)  
- 📧 Email: `lcz982@usask.ca`

If you’re a recruiter, engineer, or just someone who loves tinkering with ideas,  
**my DMs are always open.** Thanks for stopping by 
