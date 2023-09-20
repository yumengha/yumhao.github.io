---
permalink: /
title: "academicpages is a ready-to-fork GitHub Pages template for academic personal websites"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hello, I am a 24-year-old master's student from the College of Art and Design at Zhengzhou University of Light Industry.I am now in my third year of postgraduate studies. Facing the impending crossroads in my life, I have firmly chosen to continue my academic journey. I've decided to become a researcher, to pursue a doctorate, and to delve deeper into my field of expertise. In reality, the challenges of becoming a doctorate holder and successfully obtaining a PhD might deter some. Furthermore, the monotony and tediousness of academic research can make some feel overwhelmed. Yet, facing these potential challenges and trials, my decision to pursue a doctoral degree is the result of careful and thorough consideration.

Why choose to pursue a doctorate?
======
During my second year of graduate studies, I reflected on the possible life choices I might face after graduation. Like many others, I had three options. The first was to work in a field related to my major, essentially becoming a designer.The second was to take the civil service exam and join the government system. The third was to continue pursuing a doctorate. Among these three options, considering my unique strengths and characteristics, I chose the third path, which I believe is the most suitable for me.

1. Personality.I am a genuine child raised in the countryside and a typical "left-behind child." Growing up, I lived with my grandmother, managing and working on the few acres of land our family owned. The laborious and busy agricultural life made me recognize the hardships of life from a young age, and it also cultivated in me a tenacious and steady character.At the same time, having no siblings, I grew accustomed during my childhood to finding joy on my own, gradually developing a preference for solitude in my approach to life.All these factors enable me to adapt well to the monotonous life of scientific research. It could be said that due to my personality, I prefer to become a researcher.

2. Ability.Due to my upbringing, I enjoy delving deeply into subjects on my own,which has endowed me with strong self-learning capabilities.In college, I entered the entirely new world of design as a student with a science background. The content of my studies shifted from mathematical formulas to hand drawings.Despite this drastic change, I quickly adapted to the transition relying on my own abilities. Throughout my undergraduate years, including my postgraduate entrance exam preparations,I have never enrolled in any hand-drawing tutoring classes.With just a few sketching guidebooks and extensive practice, I successfully became a master's student in art and design. Eventually, I was the only student in my cohort with a science background and who did not come from a dedicated drawing class.It can be said that my strong learning ability has given me the confidence to choose and face a life in research.

From sharing about my upbringing and my postgraduate entrance exam experience, on one hand, I aim to explain the reasons for my choice to pursue a doctorate based on my personal circumstances. On the other hand, I also wish to demonstrate something to the professors:

[If you choose me, although I may not be the best, I will certainly be the most hardworking one.]

Please believe that I am not lacking in the effort to embrace success. What I lack is a better platform and resources.Hence, I've chosen to continue my climb on the academic path, and I choose to become your student and pursue further studies.


As for why I say this, I hope to continue showing you a sincere and hardworking side of me, but this might take some of your time:

If you wish to understand me more deeply, you can refer to the [Growth Diary] section.

Additionally, after deciding that I wanted to pursue a doctorate, the efforts I've made towards this goal can be seen in the [publications] section.

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
