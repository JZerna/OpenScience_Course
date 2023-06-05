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

The paper [Good enough practises in scientific computing](https://doi.org/10.1371/journal.pcbi.1005510) by Greg Wilson et al. (2017) is a guideline for making your workflow reproducible.

Reproducible analysis is all about making it easy for yourself and for others to understand what you have done, to repeat your analysis, to tweak your analysis, and to avoid digital clutter. Following all these recommendations might seem like a skyscraper of work at first, but it is most likely the only way to say goodbye to the phrase "Your closest collaborator is yourself six months ago but you don't reply to email.". Structured and clean workflows are attractive but often hard to implement, because one does not know where to start. This is a boiled down version of what the paper describes and a reminder of what is important for each aspect:

![Figure showing good enough practises in scientific computing](Images/Good_enough.jpg)

Working with Github, R, and RMarkdown

A workflow that we can recommend from personal experience is a workflow with Github, R, and RMarkdown (see Figure below).

1. In the beginning of your project, your set up a repository using Github, which is the environment your files will be in.
    * You can either set it to private or to public.
    * You can invite specific people to collaborate on this repository.
2. On your local PC, you have your data, your analysis scripts, your manuscript file, your figures, and any additional files such as supplementary materials, slides, etc.
    * Any file that you create over the course of the project will be synchronized with your Github repository.
    * This can be done using Git in R or Github Desktop or any other GUI such as Visual Studio Code.
3. Your data has ideally been collected with a secure and multi-functional software such as REDCap.
    * REDCap automatically generates a codebook for you to accompany your data and clarify any variable names and scales.
    * If your have very large data sets, e.g. EEG or fMRI data, the file size will exceed the limit set by Github. In that case, you have your files on your local PC only, and you will upload them to a repository such as OSF for others to access.
4. Everyday before you start working on any files, you synchronize the repository on your local PC with the repository on Github.
    * This is called a Pull.
    * Any changes that your collaborators have implemented while you were gone will be synchronized.
5. Each change that you make to your files will be set in stone with a comment describing what you changed.
    * This is called a Commit.
    * Each commit is a version of the file that you can come back to if you wish to. Smaller commits are therefore recommended.
6. If you have committed changes to one or more files and you would like the repository on Github to reflect those changes, you synchronize the repository on Github with the repository on your local PC.
    * This is called a Push.
    * If a collaborator now makes a Pull, they will have the most recent version of every file with the changes you made.
7. Should you ever need to work on the same file as your collaborators (e.g. one person writes code for the instruction at the beginning of the paradigm, the other implements the feedback after the task), you can create a Branch.
    * A Branch is a copy of the repository, in which you can make changes and Commits and Pushes.
    * As soon as your work is done, you can request a Merge (or do it yourself if you are the creator of the repository).
    * A Merge checks for conflicts between the files of the main Branch and the child Branch.
    * If there are no conflicts, both Branches are fused into the main.
    * If there are conflicts, you can resolve them one by one, deciding which lines of code to keep from which Branch.
    * This method only works with raw text or code files, while file types such as png, docx, or pptx cannot be resolved piece by piece, so you have to settle on the entire file from one of the Branches.
8. By using RMarkdown, the results of your analyses, including any generated figures, are automatically updated when you recompile the manuscript. This way, your manuscript is always up to date and you avoid typos in result reporting.
9. If it isn't public already, you should make your repository public when you submit your manuscript to a journal. Make sure it does not contain any unnecessary files (personal communications, old meeting notes, etc.).
10. Any reviewer or interested researcher can now copy the entire repository to their own PC and run the analyses, because the folder and file structure is exactly the same as it was on your PC.

![Figure showing our recommended workflow](Images/Workflow_Reproducible.png)

Benefits of this workflow:

- **Version Control**: You can always go back to any version of the file that you have defined through a Commit. If you have deleted a code chunk by mistake or need a previous string of thought from the manuscript, simply go to Github and choose the version you would like to go back to.
- **Collaboration**: No more sending files back and forth. Everyone is always up to date (given that they are conscientious Push-and-Pull-people).
- **Backup**: If you accidentally delete a file, a folder, or your PC crashes, your work safe and sound in your Github repository.
- **Device independence**: If you want to work on something in your repository from a different device, simply clone the repository on this device and Push and Pull from there.
- **Honesty**: Every step of your work is traceable, so it is much harder to tamper with the evidence.
- **Contribution Tracking**: In case there are any conflicts about the order of authorships, you can use the contribution overview provided by Github to check the amount of Commits and added/removed lines of code per contributor.
- **Reproducibility**: With very little effort, anyone who wants to reproduce your work (even if it is yourself in a year from now) can do so. All files are in place.

Further resources that you can refer to as needed:

- This 1h 51m workshop by Mine Çetinkaya-Rundel is very good, so if you have the time please check it out [here](https://www.youtube.com/watch?v=fwZqVvHaA0M&feature=youtu.be).
- This 1h 48m workshop shows you how to integrate Git(hub) and R(Studio) [here](https://www.youtube.com/watch?v=Cn-72tbRNFc).
- For all those seeking to improve their R skills, this online course is completely free. It provides step by step explanations for all things R (including R markdown), along with a playlist on Youtube. You can look at all lessons at any time, no need to complete a lesson to unlock the next. Learn [here](https://psyteachr.github.io/msc-data-skills/repro.html).
- This checklist on Github serves as an anchor for checking whether your own research is reproducible. Find it [here](https://github.com/datacarpentry/rr-intro/blob/gh-pages/checklist.md).

 
---

# Preregistration

---

# Replication Research