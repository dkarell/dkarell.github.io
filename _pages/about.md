---
permalink: /
title: "Daniel Karell"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am an Assistant Professor of Sociology at Yale University.

## AI for Social Science Research Methods

I teach a course on incorporating generative AI into social science research methods. 

## Research

### Generative AI, society, and social science research

“Integrating Generative Artificial Intelligence into Social Science Research: Measurement, Prompting, and Simulation”, with Thomas Davidson. 2025. *Sociological Methods and Research*. [link](https://journals.sagepub.com/doi/10.1177/00491241251339184)

“Artificial Intelligence Summaries of Historical Events Improve Knowledge Compared to Human-Written Summaries”, with Matthew Shu, Keitaro Okura, and Thomas Davidson. [preprint](https://osf.io/preprints/socarxiv/3gsqw)

“Synthetic Duality: A Framework for Analyzing Natural Language Generation's Representation of Social Reality”, with Jeffrey Sachs and Ryan Barrett. 2024. *Poetics* 108: 101966. [link](https://www.sciencedirect.com/science/article/pii/S0304422X24001049?via%3Dihub)

“Language Models in Sociological Research: An Application to Classifying Large Administrative Data and Measuring Religiosity”, with Jeffrey Jensen, Cole Tanigawa-Lau, Mai Oudah, Nizar Habash, and Dhia Fani. 2022. *Sociological Methodology* 52: 30-52. [link](https://doi.org/10.1177/00811750211053370)

### Social media and social movements

“Online Speech and Communal Conflict: Evidence from India”, with Sebastian Schutte and Ryan Barrett. 2025. *PNAS Nexus* 4: pgaf149. [link](https://academic.oup.com/pnasnexus/advance-article/doi/10.1093/pnasnexus/pgaf149/8129733?utm_source=advanceaccess&utm_campaign=pnasnexus&utm_medium=email)

“Perceived Racial Threats Increase Demand for Conservative Media: Evidence from Black Lives Matter Protests and Fox News Ratings”, with Jeffrey L. Jensen. [preprint](https://osf.io/preprints/socarxiv/bmupw/)

“‘Born for a Storm’: Hard-Right Social Media and Civil Unrest”, with Andrew Linke, Edward Holland, and Edward Hendrickson. 2023. *American Sociological Review* 88: 322-349. [link](https://journals.sagepub.com/doi/10.1177/00031224231156190) 

“How Symbols Influence Social Media Discourse: An Embedding Regression Analysis of Trump’s Return to Twitter”, with Jeffrey Sachs. 2023. *Socius* 9. [link](https://journals.sagepub.com/doi/10.1177/23780231231212108) 

“Analyzing Text and Images in Digital Communication: The Case of Securitization in American White Supremacist Online Discourse”, with Michael Freedman and Noam Gidron. 2023. *Socius* 9. [link](https://journals.sagepub.com/doi/10.1177/23780231231161049)

“Small Town Propaganda: The Content and Emotions of Politicized Digital Local News in the United States”, with Anjali Agrawal. 2021. *Poetics* 92: 101641. [link](https://doi.org/10.1016/j.poetic.2021.101641)

“The TikTok Self: Music, Signaling, and Identity on Social Media”, with Jeffrey Sachs and Rahshemah Wise. 2021. [preprint](https://osf.io/preprints/socarxiv/2rx46/)

### Social and cultural dynamics of political violence

“Sociocultural Mechanisms of Conflict: Combining Topic and Stochastic Actor-Oriented Models in an Analysis of Afghanistan, 1979–2001”, with Michael Freedman. 2020. *Poetics* 78: 101403. [link](https://www.sciencedirect.com/science/article/abs/pii/S0304422X18302766?via%3Dihub)

“Rhetorics of Radicalism”, with Michael Freedman. 2019. *American Sociological Review* 84: 726-753. [link](https://journals.sagepub.com/doi/full/10.1177/0003122419859519)

“Aid, Exclusion, and the Local Dynamics of Insurgency in Afghanistan”, with Sebastian Schutte. 2018. *Journal of Peace Research* 55: 711-725. [link](https://journals.sagepub.com/doi/full/10.1177/0022343318777566) [blog version](http://politicalviolenceataglance.org/2019/03/15/how-us-military-aid-can-backfire/)

“Local Peace and Contemporary Conflict: Constructing Commonality and Exclusion during War in Afghanistan”. 2017. *Social Science Research* 61: 75-97. [link](https://www.sciencedirect.com/science/article/abs/pii/S0049089X16303908)

“Aid, Power, and Grievances: Lessons for War and Peace from Rural Afghanistan”. 2015. *The Economics of Peace and Security Journal* 10: 43–52. [link](https://www.epsjournal.org.uk/index.php/EPSJ/article/view/228)





Site-wide configuration
----------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
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
