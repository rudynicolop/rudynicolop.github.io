---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* M.S. in Computer Science, ETH Zurich, 2025 (expected)
* B.A. in Computer Science and Physics, Cornell University College of Arts and Sciences, 2020, _magna cum laude_

Work experience
======
* Jan 2021 - Aug 2023: Research Programmer
  * Poulet4 Project.
  * Mentors: Nate Foster (Cornell), Andrew Appel (Princeton)
  * Implementing in Coq the p4cub IR for a verified p4 compiler, including type soundness & semantics-preserving transformations on the IR.
  * Writing the type system in Coq for the p4light IR, including type soundness proofs.

* Jan 2019 - Aug 2020 : Undergrad Research Assistant
  * Petr4 Project.
  * Mentors: Nate Foster (Cornell)
  * Rigorously defined the static semantics of the network programming language p4 in terms of an operational semantics.
  * Contributed to OCaml-written type-checker.

<!--

Skills
======
* Skill 1
* Skill 2
  * Sub-skill 2.1
  * Sub-skill 2.2
  * Sub-skill 2.3
* Skill 3

-->

Publications
======
<ul>
	<li>
		<b><a href="https://dl.acm.org/doi/abs/10.1145/3573105.3575670">P4Cub: A Little Language for Big Routers</a></b>
		<br /> <b>Rudy Peterson</b>, Eric Hayden Campbell, John Chen, Natalie Isak, Calvin Shyu, Ryan Doenges, Parisa Ataei, and Nate Foster <br />
		<b><a href="https://www.youtube.com/watch?v=GIzthatfKWk&list=PLyrlk8Xaylp6EB6XceHKB-UKBfmYYJAbH&index=10>talk</a></b>
		<b>CPP 2023</b>
	
	</li>

	<li>
		<b><a href="https://arxiv.org/abs/2011.05948">Petr4: Formal Foundations for P4 Data Planes</a></b>
		<br /> Ryan Doenges, Mina Tahmasbi Arashloo, Santiago Bautista, Alexander Chang, Newton Ni, Samwise Parkinson, <b>Rudy Peterson</b>, Alaia Solko-Breslin, Amanda Xu, Nate Foster <br />
		<b>POPL 2020</b>
	</li>
</ul>


<!--

Talks
======
<ul>

	<li></li>

</ul>

-->

Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
