---
permalink: /
title: "About Me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
This is the front page for an academic portfolio, outlining myself and the current research interests I'm involved in, as well as some future directions. 

Currently an MASc. Candidate at Ontario Tech University, and part of the Nuclear Fuels and Materials Group, being co-supervised by Dr. Bernie Fitzpatrick, and Dr. Markus Piro. My research area involves nuclear forensics, and the proof of concept of characterizing of uranium hexa-fluoride drums for future use in inspection purposes. The main purpose of the work is to use surface characterization, and calorimetry based techniques to identify if the forensic fingerprint on the oxide surface is significant enough to determine enrichment of the uranium held. The work is part of a larger project headed by Dr. Micheal Short at MIT, and the project is in collaboration with the Mesoscale Nuclear Materials Group of MIT.

Previous research areas include oxidation, and oxide buildup of various materials, as well as investigations into thermodynamic systems of molten salts. Previous works include one paper published in the Journal of Nuclear Materials, and a secondary paper currently in press with hopefully more to come in the future.






Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

I have also created [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the academicpages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring academicpages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
