# Reproduce-published-Galaxy-analyses

This training will demonstrate how to reproduce analyses performed in the Galaxy framework. Before start with the hands-on part, I would like to give you some information about Galaxy.

Galaxy is a scientific workflow, data integration and data analysis and publishing platform. Galaxy is an open-source platform for accessible, reproducible, and transparent computational research. While Galaxy was started to allow non-bioinformaticians to analyze DNA sequencing data, it nowadays enables analysis tasks of many different domains including machine learning, ecology, climate science and omics-type of analyses. Galaxy is easy to use because it is accessible via a web-browser and provides a graphical user interface which enables access to pre-installed tools and large computational resources. In Galaxy, all analyses are stored in so-called histories. The history keeps track of all the tools, tool versions and parameters that were used in the analysis. From such a history, a workflow can be extracted; this workflow can be used to easily repeat the analysis on different data. Both, histories and workflows, can either be shared privately with colleagues or publicly, for example as part of a published manuscript.

For more background information about Galaxy, have a look into the Galaxy publication (Afgan et al. 2018). In depth technical details about technologies that enable reproducible analyses within Galaxy are described in Grüning et al. 2018.

Agenda
In this tutorial, I will cover:

What does Galaxy look like?
Create a history and load data into it
Import and run a Galaxy workflow
Inspecting the analysis history
Manipulating the analysis
Additional Exercise: Import a published analysis history and explore it
What does Galaxy look like?
Many different Galaxy servers exist. Some are public, some are private, some focus on a specific topic and others like the usegalaxy.* servers cover a broad range of tools. To reproduce published results it is highly recommended to use the same Galaxy server that was used in the original study. In the case that this was a private server that is not accessible to you, you might want to use one of the main Galaxy servers: UseGalaxy.org.au, UseGalaxy.eu, UseGalaxy.fr, UseGalaxy.org. To learn more about the different Galaxy servers visit the slides: options for using Galaxy. The particular Galaxy server that you are using may look slightly different than the one shown in this training. Galaxy instance administrators can choose the exact version of Galaxy they would like to offer and can customize its look to some extent. The basic functionality will be rather similar across instances, so don’t worry! In this training I will use the European Galaxy server on which the original analysis was performed and shared.
