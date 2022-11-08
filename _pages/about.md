---
permalink: /
title: "About me"
excerpt: "Biography"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I gained my bachelor degree in mechanical engineering in 2010 and my first M.Sc. degree in mechanical engineering with specialization of logistics, in Tongji-University in 2013. I work as junior project manager in pilot hall at SAIC Volkswagen between 2013 and 2015.  Since 2015, I have been studying technology management in University of Stuttgart and gained my second M.Sc. degree. From 2019 to 2022, I worked as researcher in  IAT of University of Stuttgart together in the team Digital Engineering at Fraunhofer IAO.

# Research

Research interests are Modeling and Simulation, Model-based Systems Engineering, AI for Science, Machine Learning, Natural Language Processing, etc.

### ModelSolver (2022)

*ModelSolver* is a hobby project due to personal interests. It solves system of ODEs derived from bond graph. The main goal is to learn and explore the interdisciplinary simulation (or multi-physics simulation) with MBSE approach.

![model-solver](model-solver.png)

Both mechanical system modeling, bond graph transformation and numerical solver (e.g. RK-Fehlberg order4/order5) are implemented in Python as playground for purpose of a proof of concept. Further development and realization could be conducted with Python and C++ mixed.

### ODEqSolver (2022)

*ODEqSolver* is a hobby project due to personal interests. It solves system of ODEs in list of string in Python. The main goal is to have a insight in simulation tools' backbone. Deepdived are methods of explicit and implicit solver, rootfinding and linear system. Simple demos are developed with Python and Rust. Further research towards its application in established models, and PDE solver.

### QU4LITY Project (2020-2022)

*Qu4lity*  (EU H2020 825030) is the biggest European project dedicated to Autonomous Qu4lity (AQ) and Zero Defect Manufacturing (ZDM) in the Industry 4.0, co-funded by the Horizon 2020. The pilot project with Airbus origins from the concept of semantic integration in industrial system design.

Tools involved are *Protege* for application ontology development, *Metagraph and KARMA language* with *GOPPRRE* for architecture definition and system integration, *DES* (discrete event simulation) tool for design verification, trade dashboard developed using *Vue, Vuetify and Apache Echarts* for integrated visualization as frontend, *Neo4j server* and local *SQLite* as database, *docker* for frond- and backend containerization, *Google Cloud Platform* and *Azure AWS* for deployment, etc.

![asdf](dashboard.png)

The DES tool is developed with Python based on open source discrete event simulation engine *SimPy*. DES models are object-oriented designed. Models are instantiated according to design concept models as input, then processed and simulated, aiming at a automatic  generation of design concepts trade-off to support decision.

![des](des.png)

**Video Link**: [Youtube - Industrial Co-Design at Airbus - Results from EU project QU4LITY](https://www.youtube.com/watch?v=kl_Kg-8DOSA)



### AI feasibility for Offer Analysis

...



# Pubulications

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

# Thesis

- Master thesis: Development of a method for company-specific advancement of digital engineering based on AI-functionalities at the example of a voice-controlled 3D-CAD application
- Student research project: Influences of Industry 4.0 on product development
- Master thesis: ...

# Publications

- Hu, X., Lu, J., Zheng, X., Arista, R., Sorvari, J., Lentes, J., Ubis, F. & Kiritsis, D. (2022).  Semantic Modeling Supporting Discrete Event Simulation for Aircraft Assembly Process. <i>International Symposium on Knowledge and Systems Sciences </i> (pp. 83-98). Springer, Singapore
- Hu, X., Arista, R., Lentes, J., Sorvari, J., Lu, Jinzhi, Zheng, X., Sorvari, J., Ubis, F. & Kiritsis, D. (2022). Ontology-centric industrial requirements validation for aircraft assembly system design. <i>IFAC-PapersOnLine</i>, in press
- Hu, X., Arista, R., Zheng, X., Lentes, J., Sorvari, J., Lu, J., Ubis, F. & Kiritsis, D. (2022). Ontology-based system to support industrial system design for aircraft assembly. <i>IFAC-PapersOnLine, 55(2)</i>, 175-180.
- Zheng, X., Lu, J., Arista, R., Hu, X., Lentes, J., Ubis, F., Sorvari, J. & Kiritsis, D. (2020). Development of an application ontology for knowledge management to support aircraft assembly system design. *CEUR Workshop Proceeding* ISSN, 1613, 0073.
- Fang, D. & Hu, X. (2014). Architecture of a Knowledge-Based Education System for Logistics. *In Frontier and Future Development of Information Technology in Medicine and Education* (pp. 2683-2692). Springer, Dordrecht.
- Zheng, X., Hu, X., Arista, R., Lu, J., Sorvari, J., Lentes, J., & Ubis, F. (2022). A semantic-driven tradespace framework to accelerate aircraft manufacturing system design. (unpublished)

