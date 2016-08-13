OpenHPC: Template OBS Hierarchy

---

#### Introduction

This repository contains the template for packages to import into OBS.
They are mostly _service pointers to an adjunct github repository
containing either the code or the SPEC files pointing to the actual
code.  The contents here have had the crucial fields replaced will
well defined markers which can be easily search/replaced:

  * GITHUB_URL: the URL for the git base project
  * GITHUB_BRANCH: the branch of that git base project to use
  * AGGREGATE_PROJECT: base OBS project for dependencies (Lmod and Release)

Scripts to help cleanup and maintain these files are in 
http://github.com/arm-hpc/ohpc-utils and could probably be written
much better.
