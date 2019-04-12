# workflows & Pipelines in Computational Science

TLDR;

Automation and repetition has become increasingly important for fields ranging from engineering to medicine to finance to data science.
There are a number of open-source software available to assist in creating workflows (or pipelines).

My aim has to been to figure out what could work best for improving automation and reproducibility in the computational sciences especially computational chemistry. The neighbouring fields of bioinformatics and data science have been very active in trying to solve the workflow and pipeline challenge. This has been refreshing. In computational chemistry (Academically at least), a 'just-functional' Bash or Python script is the norm. This is changing as software development techniques are increasingly being used to ensure robust and tested software, but it still not the norm.

In my search to understand the complexities and opportunities in this space, I have tested tools such as Knime, Taverna and Galaxy. Since these early explorations there are now a increasing number of options including NextFlow and Common Workflow Language. Websites such as CHARMM-GUI have provided an easy-to-use simulation setup which takes the users through a set of steps. A once challenging Molecular Dynamics setup is now accessible to anyone. Software such as Schrödinger integrates with KNIME but also has its own custom Python connections to send information between the software in the Schrödinger. Working with multiple software within the Schrödinger suite is thus fairly simple.

Newly written software that seeks to integrate into the computational landscape faces several roadblocks. One is the user interface, to ensure continued user buy-in it should probably be graphical, easy-to-use and support more advanced users by allowing scripting for better automation? Another is integration with other tools which would make it easy for users to carry out complex and repetitive tasks without manual steps.

I'm currently most interested in using Galaxy and this can be seen by my involvement in the Galaxy Computational Chemistry Team on GitHub (https://github.com/galaxycomputationalchemistry). In collaboration with [Björn Grüning](https://github.com/bgruening) and the [Galaxy computational chemistry team](https://github.com/galaxycomputationalchemistry), these tools are available on [Galaxy Europe](https://cheminformatics.usegalaxy.eu/) under the Chemical Toolbox section.
I'm very thankful to the Galaxy developers, the GCC team and to [Björn Grüning](https://github.com/bgruening) who have been encouraging of the development of Galaxy tools outside of the bioinformatics field.

In situations where one tools is not sufficient I think there is scope to create recipes for use with other tools. For example time series analysis in Galaxy should have a 'sister'-recipe for use with NextFlow. If you are interested in doing this. Please get involved with the [Galaxy computational chemistry team](https://github.com/galaxycomputationalchemistry).

# Papers about pipelines

## Open Access

* Jeremy Leipzig, A review of bioinformatic pipeline frameworks, Briefings in Bioinformatics, Volume 18, Issue 3, May 2017, Pages 530–536, https://doi.org/10.1093/bib/bbw020
* Fjukstad, B. & Bongo, L.A. Data Sci. Eng. (2017) 2: 245. https://doi.org/10.1007/s41019-017-0047-z

## Preprint (Not yet peer-reviewed)
* Reproducible Data Analysis Pipelines for Precision Medicine Bjørn Fjukstad, Vanessa Dumeaux, Michael Hallett, Lars Ailo Bongo bioRxiv 354811; doi: https://doi.org/10.1101/354811

# A list of pipeline software for the computational sciences
Personal views. Please submit an issue/PR to improve this list

1. Galaxy. Existing tools, workflow and available for public use. Great because much IT complexity can be hidden from the user and it just works.

1. KNIME. Desktop interface and can connect to RDKIT.

1. Common Workflow Language.

1. NextFlow. Excited about this one. Data-driven computational pipelines
