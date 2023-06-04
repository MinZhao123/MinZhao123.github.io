---
permalink: /
title: "academicpages is a ready-to-fork GitHub Pages template for academic personal websites"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I'm a Phd student from [Beijing Normal University]. My superwisor is Professor Rong Yuan.

I am very fortunate to be advised by [Prof. XXX](https://www.XXX.com/) of XXX Lab from [School of Computer Science](https://cs.pku.edu.cn/), Peking University. I was advised by [Prof. XX](https://XXX.pku.edu.cn/) from [School of Computer Science](https://cs.pku.edu.cn/), Peking University.

You can find my CV here: [XX's Curriculum Vitae](../assets/Curriculum_Vitae.pdf).

[Email](mailto:minzhao@mail.bnu.edu.cn) / [Github](https://github.com/MinZhao123) 




My name is  [academicpages template](https://github.com/academicpages/academicpages.github.io) and hosted on GitHub pages. [GitHub pages](https://pages.github.com) is a free service in which websites are built and hosted from code and data stored in a GitHub repository, automatically updating when a new commit is made to the respository. This template was forked from the [Minimal Mistakes Jekyll Theme](https://mmistakes.github.io/minimal-mistakes/) created by Michael Rose, and then extended to support the kinds of content that academics have: publications, talks, teaching, a portfolio, blog posts, and a dynamically-generated CV. You can fork [this repository](https://github.com/academicpages/academicpages.github.io) right now, modify the configuration and markdown files, add your own PDFs and other content, and have your own site for free, with no ads! An older version of this template powers my own personal website at [stuartgeiger.com](http://stuartgeiger.com), which uses [this Github repository](https://github.com/staeiou/staeiou.github.io).

Research Interests 
======
* Partial differential equations and dynamic systems

  Reaction-diffusion equations, Nonlocal problems, Traveling waves, Spreading speed
	  
* Biomathematics

  Prey-predator system, Nonlinear differential equation, Epidemic model
	  
* Stochastic theory and process

  Brownian motion, Ergodic, Levy process



Publications
======
1. **M. Zhao**, R. Yuan, Z. Ma, X. Zhao, Spreading speeds for the predator-prey system with nonlocal dispersal, *Journal of Differential Equations*, 316 (2022), 552--598.[PDF](../assets/Curriculum_Vitae.pdf).
2. **M. Zhao**, Z. Ma, R. Yuan, The spreading speed and the existence of planar waves for a class of predator-prey system with nonlocal diffusion, *Taiwanese Journal of Mathematics*, 26(2) (2022), 381--410. [PDF](../assets/Curriculum_Vitae.pdf).
3. X. Wang, **M. Zhao**, X. Wang, S. Li, N. Cao, H. Liu, The Application of Dynamic Models to the Exploration of beta1-AR Overactivation as a Cause of Heart Failure, *Computational and Mathematical Methods in Medicine*, 2018 (2018) 1613290.[PDF](../assets/Curriculum_Vitae.pdf).
4. Y. Cheng, F. Zhang, **M. Zhao**, A stochastic model of HIV infection incorporating combined therapy of HAART driven by L\'evy jumps, *Advances in Difference Equations*, 321 (2019), 1--17.
5. **M. Zhao**, R. Yuan, Persistence of solutions in a nonlocal predator-prey system with a shifting habitat, arXiv:2306.00649. 
6. **M. Zhao**, R. Yuan, Existence and Stability of Random Transition Waves for Nonautonomous Fisher-KPP Equations with Nonlocal Diffusion, arXiv:2305.19762. 
7. Q. Griette, P. Magal, **M. Zhao**, Traveling waves with continuous profile for hyperbolic Keller-Segel equation, arXiv:2204.06920.
8. H. Li, **M. Zhao**, R. Yuan, Traveling Wave in a Ratio-dependent Holling-Tanner System with Nonlocal Diffusion and Strong Allee Effect, arXiv:2306.00666.
9. H. Li, **M. Zhao**, R. Yuan, Traveling Waves of Modified Leslie-Gower Predator-prey Systems,  arXiv:2306.00701.
10. H. Li, **M. Zhao**, R. Yuan, A sufficient condition on successful invasion by the predator, arXiv:2306.00713.



Scientific Education
======
09/2019-07/2023: PhD Candidate, Basic mathematics 
	         Prof. Rong Yuan, Beijing Normal University, China  
09/2021--09/2022: Joint training doctoral student, Applied mathematics
	          Prof. Pierre Magal, University of Bordeaux, France 
	          Prof. Quentin Griette, Universit\'e Le Havre Normandie, France 
09/2016--06/2019: Master degree, Mathematics
	          Prof. Xiaoyun Wang, Taiyuan University of Technology, China	                           
09/2011--06/2015: Bachelor degree, Mathematics and Applied Mathematics
                  Shanxi Datong University, China

%-----------------------------------
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
