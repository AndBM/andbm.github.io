---
title: "Using git to manage your research / thesis"
collection: projects
type: "Coding project"
permalink: /projects/git-for-research-project-management/
date: 2019-11-01
---

An important part of managing research projects is having the right tools for the job. Even for projects without code, git can be a powerful tool for managing notes and collaborating on papers, especially in comparison to a setup consisting of emails + shared Dropbox folders. Consider the following workflow:

You set up a private repository hosting all LaTeX notes and WIP papers. You invite your collaborators. At regular intervals, e.g. each day, you commit your work with a short description. Before discussing with collaborators, they pull the latest version of your notes and compile.

Benefits:
- Each commit marks a checkpoint in your research, which helps you track your progress and gives a digital paper trail if the originality of your research is called into question.
- Papers can be worked on locally in parallel with collaborators and easily merged. Each author's contribution can be clearly tracked.
- While not the most secure way of backing up your project, it is still better than e.g. Dropbox.
- Communicating through e.g. the Issues section on GitHub gives you access to markdown (very useful for quick math like "h<sub>&theta;</sub>(x,y) = &theta;<sub>0</sub> x + &theta;<sub>1</sub>y" ) and collects all your discussions in one place, instead of having it spread through your inbox.
- Synergizes nicely with versioning of any code your project might include.

Drawbacks:
- To work optimally, PDF files should be put in .gitignore and will need to be generated locally after a pull.
- Requires tech-savvy supervisors / collaborators.
- Using GitHub might conflict with GDPR or institution policy - an alternative is a locally hosted instance of GitLab.
- Does not provide real time LaTeX collaboration like e.g. Overleaf.
- Requires use of software that might be considered non-standard in comparison to an email client and e.g. Dropbox, and so might complicate the workflow for collaborators.

For less tech-savvy supervisors, a simple workflow should be doable through a GUI like GitHub Desktop (sadly not available for Linux, though). Although there is not direct method of backing up the Issues section offline, it can be done in a unix terminal using  ``curl -i "https://api.github.com/repos/<user>/<repository>/issues?state=all" -u "<user-name>" > <filename>``

Much more is of course possible through the use of branching and so on, but I find that this is a nice, minimal example of how git can be an excellent tool for research.
