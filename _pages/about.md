---
permalink: /
title: About Me
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

This is the front page of a website that is powered by the [academicpages template]Howdy!

I'm a first year PhD student in the Computer Science Department of UT Austin. I'm fortunate to be advised by Prof. Inderjit Dhillon and co-advised by Prof. Sujay Sanghavi. My main research interest is the design of efficient and provable machine learning and deep learning algorithms. In general, I like solving mathematical problems based on linear algebra, probability & statistics, optimization, etc. which are ubiquitous in machine learning.

Previously, I was a dual degree (combined bachelor's and master's degree) student in the Department of Electrical Engineering, Indian Institute of Technology (IIT) Bombay. At IIT Bombay, I've worked under the guidance of Prof. Subhasis Chaudhuri on some probabilistically provable theoretical aspects of neural networks and algorithmic aspects of large-scale optimization for my final thesis. I was awarded the Undergraduate Research Award (URA-03) for exceptional work in my final thesis.

You can check out my CV [here]({{ site.url }}/assets/CV_Rudra.pdf).

Publications & Competitions

"On the Separability of Classes with the Cross-Entropy Loss Function" - Rudrajit Das and Subhasis Chaudhuri.

Pre-print. Download paper here.

"Extremal Eigenvalue Analysis of the Hessian and a Learning Rate Choice for Stochastic Gradient Descent" - Rudrajit Das and Subhasis Chaudhuri.

Pre-print. Manuscript available on request.

"On the Convergence of a Biased Version of Stochastic Gradient Descent" - Rudrajit Das, Jiong Zhang and Inderjit Dhillon.

Accepted for poster presentation in "Beyond First Order Methods in ML" workshop in NeurIPS 2019.

"Nonlinear Blind Compressed Sensing under Signal-Dependent Noise" - Rudrajit Das and Ajit Rajwade.

Accepted for presentation in IEEE International Conference on Image Processing (ICIP) 2019. Download paper here.

"Sparse Kernel PCA for Outlier Detection" - Rudrajit Das, Aditya Golatkar and Suyash Awate.

Accepted for oral presentation in IEEE International Conference on Machine Learning and Applications (ICMLA) 2018. Download paper here.

iFood Challenge, FGVC Workshop, CVPR 2018 - Parth Kothari^, Arka Sadhu^, Aditya Golatkar^, Rudrajit Das^ (^ denotes equal contribution).

Finished $2^{nd}$ in the public leaderboard and $3^{rd}$ in the private leaderboard (Team name : Invincibles). Leaderboard Link. Invited to present our method at CVPR 2018 (slides can be found here).

"Some Probabilistically Provable Theoretical Aspects of Neural Networks and Algorithmic Aspects of Large-Scale Optimization" - Bachelor's & Master's Thesis. Awarded the Undergraduate Research Award (URA-03) for exceptional work in thesis. Download here.

Internships

Institute for Biomechanics, ETH Zürich, Switzerland (May '17 - July '17)
Guide : Dr. Patrik Christen and Prof. Dr. Ralph Müller, D-HEST

Proposed a stable linear model (with closed form solution) and a fuzzy boolean network for bone re-modelling.
Also developed an automated 2D-3D image registration framework for histology images from scratch. Devised an efficient sampling strategy to obtain the 2D projection of the 3D image across any plane and a good cost function to deal with the highly non-convex nature of the problem.
Altisource Business Solutions Private Limited, Bengaluru, India (May '16 - July '16)

Developed a notification system using Pagerduty, a popular incident management software, and worked on the UI of the company’s monitoring dashboard built using JBoss Dashbuilder

A data-driven personal website
======
Like many other Jekyll-based GitHub Pages templates, academicpages makes you separate the website's content from its form. The content & metadata of your website are in structured markdown files, while various other files constitute the theme, specifying how to transform that content & metadata into HTML pages. You keep these various markdown (.md), YAML (.yml), HTML, and CSS files in a public GitHub repository. Each time you commit and push an update to the repository, the [GitHub pages](https://pages.github.com/) service creates static HTML pages based on these files, which are hosted on GitHub's servers free of charge.

Many of the features of dynamic content management systems (like Wordpress) can be achieved in this fashion, using a fraction of the computational resources and with far less vulnerability to hacking and DDoSing. You can also modify the theme to your heart's content without touching the content of your site. If you get to a point where you've broken something in Jekyll/HTML/CSS beyond repair, your markdown files describing your talks, publications, etc. are safe. You can rollback the changes or even delete the repository and start over -- just be sure to save the markdown files! Finally, you can also write scripts that process the structured data on the site, such as [this one](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb) that analyzes metadata in pages about talks to display [a map of every location you've given a talk](https://academicpages.github.io/talkmap.html).

Getting started
======
1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Fork [this repository](https://github.com/academicpages/academicpages.github.io) by clicking the "fork" button in the top right. 
1. Go to the repository's settings (rightmost item in the tabs that start with "Code", should be below "Unwatch"). Rename the repository "[your GitHub username].github.io", which will also be your website's URL.
1. Set site-wide configuration and create content & metadata (see below -- also see [this set of diffs](http://archive.is/3TPas) showing what files were changed to set up [an example site](https://getorg-testacct.github.io) for a user with the username "getorg-testacct")
1. Upload any files (like PDFs, .zip files, etc.) to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.  
1. Check status by going to the repository settings, in the "GitHub pages" section

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

I have also created [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the academicpages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring academicpages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
