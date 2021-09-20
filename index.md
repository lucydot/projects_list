# Projects List

## A list of projects for undergraduate, postgraduate and summer students

At the moment most of these projects are in the area of [Research Software Engineering](https://rse.ac.uk/what-is-an-rse/).  
The projects are designed to have a real, tangible impact on the efficiency and impact of research conducted in our group.

I've given a rough indication of how challenging each project is: ⭐ = straight-forward, :star::star::star::star::star: = can it even be done?
However the difficulty will vary depending on your previous experience and skill-set, so do not take it _too_ literally. There is also scope to extend each project if you find you need an extra challenge!

If you are looking for something based within the domains of materials science or physics please contact me directly.  

### Project 1. Delete the duplication! Efficient documentation

A combination of a Github README page and a documentation site (generated using [Sphinx](https://www.sphinx-doc.org/en/master/) or similar) is very commonly used for documenting research software projects. This can lead to a duplication of effort, with the developer having to maintain / update each page separately even when there is significant crossover in content. For example, see where Installation instructions are duplicated in the README [here](https://github.com/lucydot/effmass#installation) and the documentation site [here](https://effmass.readthedocs.io/en/latest/Installation.html).

In this project you will design a workflow, possibly based on a tool such as Github actions, to remove this duplication of effort and save researcher time.

Difficulty = :star::star:

### Project 2. But who uses this software? Quantifying the impact of research software

It is increasingly common for academics to develop software for their research. Despite the time investment made, this effort is not commonly recognised and there are [open issues around software citation](https://www.software.ac.uk/how-cite-software). Other quantities for measuring impact  - such as the number of downloads via the from [Python package index stats](https://packaging.python.org/guides/analyzing-pypi-package-downloads/) - are an inaccurate reflection of the number of users. The number is inflated due to installs for continuous integration, and through use of download mirrors, amongst other factors.

As a concrete example, take the software project [`effmass`](https://github.com/lucydot/effmass). This is a very niche tool that calculates the effective mass of electrons from the output of quantum chemical simulations. It has been downloaded a suspiciously _high_ 14,000 times and cited (in peer-reviewed journals) a suspiciously _low_ 4 times.

In this project you will: i) research the current tools for quantifying the impact of research software; ii) identify the limitations/approximations inherent to each tool; iii) design a tool for calculating quantities (e.g download statistics) that more accurately reflect software impact.

Difficulty = :star::star:

### Project 3. Electrons for all: Developing a GUI for the `effmass` project

A graphical user interface (GUI) helps to reduce the learning curve for using software, increases the base of potential users and can ultimately increase citations and impact. A well-designed GUI can perform validation and increase the robustness and reproducibility of the results. 

In this project you will design a GUI for the software project [`effmass`](https://github.com/lucydot/effmass), which calculates the effective mass of electrons from the output of quantum chemical simulations. The optimum GUI would be: multi-platform (Windows, MacOS, other unix-based systems), accessible (downloaded as a standalone executable) and robust (with automated testing for continuous integration with the release of new `effmass` versions).

Difficulty = :star::star::star:

### Project 4. Building a bot for RSdropinUK:

As data volumes continue to grow, models and algorithms get more complex and research processes require increasingly advanced pipelines, more and more researchers will find themselves writing or working with software. [RSdropinUK](https://rsdropin.github.io/RSdropinUK/) aims to provide regular, informal, community-led sesssions where researchers and research software developers can come along to ask questions about technical problems or challenges, or to ask for general technical advice.

To co-ordinate the drop-in sessions there are two groups of people to manage: participants who ask the questions, and volunteer experts who answer the questions. Many people end up acting in both roles, as we all experts in some things, and novices in others. Managing these two groups is currently quite a time-intensive process. Sign-up is via an online form, which we then reply to via email. Ideally we would have a system where volunteer experts can sign up in advance, advertising their skill-set, and participants sign-up in advance, with an outline of their problem. This process would be automated, requiring as little human intervention as possible, and the sign-up information for each session would be publically available.

In this project you will work with the RS-dropin-UK organisers to design (on paper) an optimum workflow for expert and volunteer management. You will then use open source tools such as Github actions and Github pages to automate this process as far as is possible. For Github automation inspiration, see the editorial bot [Buffy](https://github.com/openjournals/buffy) which helps scientific journals ([JOSS](https://joss.theoj.org/) and [rOpenSci](https://ropensci.org/)) and conference proceedings ([JuliaCon](https://proceedings.juliacon.org/)) manage submission reviews.

Difficulty = :star::star::star::star:

### Project 5. Implementing a Poisson-drift-diffusion solver for solar cells

[Solcore](https://www.solcore.solar) was originally created as a heterogeneous aggregate of tools used by researchers as part of their work on high-efficiency photovoltaic devices (solar cells). Among Solcore’s unique features is the implementation of multiple models to simulate the electrical and optical properties of solar cells, including both traditional, well-established approaches and novel designs. This feature provides Solcore with an unprecedented capability that other photovoltaic solar cell software packages cannot match. 

An important part of Solcore is the Poisson-drift-diffusion (PDD) solver - this is the only part of Solcore written in Fortran, is custom-made and is becoming increasingly difficult to maintain. 

In this project you will undertake a major refactoring of the PDD solver in Solcore. You will make use of existing numerical packages written in Python (for example FiPy) to solve the underlying partial differential equations. If the project is successful, Solcore will be significantly easier to install and, as a result, will be accessible to a larger community of researchers.

Difficulty = :star::star::star::star::star:

