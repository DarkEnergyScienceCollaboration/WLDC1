# WLDC1
Configuration and planning for DESC Weak Lensing DC1 simulations

## Getting started

- Read the objectives below and the relevant sections of the DESC Science Roadmap DC1 Key Project WL1.
- Review the ongoing tasks and task leads for the Weak Lensing group on the [DESC wiki](https://confluence.slac.stanford.edu/display/LSSTDESC/Weak+Lensing+Near-term+Tasks+in+the+Science+Roadmap).
- Sign up to lead or contribute to a task.
- Create a git 'branch' of this repository for your project.
- Build a simulation script and commit it to this repository on your branch.
- Run your simulations, commit any analysis scripts here as well.
- Document your analysis on the 'Issues' or 'Wiki' page for [this repository on Github](https://github.com/DarkEnergyScienceCollaboration/WLDC1) or on the DESC Confluence wiki.
- Report on your work at a DESC WL telecon or DESC meeting.
- Publish a paper!
- Merge your branch into the 'master' branch for posterity and for others to use. 

## Objective for DC1 Key Project WL1

From the [Science Roadmap](https://confluence.slac.stanford.edu/display/LSSTDESC/Science+Roadmap+2015), our objective for the first Weak Lensing Data Challenge is,

"Develop a software pipeline that can be used to derive a rigorous set of requirements for both LSST DM outputs and our own analysis steps, along with a suite of null tests to verify that these requirements are met."

For DC1, we will use small-scale simulated datasets (e.g., from GALSIM; the code for producing such simulations is herein called WLIMSIM) and/or real data to do the preparatory steps needed to carry out a cosmological weak lensing analysis. Part of the motivation for this choice to not do a traditional data challenge is that some aspects of the analysis on the DM side (e.g., shear estimates) are not quite ready for us to use in any kind of realistic analysis, and there is substantial software to develop for the step from catalogs to science.

Note that this key project will not focus much on blending issues; these are the subject of a parallel effort in CX1, especially CX1.1WL and CX1.3WL, which will happen on a similar timescale. However, at no point in this key project should blending issues be “designed out” of the code. By the DC2 time frame, we will need to merge these two parallel tracks into a single pipeline and suite of null tests.

## What are actually simulating?

See the plan on the [DESC wiki here](https://confluence.slac.stanford.edu/display/LSSTDESC/DC1+WL+simulations).

## Tools

- GalSim
- ...
