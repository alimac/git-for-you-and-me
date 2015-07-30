<!-- .slide: data-background="#fff" -->
# <i class="fa fa-code-fork"></i> Git for you and me
### DrupalCorn 2015



## [http://bit.ly/git-drupalcorn](http://bit.ly/git-drupalcorn)

Note:
- Slides and speaker notes available online



## Alina Mackenzie
#### _University of Illinois at Chicago_
<img src="custom/images/alimac-avatar.png">

<a href="https://www.drupal.org/u/alimac"><i class="fa fa-drupal"></i> alimac</a>

<a href="https://twitter.com/czaroxiejka"><i class="fa fa-twitter"></i> czaroxiejka</a>

char • o • jay • ka
<!-- .element class="fragment" style="word-spacing: 8px;" -->

Note:
- Developer and system administrator based in Chicago
- Doing Drupal for ~4 years, active in the community for ~2 years
- Using git for ~2 years



## Plan

Note:
- This is a beginner session
- Introducing concepts, sprinkling with tips
- Healthy dose of resources for beginners



<!-- .slide: data-background="custom/images/clement127-chemical-experiment.jpg" style="text-align: left;" data-state="show-header" data-header="Photo: CC-BY-NC-ND clement127 https://flic.kr/p/pZg3v (cropped)" -->
## Why?
<!-- .element class="heading" -->
<br>

history
<!-- .element class="fragment heading invert" -->

undo
<!-- .element class="fragment heading invert" -->

experiment
<!-- .element class="fragment heading invert" -->

Note:
- "Everybody's doing it."
- 3 reasons:
 1. write project history
 1. undo changes (thanks to history)
 1. experiment and track changes



<!-- .slide: data-background="custom/images/boris-baldinger-sprinting.jpg" style="text-align: left;" data-state="show-header" data-header="Photo: CC-BY Boris Baldinger https://flic.kr/p/ps8ZgK (cropped)" -->
## How?
<!-- .element class="heading" -->
<br>

single user
<!-- .element class="fragment heading invert" -->

collaborative
<!-- .element class="fragment heading invert" -->

Note:
- single-user: local, or local+remote
- collaborative: local+remote



## Distributed or centralized?

Note:



<!-- .slide: data-state="show-header" data-header="Diagram by Scott Chacon and Ben Straub, git-scm.com" -->
## Centralized
<img src="custom/images/centralized.png">

Note:
- Client-server model
- Local checkout of recent files
- Full history of the project is on a central server
- Example: CVS, Subversion



<!-- .slide: data-state="show-header" data-header="Diagram by Scott Chacon and Ben Straub, git-scm.com" -->
## Distributed
<img src="custom/images/distributed.png">

Note:
- Each developer works directly with their own local repository
- Changes are shared between repositories as a separate step
- Full history in every repository
- Agreement on which is the authoritative repository
- Example: Mercurial, Git



## Hosting



## <i class="fa fa-terminal"></i> Command line
Update to the latest version (2.5.0)
<!-- .element: class="fragment" -->

Note:
- Download for Windows, comes with OS X, Linux
- Tip: update for latest features



## <i class="fa fa-desktop"></i> Apps
- [SourceTree](https://www.sourcetreeapp.com/)
- GitHub for [Windows](https://windows.github.com/) and [Mac](https://mac.github.com/)
- [SmartGit](http://www.syntevo.com/smartgit/)

Note:
- SourceTree: OS X, Windows. Free
- GitHub for: OS X, Windows. Free
  - [GitHub Desktop](https://desktop.github.com/) - join waitlist
- SmartGit: cross-platform. Commercial license, non-commercial license



## SourceTree
<img src="custom/images/sourcetree.png">

Note:
- Same concepts (add, remove, branch, merge) apply
- At-a-glance view of the repository vs. command at a time



## Configure git
- system <i class="fa fa-laptop"></i>
- global <i class="fa fa-user"></i>
- local <i class="fa fa-folder-open"></i>

Note:
Configuration has scope:
- system-wide (for all users of a system)
- global (for all of user's projects)
- local (for a specific project)






## Setting



## Phases



## Sidekicks



## Commit



## Push



## Undoing



## Branching



## Merging



## Rebasing



## Conflicts



## More than one way



## What next?



### Git Immersion
#### [gitimmersion.com](http://gitimmersion.com)

Note:
- guided tour that walks through the fundamentals of Git
- inspired by the premise that to know a thing is to do it
- for step-by-step learners



### Try Git
#### [try.github.io](http://try.github.io)

Note:
- created by Code School, sponsored by GitHub
- in browser tutorial
- for instant gratification



### Visualizing Git Concepts with D3
#### [onlywei.github.io/explain-git-with-d3](http://onlywei.github.io/explain-git-with-d3)

Note:
- D3.js is a JavaScript library for data visualization
- Animates git concepts like branching, pushing, merging
- for visual learners of git concepts



### Git for Teams
#### [gitforteams.com](http://gitforteams.com)

Note:
- comprehensive look at using git for teams of people
- for people who are looking for strategies to integrate git into existing teams



### Pro Git
#### [git-scm.com/book/en/v2](https://git-scm.com/book/en/v2)

Note:
- in-depth look at git, including what's inside git
- for people who like to take things apart to learn
