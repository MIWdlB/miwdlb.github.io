---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Glasgow, Scotland · [michael.williams.20@ucl.ac.uk](mailto:michael.williams.20@ucl.ac.uk)

{% comment %}
  The PDF below is a static copy and does not update with this page.
  When you edit the CV content here, also replace files/Michael_Williams_de_la_Bastida_CV.pdf.
{% endcomment %}
<a href="{{ base_path }}/files/Michael_Williams_de_la_Bastida_CV.pdf" class="btn btn--primary" download><i class="fas fa-fw fa-download"></i> Download CV (PDF)</a>

Education
======
* PhD Chemistry
  * Resource Reduction for Hybrid Quantum-HPC Simulation of Chemistry
  * University College London, London, in progress (completion 2026)
* MRes Quantum Technologies (Distinction)
  * Embedded Quantum Algorithms for Chemical Structure
  * University College London, London, 2021
* MPhys Theoretical Physics (First Class)
  * Examining the Orthogonality Catastrophe with the Kernel Polynomial Method
  * University of St Andrews, 2019
* Airline Transport Pilot's License
  * Flight Training Europe, Jerez, Spain, 2013
  * 93% average in 14 ATPL theory exams
  * First attempt pass in Commercial Pilot's License and Instrument Rating
  * Jet Orientation Course with Multi-crew Co-ordination

Work experience
======
* ProEd Et Al - Lecturer
  * July 2023 - Present
  * Introduction to Quantum Computing from Computer Science: 6 hour in-person course for university entrants.
  * Physical Sciences and Programming: 3 day course covering study and careers in physical and information sciences for students in late secondary education.
  * Introduction to Computer Science: 6 hour online course covering classical information theory, physical computing and computational science for students in secondary education.

* Microsoft - Automation Software Engineer
  * September 2019 - September 2020, London
  * Developed cloud automation tools for deployment and life-cycle management of telecoms virtual machines in Python and Rust.
  * Implemented testing and data-validation models for cloud infrastructure.
  * Provided installation engineers with CLI tools for headless debugging, resulting in reduced commissioning time.

* Max Planck Institute for Gravitational Physics - Research Intern
  * Summer 2017
  * Duties included: Develop an undergraduate teaching laboratory on the topic of interferometry.
  * Supervisor: Dr. Michael Tröbs

* University of St. Andrews - Research Intern
  * Spring 2017
  * Duties included: Qualitative Research on misconceptions held by students regarding quantum mechanics.
  * Supervisor: Dr. Antje Kohnle

Service
======
* Reviewer, Journal of Open Source Software (1 review in 2026)
  * Quantum Computing, Computational Chemistry, Python, Rust, R

Conferences
======

Talks
------
* "Optimised Fermion-Qubit Encodings", Scientific Computing in Rust 2026, Online, 9 July 2026 ([video](https://www.youtube.com/watch?v=7HQ5W29QhYI))
* "Optimised Fermion-Qubit Encodings for quantum simulation with reduced circuit depth", QUANTUMatter 2026 (6th Quantum Matter International Conference & Expo), Barcelona, Spain, April 2026

Tutorials
------
* "Accelerated Quantum Supercomputing: A Hands-On Tutorial on Quantum-Classical Hybrid Workflows Executed on QPUs and GPUs", SC26, Chicago, USA, 15 November 2026

Posters
------
* "Optimised Fermion-Qubit Encodings", QCTiP 2026, Oxford, England ([poster PDF]({{ base_path }}/files/QCTiP_2026_Poster.pdf))
* "Quantum Multicast Communication for the Quantum Internet", Careers in Quantum 2022, Bristol, England, June 2022 ([poster PDF]({{ base_path }}/files/Careers_in_Quantum_2022_Poster.pdf))

Skills
======
* Research: Quantum algorithms, simulation of chemistry, resource reduction of quantum algorithms, education and dissemination
* Programming languages: Python, Rust, R
* Cloud technologies: Terraform, Ansible
* DevOps & version control: Git, Jujutsu, GitHub Actions

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
