README: Project template
========================

This repository is to be the starting point for all new projects in the [Yoder Lab](http://lab.jbyoder.org). To begin a new project, fork this one, renaming it to something apt and pithy. 

This file is the README, which contains an explanation of the repository contents. It's written in [markdown](https://daringfireball.net/projects/markdown), a form of text markup that is readable as plaintext, but that can also be interpreted into formated rich text or HTML by various readers, including the GitHub website. When you create a project, you should revise this file to describe the project as you plan it, and keep it updated as you proceed.


Directory structure and contents
--------------------------------

These are the major contents and subdirectories of the project folder. Add or delete and modify as necessary.

- `project_template.text`: project notes, ongoing, in markdown; RE-NAME this to match the repository name when you fork this repo to create a new project
- `scripts`: shell scripts and other languages
	- `R`: R code specifically
- `data`: data generated *in the course of analysis*; larger raw datafiles, especially DNA sequence reads, should live elsewhere, outside the project folder, to save space on GitHub and so that we can share project code without automatically also sharing the raw data
- `output`: final(ish) analysis results
- `figures`: figures
- `ms`: manuscript text, drafted in markdown with [LaTeX](https://www.overleaf.com/learn/latex/Learn_LaTeX_in_30_minutes)-formatted display items (tables, figures, equations) for typesetting using pandoc; we will usually port writing work to [https://www.overleaf.com](Overleaf) when we get past initial drafting.


Dependencies
------------

These are the programs, utilities, and other software infrastructure necessary to make the elements of the project work. At a minimum, we'll usually use the following; add to this as the project proceeds.

- pandoc --- [https://pandoc.org](https://pandoc.org) --- for typesetting manuscript drafts
- R --- [http://www.r-project.org](http://www.r-project.org) --- for most statistical analysis and a fair bit of scripting-like work


External data
-------------

This should list and describe any external datasets that the project scripts operate on. File formats, especially, should be annotated to aid people using the project scripts. For instance, projects in our lab will often use

- `Jotr_SDM2023_range` --- folder with `jotr_SDM2023_range.shp` and `jotr_SDM2023_range_simple.shp`, shapefiles (and accessory files) that provide range map polygons for Joshua tree (eastern and western together) derived from the [Esque *et al.* (2023)](https://doi.org/10.3389/fevo.2023.1266892) data set.
- `PRISM` --- folder of raster-formatted monthly weather data from 1900 to the most recent full year, from the [PRISM](https://prism.oregonstate.edu) database
