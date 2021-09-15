# Projects List

## A list of projects for undergraduate, postgraduate and summer students

At the moment most of these projects are in the area of [Research Software Engineering](https://rse.ac.uk/what-is-an-rse/).  
The projects are designed to have a real, tangible impact on the efficiency and impact of research conducted in our group.

If you are looking for something based within the domains of materials science or physics please contact me directly.  

### Project 1. Delete the duplication! Efficient documentation

A combination of a Github README page and a documentation site (generated using [Sphinx](https://www.sphinx-doc.org/en/master/) or similar) is very commonly used for documenting research software projects. This can lead to a duplication of effort, with the developer having to maintain / update each page separately even when there is significant crossover in content. For example, see where Installation instructions are duplicated in the README [here](https://github.com/lucydot/effmass#installation) and the documentation site [here](https://effmass.readthedocs.io/en/latest/Installation.html).

In this project you will design a workflow, possibly based on a tool such as Github actions, to remove this duplication of effort and save researcher time.

### Project 2. But who uses this software? Quantifying the impact of research software

It is increasingly common for academics to develop software for their research. Despite the time investment made, this effort is not commonly recognised and there are [open issues around software citation](https://www.software.ac.uk/how-cite-software). Other quantities for measuring impact  - such as the number of downloads via the from [Python package index stats](https://packaging.python.org/guides/analyzing-pypi-package-downloads/) - are an inaccurate reflection of the number of users. The number is inflated due to installs for continuous integration, and through use of download mirrors, amongst other factors.

As a concrete example, take the software project [`effmass`](https://github.com/lucydot/effmass). This is a very niche tool that calculates the effective mass of electrons from the output of quantum chemical simulations. It has been downloaded a suspiciously _high_ 14,000 times and cited (in peer-reviewed journals) a suspiciously _low_ 4 times.

In this project you will: i) research the current tools for quantifying the impact of research software; ii) identify the limitations/approximations inherent to each tool; iii) design a tool for calculating quantities (e.g download statistics) that more accurately reflect software impact.

### Project 3. Electrons for all: Developing a GUI for the `effmass` project

A graphical user interface (GUI) helps to reduce the learning curve for using software, increases the base of potential users and can ultimately increase citations and impact. A well-designed GUI can perform validation and increase the robustness and reproducibility of the results. 

In this project you will design a GUI for the software project [`effmass`](https://github.com/lucydot/effmass), which calculates the effective mass of electrons from the output of quantum chemical simulations. The optimum GUI would be: multi-platform (Windows, MacOS, other unix-based systems), accessible (downloaded as a standalone executable) and robust (with automated testing for continuous integration with the release of new `effmass` versions).
