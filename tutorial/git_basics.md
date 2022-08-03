# Git Basics for non-developpers

Introductory GIT tutorial by:

* [Anna Nagy](mailto:anna.nagy@econengineering.com)
* [Gergely Erdős](mailto:gergely.erdos@econengineering.com)
* [Milán László](mailto:milan.leszlo@econengineering.com)
* [Péter Mizsák](mailto:peter.mizsak@econengineering.com)

---

## Intorduction

As the number and complexity of coding projests grew at Econ,
it is time to jump to the next level at organizing these projects,
which is not possible without an approproate version-controll system
that enables the collaboration of multiple developpers.

The industry-standard for this purpose is `GIT`.

Using git can appear to be a bit complicated first,
but after understanding the basics, it can really accelerate the development.
It can also be used in your own, 1-person projects to track changes.

In this short tutorial our goal is to introduce the basic concepts of using git
withoud diving deep into the command-line.

### What is git?

* Git is a free and open-source *version control system*.
* Git is distributed: every developer has the full history of their code repository locally.
* Git keeps track of all the changes done on each file.
* With git you can revert to any prevous stage of the project.
* With git you can merge changes done by seperate developpers simultaniously.

### Why do we need version controll?

---

In git, you track your projects using a so-called `repository`. There are two types of repositories: one is **local**, tha other is the **remote** (called bare). They have different purposes but usually used together, so we will look at both types:

## Working with git locally

* Commit
  * add
  * stage
  * amend

* Branch
  * checkout
  * merge
  * rebase
  * merge conflict

## Working with remote repositories

* Clone
* Pull
  * fetch
  * merge/rebase
* Push
* Pull request

---

## GIT workflow summary

---

## Further useful features

* Stash
* Cherry-pick

---

## Useful links

### Tutorials

* [Web-based tutorial for command-line git commands](https://learngitbranching.js.org/)
* [Basic Git Workflow for Small Projects](https://medium.com/@peterjussi/a-basic-git-workflow-for-smaller-projects-d8694d50297d)
* [Atlasian: Feature branch workflow](https://www.atlassian.com/git/tutorials/comparing-workflows/feature-branch-workflow)

### Downloads

* [GIT official downlaod](https://git-scm.com/downloads)
* [GitLens VS Code extension](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)
* [Git Graph VS Code extension](https://marketplace.visualstudio.com/items?itemName=mhutchie.git-graph)
* [Sourctree desktop GUI](https://www.sourcetreeapp.com/)
