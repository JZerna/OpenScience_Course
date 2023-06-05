# Handbook for the Open Science course of the MGK CRC940

## Chapters

- [Introduction](#introduction)
- [Open Science](#open-science)
- [Open Access](#open-access)
- [Open Data, Materials, and Code](#open-data-materials-and-code)
- [Reproducible Analysis](#reproducible-analysis)
- [Preregistration](#preregistration)
- [Replication Research](#replication-research)

---

# Introduction

The structure of this workshop is loosely based on [Seven easy steps to Open Science: An annotated reading list](https://doi.org/10.1027/2151-2604/a000387) by Crüwell et al. (2019).

It is a very good overview of the different aspects that we will cover, and you will find the papers they refer to in the subsections of this course.

You are free to read the Crüwell paper as an introduction or dive right into the subsections. You can even save it for last, as a course summary if you will.

The subsections [Open Science](#open-science), [Open Access](#open-access), [Open Data, Materials, and Code](#open-data-materials-and-code), [Reproducible Analysis](#reproducible-analysis), and [Preregistration](#preregistration) are compulsory course elements, while [Replication Research](#replication-research) is an optional subsection for you to look into if you are interested. We deliberately left out the seventh step, Teaching, in order to make space for the other issues that are more relevant to you right know.

---

# Open Science

Open Science

A good introduction to Open Science gives the paper by Munafó et al. (2017): [A manifesto for open and reproducible science](https://doi.org/10.1038/s41562-016-0021).

The illustration below (taken from the paper by Munafó et al.) illustrates the concept of Open Science well. It shows the deductive scientifc process and - in red - the threats to the quality of this process. Open Science aims to eliminate these threats, thereby ensuring scientific quality. The cyclic character of the illustration already gives you an idea of one of the most challenging aspects of Open Science: It won't be enough to tackle single threats one by one, you need to address them all. Luckily, many Open Science practises such as preregistration address multiple threats at the same time. And yet, preregistration is one of the practises that is quite easy to implement because it is all in your hands and no one can stop you. Practises that address publication bias are harder to implement because we are still very dependent on publishers for getting our peer-reviewed papers out in the world.

![Figure from Munafó et al. 2017 showing the research cycle and which threats to scientific transparency can arise during each phase](Images/Cycle.png)

You will get to know the most important Open Science practises throughout this course, so you can get a more in-depth understanding of the motivation behind each practise, tips and resources for how to implement them, and future challenges that have yet to be solved.

Further resources that you can refer to as needed:

- The Open Science Initiative of the faculty of psychology (OSIP) offers monthly meetings, information, and discussion. Sign up [here](https://tu-dresden.de/mn/psychologie/die-fakultaet/open-science?set_language=en).
- Simine Vizire wrote an article in 2018 about the implications of the credibility revolution. It is a good introduction to Open Science, as she paints the bigger picture of how those seemingly disadvantageous practices benefit science in the long run. Read it [here](https://doi.org/10.1177/1745691617751884).
- Mallory Kidwell and colleagues wrote a paper in 2016 about how much the badge system of Psychological Science has been contributing to the prevalence and quality of open data. Read it [here](https://doi.org/10.1371/journal.pbio.1002456).
- Slides and audio recordings for an introduction workshop on open science by Xenia Schmalz can be found [here](https://osf.io/7sxkg) (why do we need open science, registered reports and preregistration, open research workflow with the open science framework, accessing papers, FAIR data, open science in action).


---

# Open Access

This paper by Jon Tennant et al. (2016) on [The academic, economic and societal impact of Open Science](https://doi.org/10.12688/f1000research.8460.3) provides great insight into the current scientific system. Don't be discouraged, almost two thirds of it are references and appendices.

Open access refers to the strive of making scientific knowledge freely available to anyone, without paywalls or regional restrictions. Thanks to expensive contracts between SLUB and publishing houses, you as a member of the TUD have access to a large portion of journal articles out there. But you have probably also been in a situation yourself, where you were in the middle of a literature search and had a highly interesting abstract in front of you, only to see that the full pdf can be purchased for the slim price of 35.99$. In some cases, authors cannot even freely access the final typesetted version of *their own* paper.

The current, very flawed system looks like this:

![Figure showing the conservative model of scientific publishing](Images/OA_Closed_Access.jpg)

The system is changing thanks to a lot of pressure by activists of the scientific community, but it is changing slowly, and many established and new journals are trying to profit from this change by simply charging fees at a different step in the process under a different name.

There are different types or 'routes' of open access publishing. There is the Gold Open Access model, where you (or hopefully your institution) pay an article processing charge (APC) to the journal in order to make it freely available to the public. The APC can range from 2,000$ to 10,000$ depending on the impact factor and lack of guilty conscience of the journal. And keep in mind that this only to make your article open access, your institution still has to pay to access all the other non-open-access articles that have been published in the past. And then there is the Green Open Access model, where you upload the final article in a repository in order to make it freely available to the public after a certain amount of time, usually six months.

![Figure showing the Gold model of scientific publishing](Images/OA_Gold_Access.jpg)


![Figure showing the Green model of scientific publishing](Images/OA_Green_Access.jpg)

The three graphics were taken from [here](https://open-access.net/en/information-on-open-access/open-access-strategies).

Further resources that you can refer to as needed:

- The SLUB is currently developing an Open Access search engine called [B!SON](https://service.tib.eu/bison/), which aims to recommend suitable journals based on the input of title, abstract, and references of your manuscript.
- An overwhelmingly long sitemap of resources can be found on the Open Access information platform [here](https://open-access.network/en/translate-to-english-sitemap). Choose between the history of Open Access, repositories, Open Access for different types of media, positions on Open Access, legal issues in different countries, etc.


---

# Open Data, Materials, and Code

This paper by Olivier Klein et al. (2018), titled [A practical guide for transparency in psychological science](
https://doi.org/10.1525/collabra.158), does exactly what it says.

Sharing your data (and your analysis scripts) openly in safe repositories is not only intended to enable the reproduction of your analyses but also the aggregation of data sets from all over the world for powerful meta-analyses. However, many researchers are hesitant when it comes to open data because they are concerned about copyright issues, having missed a mistake of their own, accidental violations of privacy, etc. It is important to address these concerns in order to move forward with the open data movement.

This figure is adapted from the talk by Felix Schönbrodt (see below) and represents some of the core concerns and values that need to be balanced in the open data movement, with possible solutions/tips in the grey box inbetween:

![Figure showing the value conflicts when sharing data publicly](Images/Values.png)

Further resources that you can refer to as needed:

- This compact article by the University of Calgary briefly describes what each licence type means, read it [here](https://libanswers.ucalgary.ca/faq/200582).
- This tool takes you through your goals step by step to find the licence type that is right for you. Find it [here](https://chooser-beta.creativecommons.org/).
- This website by the Open Knowledge Foundation provides a compact framework of Open Data. You can navigate to different steps in the Open Data research process using the hamburger in the upper left corner. It also contains a nifty glossary of all the terms associated with Open Data. Find it [here](http://opendatahandbook.org/guide/en/introduction/).
- This website allows you to search for a repository that suits your needs. You can filter by subject, country, licenses, restrictions, standards, etc. Find it [here](https://www.re3data.org/).
- This checklist gives you an idea of whether your data conforms to the FAIR principles [here](https://satifyd.dans.knaw.nl/).

---

# Reproducible Analysis

---

# Preregistration

---

# Replication Research