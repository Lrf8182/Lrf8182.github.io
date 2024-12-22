---
permalink: /
title: "Software Engineering & AI Research"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am an undergraduate student at Shanghai University's School of Computer Engineering and Science, focusing on artificial intelligence and software engineering. My research interests span vehicle network security, meteorological applications, and AI system optimization. Currently, I work as an intern at OpenJobs AI, developing intelligent solutions for job search and recruitment.

Research Focus
======
My research combines theoretical foundations with practical applications across several domains:

Vehicle Network Security
Working with the Cybersecurity Lab Vehicle Communication System Modeling and Simulation Group, I contribute to developing advanced detection systems for vehicle network attacks. Our work includes designing and implementing the Sequence Mapping Block (SMB) with OneHot encoding, significantly improving model convergence in anomaly detection.

Meteorological Applications
At the East China Air Traffic Management Bureau, I research deep learning applications for meteorological forecasting and super-resolution. This work involves comparing and optimizing various state-of-the-art models, including RVRT and BasicVSR++, while incorporating optical flow techniques for enhanced accuracy.

Professional Experience
======
I actively bridge academic research with industry applications:

OpenJobs AI: Leading the development of Lingxi, a multilingual job search engine, and implementing intelligent resume optimization systems
Yum China: Working on enterprise-level RAG applications and exploring advanced CV models using Stable Diffusion

Publications
======
"MDHP-Net: Detecting Injection Attacks on In-vehicle Network using Multi-Dimensional Hawkes Process and Temporal Model." IEEE S&P 2025 (Under Review)
"HP-LSTM: Hawkes Process–LSTM-Based Detection of DDoS Attack for In-Vehicle Network." Future Internet 2024 

Technical Skills
======
Advanced proficiency in Python, C++, and distributed systems
Extensive experience with machine learning frameworks and large language models
Strong background in data processing and system optimization

For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

The repository includes [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/), the [growing wiki](https://github.com/academicpages/academicpages.github.io/wiki), and you can always [ask a question on GitHub](https://github.com/academicpages/academicpages.github.io/discussions). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
