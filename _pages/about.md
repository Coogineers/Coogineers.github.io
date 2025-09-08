---
permalink: /
title: "Automated Oil-Fill System for MWD Pulser Assembly"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

In Measurement While Drilling (MWD) systems, dielectric oil is used to ﬁll an internal chamber within a pulser to protect sensitive electronics and balance pressure across seals during downhole operations. At KLX Energy Services, this process is currently performed manually. A technician cycles pressure several times to eliminate residual bubbles using an MWD tool assembly. Finally, they install an oil ﬁll plug to seal the chamber. While eﬀective, the process is highly dependent on the operator, time consuming and prone to inconsistencies. Any trapped air can compromise tool reliability leading to shortening lifespan in ﬁeld operations. 

Our project aims to design and build an automated system for the oil-ﬁlling process that integrates with the company’s existing vacuum-ﬁll infrastructure to perform this process more consistently and eﬃciently. Using a programmable articulating arm and an integrated control system, the device will replicate the manual procedure by following a programmed sequence, including drawing vacuum, controlled pressurization, and reorientation of 30lbs pulser assembly to help trapped air escape.  The automation process must not only replicate technician steps but also reduce cycle time while improving repeatability. 

 You can fork [this template](https://github.com/academicpages/academicpages.github.io) right now, modify the configuration and Markdown files, add your own PDFs and other content, and have your own site for free, with no ads!

A The technical design effort wil include:
======

Kinematic and motion simulations to achieve precise positioning targeting cycle times of 15 minutes or less in 95% of cases. 

Integration of pressure sensors for real-time veriﬁcation of correct ﬁll cycles ensuring pressure stability of less than 0.1 psi/s drift for 60 seconds. 

Development of control logic to manage vacuum draw and compressed air pressurization steps reaching 30 psi with a tolerance of +/- 2 psi. 

Finite Element Analysis (FEA) to ensure structural integrity and feasibility under repeated use, validating a safety factor of 2.  Quantifying repeated cycling/ creep analysis of motor actuation lifting and lowering 30 lbs pulser assembly. 

Deﬁne success of trapped air removal via pressure measurements and validation test of at least 10 consecutive cycles without drift or failure. 

  

Deliverables will include: 

User/ Operator/ Troubleshooting guides and manuals 

Schematic of control logic with programmed sequences of vacuum and pressurization. 

Report of structural and fatigue analysis, including verification of safety factor >2 and results of static loading testing at 1.5 times expected load. 

Prototype fabrication and experimental validation using actual MWD pulsers in sponsor’s facility. 

CAD modeling of the articulation arm. 

Test reports documenting performance against key metrics: cycle time, stable pressure hold, pressurization target, overshoot and uninterrupted cycles completed successfully.  

For those users that need more advanced functionality, the template also supports the following popular tools:
- [MathJax](https://www.mathjax.org/) for mathematical equations
- [Mermaid](https://mermaid.js.org/) for diagraming
- [Plotly](https://plotly.com/javascript/) for plotting

Header
======


Header
------


Header
------
For site content, there is one Markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a Markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each Markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

The repository includes [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual Markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the Markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and Markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a Markdown file for a talk
![Editing a Markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/), the [growing wiki](https://github.com/academicpages/academicpages.github.io/wiki), and you can always [ask a question on GitHub](https://github.com/academicpages/academicpages.github.io/discussions). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
