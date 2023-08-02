---
permalink: /
title: "Today's bird: Eastern Phoebe"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<a href="https://www.audubon.org/field-guide/bird/eastern-phoebe">
  <img src="https://www.birdnote.org/sites/default/files/storage/eastern_phoebe-for-web-and-fb-joanne-kamo.jpg" alt="August 2 = Eastern Phoebe"></a>
  
One of our most familiar eastern flycatchers, the [Eastern Phoebe’s](https://www.audubon.org/field-guide/bird/eastern-phoebe) raspy “phoebe” call is a frequent sound around yards and farms in spring and summer. These brown-and-white songbirds sit upright and wag their tails from prominent, low perches. They typically place their mud-and-grass nests in protected nooks on bridges, barns, and houses, which adds to the species’ familiarity to humans. Hardy birds, Eastern Phoebes winter farther north than most other flycatchers and are one of the earliest returning migrants in spring.  

Drawing resource: [Learn to Draw Birds with David Sibley](https://www.audubon.org/magazine/summer-2020/learn-draw-birds-david-sibley)



The Rules
======
1. LOOK for your daily group text which will include the Bird of the Day (sourced from this birdwatcher's list). A link to The Audubon Society's info page will be posted here.
1. DRAW the bird. Any form, medium and interpretation is acceptable.
1. TEXT ME (not the group) a photo of your bird creation by 11:59pm PT and I'll upload all photos here each night. Better than receiving multiple bird texts a day, and a fun way to see everyone's different styles together!
1. HELP? A link to a random daily drawing tutorial will be posted simply because I need drawing help and inspiration. No need to use it. Found a cool resource? Please send it my way to share it here!
1. CONSISTENCY is key! It is more important than technique, perfection, and maybe even improvement.
1. FLEX your creativity muscle and challenge yourself to find a few (or more!) minutes every day to show up for this group!

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
[Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring academicpages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
