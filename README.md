# URSSI Summer School on Research Software and Open Science, July 2024
---

## Discussion and notes

[HackMD for notes/discussion](https://hackmd.io/@M0eajM-mS9CDKKt8Rq--0g/B1cjGQVFC)

[Zulip chat room](https://urssi-softwareschool.zulipchat.com)

--- 

29 July - 02 August 2024, Urbana-Champaign IL

Welcome! This is the repository for the 2024 URSSI Summer School on Research Software and Open Science, held at the University of Illinois at Urbana-Champaign. All instruction will happen at the [Campus Instructional Facility](https://cif.illinois.edu/) (CIF), room 4031.

## Tentative schedule

| Time | Topic  | Instructor |
|:--|:--|:--|
| July 29th, 8:30-9am | Room Open, Coffee | |
| July 29th, 9-9:45am  | [Welcome and introductions](https://munkm.github.io/research-software-schools/school-intro.slides.html) | Madicken |
| July 29th, 9:45am-12pm | [Software design](https://evamaxfield.github.io/winter-school-lectures/software-design-and-modularity.slides.html#/), [Structuing Python packages](https://docs.google.com/presentation/d/1thjeqGGnx40pnVobCNxgsXxXA14WimmqlH2tPomOpSg/edit?usp=sharing), [Distributing your Science][Distributing your Science] | Matthew |
| July 29th, 12-1:00pm | Lunch | |
| July 29th, 1pm-3pm | [Software design](https://evamaxfield.github.io/winter-school-lectures/software-design-and-modularity.slides.html#/) , [Structuing Python packages](https://docs.google.com/presentation/d/1thjeqGGnx40pnVobCNxgsXxXA14WimmqlH2tPomOpSg/edit?usp=sharing), [Distributing your Science][Distributing your Science] | Matthew |
| July 29th, 3-5pm | Ethos of Open Science | Madicken |
|--|--|--|
| July 30th, 8:30-9am | Room Open, Coffee | |
| July 30th, 9am-12pm | [Collaboration with Git/GitHub/Workflows](https://munkm.github.io/2024-winterschool/git-collaboration.slides.html) | Danika |
| July 30th, 12-1pm | Lunch | |
| July 30th, 1-2:30pm | Work Time | Everybody |
| July 30th, 2:30-5pm | Open Tools and Resources | Ana |
|--|--|--|
| July 31st, 8:30-9am | Room Open, Coffee | |
| July 31st, 9am-12pm  | [Testing and continuous integration, linting](https://evamaxfield.github.io/winter-school-lectures/testing-lint-ci.slides.html#/)  | Ana |
| July 31st, 12-1pm | Lunch | |
| July 31st, 1-2:30pm | Work Time | Everybody |
| July 31st, 2:30-5pm | Open Data | Matthew |
|--|--|--|
| August 1st, 8:30-9am | Room Open, Coffee | |
| August 1st, 9am-12pm | [Peer code review](https://munkm.github.io/research-software-schools/peer-review.slides.html), work time | | Madicken
| August 1st, 12-1pm | Lunch | |
| August 1st, 1-2:30pm | Work Time | Everybody |
| August 1st, 2:30-5pm | Open Results | Kyle |
| August 1st, 6:30 pm | Dinner at [Maize at the Station](https://www.maizemexicangrill.com/the-station) | |
|--|--|--|
| August 2nd, 8:30-9am | Room Open, Coffee | |
| August 2nd, 9am-12pm | [Documentation and versioning](https://kyleniemeyer.github.io/research-software-dev-modules/module-documentation/), [Open science & software citation](https://kyleniemeyer.github.io/research-software-dev-modules/module-open-science/) | Kyle |

Each morning and afternoon session will be split up with a break, and we'll have lunch organized on-site M-Th.

[Distributing your Science]: https://github.com/matthewfeickert-talks/talk-urssi-summer-school-2024

## Code of Conduct

We have adopted a [code of conduct](https://github.com/si2-urssi/summerschool-June2024/blob/main/CODE_OF_CONDUCT.md) for the URSSI Summer School and all associated spaces, both physical and digital. Please review this.

The URSSI Summer School is a scent-free environment. We would like to ask the participants to refrain from using any scented lotions, perfumes, essential oils, scented antiperspirants, etc., as these make the space inaccessible for folks with asthma, allergies to the scents, or with Multiple Chemical Sensitivity. Having a scent-free environment will help prevent dizziness, nausea, breathing difficulties, headaches, and other issues among our participants.

## Instructors

[Madicken Munk](https://github.com/munkm)

[Danika MacDonell](https://github.com/danikam)

[Matthew Feickert](https://www.matthewfeickert.com/)

[Ana Trisovic](https://anatrisovic.com/) 

[Kyle Niemeyer](https://github.com/kyleniemeyer)

## Teaching assistants / aids

[Aya Hegazy](https://github.com/AyaHegazy22/)
 
[Silvana Tabares Burgos](https://github.com/tabaress9)
 
## Requirements

You will need a laptop with a Mac, Linux, or Windows operating system (not a tablet, Chromebook, etc.) that you have administrative privileges on, and need some specific software packages installed:


**On your machine**
- the Bash shell; you should only have to set this up if you are using a Windows machine, following the [Software Carpentry setup instructions](http://carpentries.github.io/workshop-template/#setup)
- Git [installed](http://carpentries.github.io/workshop-template/#setup) and [configured](https://swcarpentry.github.io/git-novice/02-setup.html) on your local machine
- Python 3.x; we recommend installing [Miniconda](https://docs.anaconda.com/miniconda/)
- a text editor, preferably one designed for writing code; we recommend [VS Code](https://code.visualstudio.com) if you haven't chosen one.

**In the browser**
- You should sign up for a [GitHub](https://github.com/) account if you don't already have one. Make sure you have your [github authentication](https://swcarpentry.github.io/git-novice/#creating-a-github-account) set up as well. 
- Sign in to the school's Zulip instance to communicate with students and instructors throughout the course: https://urssi-softwareschool.zulipchat.com
- Register for an [ORCID](https://orcid.org/) and sign in to the [Open Science MOOC](https://openscience101.org/) using your ORCID. At the completion of the school you will receive a badge for this curriculum that shows up on your ORCID account.  

Specific Python packages (install with pip or conda):
- pytest
- sphinx

## Projects

Most of your work time will be spent on an individual project where you develop a research software package.
Please bring an idea or some basis for a project.

Ideally, this should be something that supports your work and that you would (or could) continue developing or using after the winter school.
We hope that most—or at least some—of the projects will eventually be submitted to the [Journal of Open Source Software (JOSS)](https://joss.theoj.org), which we'll briefly talk about on the final day.

## Reimbursements

Please follow the instructions you will receive over email and reach out to Madicken Munk with any questions or concerns.

## Feedback 

TBD
