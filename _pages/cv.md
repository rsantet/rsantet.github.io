---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Experience
======
* CEA research enginner @ [CEA](https://www.cea.fr/) since December 2025.
* Post-doctoral researcher @ [CEA Cadarache](https://cadarache.cea.fr/cad/Pages/Accueil.aspx), February 2025 - November 2025, under the supervision of [Emeric Bourasseau](https://scholar.google.com/citations?user=M4Tc3AMAAAAJ&hl=fr) and [Luca Messina](https://scholar.google.com/citations?hl=fr&user=_q0x3tsAAAAJ).
  AI potentials for the mixed oxide nuclear fuel. Languages: Python, Bash; Software: ABINIT, VASP, LAMMPS, FitSNAP, Dakota.
* Recognized student @ [Department of Statistics](https://www.stats.ox.ac.uk/) (Oxford University), Michaelmas term (September - December 2023), under the supervision of [George Deligiannidis](https://www.stats.ox.ac.uk/~deligian/).
  Computing free energy differences using diffusion model techniques. Relevant topics include Jarzynski-Crooks' equality, annealed importance sampling, diffusion models, Schrödinger bridges. Languages: Python.
* PhD student @ [CERMICS](https://cermics-lab.enpc.fr/) (École des Ponts) and [MATHERIALS](https://team.inria.fr/matherials/) (INRIA Paris), October 2021 - September 2024, under the supervision of [Tony Lelièvre](https://cermics.enpc.fr/~lelievre/) and [Gabriel Stoltz](https://cermics-lab.enpc.fr/gabriel-stoltz/).
* Research Intern @ [Green Shield Technology](https://greenshield.fr/), April - August 2021, under the supervision of [Renaud Dessalles](https://dessalles.github.io/).
  Mathematical epidemiology applied to the spread of beetroot diseases. Relevant topics include mathematical epidemiology, scientific computing, simulation. Languages: Python.
* Data Scientist & Customer Success officer @ [FieldBox.ai](https://www.fieldbox.ai/), January - July 2020.
  Machine learning challenges and IT support for customers (front-end and back-end). Relevant topics include machine learning, IT systems, front-end and back-end development. Languages: Python, Bash, JavaScript, Erlang.
* Research Intern @ [CEA](https://www-dam.cea.fr/), June - November 2019, under the supervision of [Jean-Bernard Maillet](https://scholar.google.fr/citations?user=KaL3RUIAAAAJ&hl=fr).
  Applying mathematics to molecular dynamics. Relevant topics include statistical physics, machine learning, scientific computing. Languages: C++, Python; Software: LAMMPS, PLUMED2.

Education
======
* **Sorbonne Université**, Master's Degree, 2020 - 2021. *Master de la Modélisation* (Master of Modelisation), specializing in *Analyse Numérique et Équations aux Dérivées Partielles* (Numerical Analysis and Partial Differential Equations). Relevant topics include functional analysis, stochastic processes, numerical analysis, hyperbolic equations, multiscale systems, elliptic equations, Lorentzian differential geometry. Languages: Python, Julia.
* **École Nationale des Ponts et Chaussées**, Engineering Degree, 2017 - 2021. Specialization in *Modélisation, Analyse, Simulation* (Modelisation, Analysis, Simulation). Relevant topics include functional analysis, stochastic processes, Fourier analysis, numerical analysis, scientific computing, probability, statistics, optimal control, operational research, artificial intelligence, quantum mechanics, economics. Languages: C++, Python, Julia, Git, LaTeX.

Distinctions
======
* [Pasquet's Prize](https://www.fondationdesponts.fr/prix-pasquet/) - Valedictorian of École Nationale des Ponts et Chaussées (2022)
* Bourse d'Excellence via the Chaire Saint-Gobain - École des Ponts ParisTech

Community involvement
======
* Helping pupils and students with their homework with [Mosaïc](https://mosaic-a-montreuil.fr/), 2023 - 2024.
* PhD representative of the [MSTIC doctoral school](https://www.paris-est-sup.fr/ecoles-doctorales/ecole-doctorale-mathematiques-et-stic-mstic/l-ed-mstic/), 2023. Administrative meetings.
* PhD representative of the [CERMICS laboratory](https://cermics-lab.enpc.fr/), 2022 - 2023. 3-day seminar organization, administrative meetings.
* Member of the [Running Vincennes Association](https://www.running-vincennes.fr/), 2021 - 2024.
* Member of a sustainable development association [Dévelop'Ponts](http://developponts.enpc.org/), 2018 - 2019. Sustainable development projects, distribution of veggie baskets to students and staff, website update. Languages: PHP, HTML, Git.
* Member of the ENPC IT club [KIClubInfo](https://clubinfo.enpc.org/), 2018 - 2019. In charge of the club's finances. Organization of [LaTeX trainings](https://clubinfo.enpc.org/formations.php) for ENPC students. Languages: LaTeX, Git.
* Co-founder of the ENPC chess club, Pions & Chaussées, 2018 - 2019. Organization of chess tournaments and introduction to the game for ENPC students. Co-founder of the [ENPC Lichess team](https://lichess.org/team/pions-et-chaussees).

Publications
======
<ul>
{% for post in site.publications reversed %}
  <li>{{ post.title }}{% if post.venue %}, <i>{{ post.venue }}</i>{% endif %}{% if post.date %} ({{ post.date | date: "%Y" }}){% endif %}</li>
{% endfor %}
</ul>

Talks & posters
======
<ul>
{% for post in site.talks reversed %}
  <li>{{ post.title }} - {{ post.venue }}{% if post.date %} ({{ post.date | date: "%B %Y" }}){% endif %}</li>
{% endfor %}
</ul>

Teaching
======
<ul>
{% for post in site.teaching reversed %}
  <li>{{ post.title }}{% if post.venue %}, {{ post.venue }}{% endif %}{% if post.date %} ({{ post.date | date: "%Y" }}){% endif %}</li>
{% endfor %}
</ul>
