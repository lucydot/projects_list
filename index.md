## A list of projects for undergraduate, postgraduate and summer students

These projects are designed to have a real, tangible impact on the research conducted in our group. They are flexible, and the project list is incomplete - so if you want to do something related, but not listed, please just get in contact with me.

## Projects based around *ab-initio* Materials Modelling, Data and/or Machine Learning

Ab-initio materials modelling is an exciting area of science which combines solid state physics, quantum chemistry and computer simulations. Ab-initio means "from the beginning" or "from first-principles": the idea being that simulations of electrons and atoms within a material are ran with little experimental input, using theories derived from quantum mechanics. An increasingly popular approach is to use techniques from data science to probe the existing ab-initio data hosted on large databases. Linked also to this is using Machine Learning to model materials with the accuracy of ab-initio simulations, but at lower computational cost.

For more on this area of work, please see my short description of [solid state physics](https://lucydot.github.io/projects_list/solid-state-phys).

### Singing Materials: Phonon sonification

**A phonon** is a quantum mechanical particle of heat. Phonons are used to describe the vibrations of a crystalline material. These vibrations are important because they affect a whole host of material properties, like electrical conductivity. **Sonification** is the use of non-speech audio to convey information. A well-known scientific example is a geiger counter which produces an audible click when it detects an ionisation event. Sonification can also be used creatively as a tool for musical composition.

In this project you will use cutting-edge tools from the [Audio Universe](https://www.audiouniverse.org/) project to explore sonification of phonon data. You will work alongside an active research team based across Northumbria and Newcastle University, identifying how best to communicate these quantum vibrations either as a tool for teaching or composition.

### Do we need to use consistent exchange-correlation functionals?

Exchange-correlation functionals are an incredibly important aspect of Density Functional Theory (DFT) as they determine the accuracy of our predictions. A common strategy when using DFT is to predict the atomic structure of a material using a "cheap" functional, followed by a prediction of electronic structure with an "expensive" functional. However it is not well understood when this approach is valid. In this project you will start to explore this question using Density Functional Theory with various exchange-correlation functionals. You will monitor how predicted band gaps vary with each approach, with a focus on identifying chemical trends. To do so you will compare results across the oxide, halide and sulfide perovskites.

### Under Pressure: identifying the chemical trends for internal pressure

A material expands as it is heated up.
The internal pressure of a material corresponds to sensitivity of free energy to volume expansion. In a perfect gas the internal pressure is zero: the free energy is independent of volume.  At the other extreme, carbon in the diamond has such a large internal pressure that it can contain [space water from millions of years ago](https://space.stackexchange.com/questions/18374/what-forms-of-water-ice-have-been-observed-and-verified-in-the-solar-system/33570#33570). Whereas carbon in the graphite structure is somewhere in this middle, with a free energy which is more weakly dependent on volume expansion. In this project you will use Density Functional Theory to quantify the internal pressure of a range of materials.  You will also explore how internal pressure varies with material chemistry. To do so you will compare results for the oxide, iodide and sulfide perovskites.

### Data Science meets Materials Science: exploring the relationship between bond length, atomic mass and phonon frequency

The [Materials Project](https://next-gen.materialsproject.org/materials) is a web-based database containing quantum chemical information on known and predicted materials, as well as powerful analysis tools to inspire and design novel materials. In this project you will use the [Materials Project API](https://next-gen.materialsproject.org/api) to determine the relationship between bond length, atomic mass and phonon frequency. Standard harmonic models would indicate that there is a simple relationship between these three values, but this relationship remains largely unexplored, with only [preliminary work available](https://www.nature.com/articles/sdata201865). Extensions to machine learning model development is also possible, and would allow extrapolation to material data that has not yet been collected.

### Developing a machine learning model for zirconium sulfide

A recent development in our group is using machine learning models to predict the behaviour (vibrations) of materials across a range of temperatures. This allows us to accurately predict, without any experimental input, how a material might perform in the lab or in a working device. 
Zirconium Sulfide (ZrS2) is a crystalline compound used to form photovoltaic (solar cell) materials. In this project you will use a [state-of-the-art computational framework](https://calorine.materialsmodeling.org/) to develop a machine learning model which describes the finite-temperature vibrations of ZrS2. A successful model will ultimately allow us to predict the temperatures at which related materials are stable or degrade.

### Quantum Chemical model for mixed chalcogenide perovskites

Our [recent research](https://pubs.acs.org/doi/10.1021/acsaem.3c03208) shows that BaZrS3 is a promising material for photovoltaic applications. A key material property for solar cell applications is the band gap, which can be tuned by mixing selenium onto the sulfur site, forming BaZr(S,Se)3. In this project you will use the Quantum Chemical method Density Functional Theory and supercomputing to model the properties of BaZr(S,Se)3 from first-principles. This will form an important first step towards continued experimental synthesis and characterisation.

### High-throughput screening for anharmonic materials

The [Materials Project](https://next-gen.materialsproject.org/materials) is a web-based database containing quantum chemical information on known and predicted materials, as well as powerful analysis tools to inspire and design novel materials. In this project you will use the [Materials Project API](https://next-gen.materialsproject.org/api) to screen for materials which display strong anharmonicity through a large [three-phonon phase space](https://www.nature.com/articles/s41467-021-23618-7). You will analyse how these anharmonic vibrations correlate with other material properties, such as symmetry or chemical composition. This will provide useful insight into where the commonly used harmonic model breaks down, and may help new identify materials for thermoelectric applications, where anharmonicity is beneficial.

## Projects based around Research Software Engineering 

[Research Software Engineering](https://rse.ac.uk/what-is-an-rse/) is a quickly growing discipline and emerging career route. It is centred around developing and maintaining software that enables research across a range of domains. The projects listed below are geared towards our work in materials modelling, but do not necessarilly require domain-specific expertise.

I've given a rough indication of how challenging each project is: ⭐ = straight-forward, ⭐⭐⭐⭐⭐ = can it even be done?
However the difficulty will vary depending on your previous experience and skill-set, so do not take it _too_ literally. There is also scope to extend each project if you find you need an extra challenge!

### Winning an OSSCAR

The OSSCAR (Open Software Services for Classrooms and Research) platform is a collaborative environment targeted at enhancing awareness and adoption of best practises in Open Science and computational thinking, focusing on education and research. You can see more details here: https://www.osscar.org/.

In this project you will use OSSCAR to develop a web application in the area of physics or materials science. The topic will be geared towards your interests, and will most likely be designed to cement your understanding of concepts covered during your undergraduate training. For example, you may like to develop a web app based on the phenomenon of quantum tunnelling or a web app for simulating heat diffusion. Successful projects will be submitted to the OSSCAR hub and, through this, will be disseminated across institutions worldwide.

Difficulty = ⭐⭐

### Delete the duplication! Efficient documentation

A combination of a Github README page and a documentation site (generated using [Sphinx](https://www.sphinx-doc.org/en/master/) or similar) is very commonly used for documenting research software projects. This can lead to a duplication of effort, with the developer having to maintain / update each page separately even when there is significant crossover in content. For example, see where Installation instructions are duplicated in the README [here](https://github.com/lucydot/effmass#installation) and the documentation site [here](https://effmass.readthedocs.io/en/latest/Installation.html).

In this project you will design a workflow, possibly based on a tool such as Github actions, to remove this duplication of effort and save researcher time.

Difficulty = ⭐⭐

### But who uses this software? Quantifying the impact of research software

It is increasingly common for academics to develop software for their research. Despite the time investment made, this effort is not commonly recognised and there are [open issues around software citation](https://www.software.ac.uk/how-cite-software). Other quantities for measuring impact  - such as the number of downloads via the from [Python package index stats](https://packaging.python.org/guides/analyzing-pypi-package-downloads/) - are an inaccurate reflection of the number of users. The number is inflated due to installs for continuous integration, and through use of download mirrors, amongst other factors.

As a concrete example, take the software project [`effmass`](https://github.com/lucydot/effmass). This is a very niche tool that calculates the effective mass of electrons from the output of quantum chemical simulations. It has been downloaded a suspiciously _high_ 14,000 times and cited (in peer-reviewed journals) a suspiciously _low_ 4 times.

In this project you will: i) research the current tools for quantifying the impact of research software; ii) identify the limitations/approximations inherent to each tool; iii) design a tool for calculating quantities (e.g download statistics) that more accurately reflect software impact.

Difficulty = ⭐⭐

### Electrons for all: Developing a GUI for the `effmass` project

A graphical user interface (GUI) helps to reduce the learning curve for using software, increases the base of potential users and can ultimately increase citations and impact. A well-designed GUI can perform validation and increase the robustness and reproducibility of the results. 

In this project you will design a GUI for the software project [`effmass`](https://github.com/lucydot/effmass), which calculates the effective mass of electrons from the output of quantum chemical simulations. The optimum GUI would be: multi-platform (Windows, MacOS, other unix-based systems), accessible (downloaded as a standalone executable) and robust (with automated testing for continuous integration with the release of new `effmass` versions).

Difficulty = ⭐⭐⭐

### Building a bot for RSdropinUK:

As data volumes continue to grow, models and algorithms get more complex and research processes require increasingly advanced pipelines, more and more researchers will find themselves writing or working with software. [RSdropinUK](https://rsdropin.github.io/RSdropinUK/) aims to provide regular, informal, community-led sesssions where researchers and research software developers can come along to ask questions about technical problems or challenges, or to ask for general technical advice.

To co-ordinate the drop-in sessions there are two groups of people to manage: participants who ask the questions, and volunteer experts who answer the questions. Many people end up acting in both roles, as we all experts in some things, and novices in others. Managing these two groups is currently quite a time-intensive process. Sign-up is via an online form, which we then reply to via email. Ideally we would have a system where volunteer experts can sign up in advance, advertising their skill-set, and participants sign-up in advance, with an outline of their problem. This process would be automated, requiring as little human intervention as possible, and the sign-up information for each session would be publically available.

In this project you will work with the RS-dropin-UK organisers to design (on paper) an optimum workflow for expert and volunteer management. You will then use open source tools such as Github actions and Github pages to automate this process as far as is possible. For Github automation inspiration, see the editorial bot [Buffy](https://github.com/openjournals/buffy) which helps scientific journals ([JOSS](https://joss.theoj.org/) and [rOpenSci](https://ropensci.org/)) and conference proceedings ([JuliaCon](https://proceedings.juliacon.org/)) manage submission reviews.

Difficulty = ⭐⭐⭐⭐

### Implementing a Poisson-drift-diffusion solver for solar cells

[Solcore](https://www.solcore.solar) was originally created as a heterogeneous aggregate of tools used by researchers as part of their work on high-efficiency photovoltaic devices (solar cells). Among Solcore’s unique features is the implementation of multiple models to simulate the electrical and optical properties of solar cells, including both traditional, well-established approaches and novel designs. This feature provides Solcore with an unprecedented capability that other photovoltaic solar cell software packages cannot match. 

An important part of Solcore is the Poisson-drift-diffusion (PDD) solver - this is the only part of Solcore written in Fortran, is custom-made and is becoming increasingly difficult to maintain. 

In this project you will undertake a major refactoring of the PDD solver in Solcore. You will make use of existing numerical packages written in Python (for example FiPy) to solve the underlying partial differential equations. If the project is successful, Solcore will be significantly easier to install and, as a result, will be accessible to a larger community of researchers.

Difficulty = ⭐⭐⭐⭐⭐

