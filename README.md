# Documentation standards and resources for NumFOCUS projects websites

The aim of this repository is to define some standards that NumFOCUS projects can implement.
This will allow users of different projects to have a consistent experience across websites
of different projects. And will make it easier to navigate websites that can possibly have:

- A common terminology to refer to the sections
- The same order (which section appears first...)

## Origin

The creation of this document started in the discussions to unify the navigation of
[NumPy](https://numpy.org/) and [pandas](https://pandas.pydata.org).
See https://github.com/numpy/numpy.org/issues/43

The discussion continued at the [NumFOCUS summit 2019](https://numfocus.org/summit2019)
with a session about websites. Notes have been copied to: #1

## Navigation

Current proposal (feel free to propose changes via PRs or Issues).

It's expected that in some cases projects need to add sections not
in this navigation, or don't want to have some sections. Using the
same terminology and structure can still be useful to users, even
if small differences exist.

- About us
  - Our history
  - Ecosystem
  - Roadmap
  - Team
  - Sponsors
  - Citing <project>
  - Donate
- Getting started (single page)
  - Install
  - Tutorials
  - Videos
  - Books
  - Courses
  - Cheat sheets
- Documentation
  - User guide
  - API reference
  - Release notes
  - Older versions
  - ... (NEPs, f2py guide for NumPy...)
- Community
  - Blog
  - Ask a question (StackOverflow)
  - Discuss (Discourse / mailing list)
  - Code of conduct
  - Community survey
- Contributing
- ... (Array computing for NumPy - NBViewer, JupyterHub, Widgets for Jupyter,...)

## Sphinx theme

https://github.com/pandas-dev/pandas-sphinx-theme
