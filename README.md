# Intelligent Agents

MSc Artificial Intelligence – e-Portfolio

* [Home](index.html)
* [Discussions](discussions.html)
* [Activities](activities.html)
* [Project & Deep Learning](project.html)
* [Reflections](reflections.html)
* [About](about.html)

---

## Module e-Portfolio Overview

Collecting my work, experiments and reflections for the *Intelligent Agents* module (Oct 2025 cohort).

This e-Portfolio brings together:

* My contributions to the three **collaborative discussions** (Agent-Based Systems, Agent Communication Languages, Deep Learning).
* **Seminar preparation** tasks where I worked through scenarios, designs and short coding exercises.
* **Design activities**, such as creating agent dialogues and parse trees.
* A final **reflective narrative** on what I learned about intelligent agents, multi-agent systems and deep learning – and how this connects to real-world problems in my own professional context.

The formal assessment for this e-Portfolio is **40% of the module mark**, with a total word limit of **2,500 words**:

* Up to **1,500 words** across the activity pages (discussions, designs, seminar work).
* A **1,000-word reflective section** that brings everything together and focuses on my learning journey and contribution to team work.

Screenshots of my posts, diagrams and code samples will be included where relevant and **do not count** towards the word limit.

---

## Collaborative Discussion 1 (Units 1–3)  
### Agent-Based Systems

Exploring where agent-based systems add real value.

This discussion focused on identifying a suitable real-world scenario for an agent-based system, justifying why agents were appropriate, and considering the challenges of designing and evaluating such a system.

### My chosen scenario

For my initial post, I focused on an **agent-based system for emergency medical response and ambulance coordination**, inspired by my work in prehospital care. The idea was to model:

* **Ambulance agents** – with beliefs about current location, availability and equipment; desires to reach patients quickly and safely; intentions based on assigned calls.
* **Hospital agents** – representing capacity, specialities (e.g. trauma, cardiac) and current load in emergency departments and ICUs.
* **Triage / dispatch agents** – responsible for matching incidents to the most appropriate ambulance and destination, considering time, severity and resources.
* **Environment** – including road networks, traffic, incident locations and constraints such as weather or large events.

This scenario was chosen because decisions about **where to send ambulances and which hospital to use** are dynamic, complex and involve many interacting entities. An agent-based approach can capture this interaction more realistically than a single centralised algorithm.

### Key points from my initial contribution

In my post, I argued that an **agent-based simulation** would allow us to:

* Experiment with different **dispatch strategies** (e.g. nearest ambulance vs. load balancing vs. speciality-based routing).
* Study **bottlenecks and emergent behaviour** (e.g. overcrowding at a single hospital, long waiting times in some regions).
* Evaluate the impact of **new policies**, such as reserving capacity for critical cases or prioritising certain incident types.

I also highlighted potential challenges:

* Designing believable **agent behaviours and rules** that represent real clinical policies and constraints.
* Obtaining **realistic data** for calibration (travel times, hospital capacities, typical incident patterns).
* Choosing suitable **evaluation metrics**, such as average response time, number of diverted patients or ICU admission delays.

### Insights from peers

In the discussion, my peers chose very different domains, such as:

* **Smart traffic lights and autonomous vehicles**.
* **E-commerce recommender systems with negotiating buyer/seller agents**.
* **Energy management in smart grids**.

From their posts and our exchanges, I took away several key insights:

* Agent-based systems are powerful whenever the problem involves **many semi-autonomous entities** that interact locally but produce **global patterns**.
* It is important to decide **which behaviours are handled by individual agents** and which are better treated as **global constraints or system rules**.
* Visualising simulations (e.g. maps, timelines, heatmaps) is crucial for interpreting emergent behaviour and explaining results to non-technical stakeholders.

### What I learned (reflection)

This first discussion helped me to:

* Connect the **abstract definitions of agents, environments and architectures** from the lecture to a problem I care about in real life.
* Recognise that agent-based systems are not only about “intelligent” behaviour, but also about **modelling interactions and emergence**.
* Appreciate how **different design choices** (e.g. how rational agents are, how much information they share, how they handle uncertainty) can radically change the outcome of a simulation.

In my later activities (e.g. agent communication languages and deep learning), I will continue to return to this emergency-response scenario as a **running example** for linking theory to practice.

[↑ Back to top](#intelligent-agents)

---

## Structure of this e-Portfolio

This page acts as the **home and overview** for the Intelligent Agents e-Portfolio.

Each main activity has its own section or page, which will be linked from the navigation and from here as the module progresses:

### Discussions

* **Collaborative Discussion 1: Agent-Based Systems (Units 1–3)**  
  Summary of my initial post, peer responses and final reflection on using agent-based modelling in emergency response.
* **Collaborative Discussion 2: Agent Communication Languages (Units 5–7)**  
  Focused on KQML/KIF, designing communication protocols between agents and analysing strengths and weaknesses of agent communication languages.
* **Collaborative Discussion 3: Deep Learning (Units 9–11)**  
  Explores how deep learning fits into the broader Intelligent Agents landscape, with examples and critical reflection on real-world use.

### Activities & Seminar Preparation

* **Unit 1, 2, 4, 6, 8, 10 & 12 Seminar Preparation Tasks**  
  Short written answers, small designs and code fragments in Python (where applicable), demonstrating how I prepared for each seminar.
* **Creating Agent Dialogues (Unit 6)**  
  Design of simple conversations using KQML performatives and KIF expressions, plus reflections on how easy or difficult it was to represent knowledge and intentions clearly.
* **Creating Parse Trees (Unit 8)**  
  Constructing parse trees for agent communication examples and reflecting on how syntax and structure influence meaning.

### Project & Deep Learning

* **Deep Learning in Action (Unit 10)**  
  A short practical piece or case study showing how a deep learning approach can support or extend an intelligent agent system.
* A brief summary of how **agent-based thinking** and **deep learning** can complement each other in complex, data-rich environments.

### Reflections

* **Final 1,000-word reflection**  
  Organised around the “What? – So What? – Now What?” structure (Rolfe et al., 2001), focusing on:
  * My role and behaviour as part of a **development team**.
  * How I contributed to the **group project in Unit 6**.
  * What I learned about intelligent agents, collaboration and professional practice.
  * How I plan to apply these skills and concepts in future modules and in my work.

This reflection will integrate evidence from my discussions, activities, and project work, supported by relevant literature and module readings where appropriate.

---

## Reflection Framework & Learning Outcomes

Throughout the module, I will use a simple reflective structure:

* **What?** – Briefly describe the activity, project or incident (for example, a discussion, a design task, or the group work in Unit 6).
* **So What?** – Analyse what happened, how I felt, what worked well or not, and how this relates to theory, prior experience and feedback.
* **Now What?** – Identify concrete changes to my practice: skills I need to develop, strategies I will use in future, and how this shapes my longer-term goals.

By the end of the module, I expect to be able to:

* Explain the **motivations for using intelligent agents and agent-based computing** in specific domains.
* Describe and compare the **main agent models and architectures**, linking them to core AI concepts such as rationality, planning and learning.
* Demonstrate that I can **develop, deploy and evaluate intelligent systems** (including agent-based and deep learning components) to address real-world problems.
* Engage with **contemporary research issues** in intelligent agent systems, including communication, coordination, ethics and robustness.

---

### Quick navigation

* [Collaborative Discussion 1 – Agent-Based Systems](#collaborative-discussion-1-units-13)
* Discussions (Units 5–7, 9–11) – *to be completed during the module*
* Activities & Seminar Preparation – *in progress*
* Project & Deep Learning – *in progress*
* Final Reflection – *to be written in Unit 12*

---

Intelligent Agents e-Portfolio · Naeema Abdalla Ahmed Alnaqbi · 2025
