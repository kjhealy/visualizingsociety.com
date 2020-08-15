# SOCIOL 179FS: Visualizing Society

## Kieran Healy

![Socviz badge](static/img/social-image.png) 

This repository is a Hugo/Blogdown site that makes [visualizingsociety.com](https://visualizingsociety.com/), the website for a Freshman FOCUS Cluster seminar [I](https://kieranhealy.org) am teaching at Duke University in the Fall of 2020.

Various hugo and blogdown features were borrowed more or less directly from [Andrew Heiss](https://www.andrewheiss.com) and his excellent [teaching](https://statsf18.classes.andrewheiss.com/) and [class](https://econw19.classes.andrewheiss.com/) [websites](https://datavizf18.classes.andrewheiss.com/).

This site uses the [Academic Hugo theme](https://sourcethemes.com/academic/), which is _very nearly_ more trouble than it is worth. There are some slight template modifications found in `/assets/` and `layouts/`. The theme is included as a submodule, so when when cloning for the first time, use this command to get the theme too:

    git clone --recursive https://github.com/gcushen/hugo-academic.git

To get the theme later, use this command:

    git submodule add \
      https://github.com/gcushen/hugo-academic.git \
      themes/hugo-academic

To update to the latest version of the theme, use:

    git submodule update --recursive --remote
