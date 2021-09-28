---
title: "Final project"
date: 2021-09-17
---

In this project, you'll be applying the data science skills that you've learned to prepare a short, reproducible, exploratory analysis of a dataset.  

# Data #

The ideal dataset for this project is a relatively large, complex dataset from your field.  This might be data for a project that you've worked on, some open data published along with a paper in your field, or a widely-used dataset such as the General Social Survey.  


# What to submit #

When you complete this project, turn in the following elements to me by email:  

- a link to the GitHub repository for your project
- a PDF of the project report
- a link to the data, if for some reason it can't be included in the GitHub repository

It's okay to use a private GitHub repository, so long as I'm added as a collaborator.  

A readme in the repository should explain clearly what steps to take to reproduce the full analysis pipeline and typeset the PDF from the Markdown, R Markdown, or LaTeX source. 

Ideally, you've set up a Makefile to run the entire analysis and generate the PDF of the report with a single command, and also used GitHub Actions and Pages to automatically reproduce the analysis and make it publicly available.  But, because these topics are covered in the last few weeks of the term, I regard them as stretch goals.  


# Report #

The report for your analysis is structured somewhat like a traditional scientific paper:  introduction, methods, results, discussion.  But the content of these sections will be somewhat non-traditional.  

The total length of this report should be 3,000-5,000 words (not including references). 

Introduction
: As usual, motivate your topic, give some background, and clearly state the research question.  
    In addition, incorporate answers to the reflexivity questions from the labs:  what did you already know about this topic before starting to work on the project, what did you expect to find, who's impacted by this topic and how are you connected to them.  

Methods
: The methods section should focus on the data, and in particular should include a fairly detailed (~1,000-word) narrative of the journey that the data travelled to get to you.  Here's the list of things we came up with during our discussion of the idea of data journeys:  
    - making assumptions explicit
    - accessible to many audiences
    - acknowledging limits of sample
    - how these limits change analysis strategy
    - justifying choice of methods / other possible methods
    - [authors'] qualifications
    - resources and capabilities [and how they enabled/prevented different kinds of data and analysis]
    - version control as lineage
    - reflection on ethical issues
    - research assistants — who were they and what did they do
    - population affected by study's results
    - researchers' social location and background
    - clinical or policy implications but [often] no follow-through
    - [professional status of] researchers — PI, student, postdocs, etc.
    - what counts as "success"
    - tensions between different notions of "success" and how [they're] managed
    - disagreements within research team

    Beyond the methods covered in this course — which, after all, are focused much more on preparing and maintaining your data than on analysis — you're welcome to use any analytical techniques with which you're comfortable.  

Findings
: As usual, your findings should be framed as phenomena (in the sense of the Brown chapter) rather than causal claims, mechanisms, or theoretical results.  
    The first subsection of your findings should cover the most relevant elements from the EDA checklists to validate your data.  Be sure to identify and address limitations of your data for answering your research question.  (If you find that the data are not fit for purpose, it's okay to turn in a report that reaches that conclusion.  The discussion section can talk about how researchers in your field might collect data that could actually be fit for purpose.)  
    The second subsection can address your research questions.  Use visualizations along with or instead of tables.  Keep your visualizations close to the data.  For example, include both a scatterplot and a fitted regression curve.  

Discussion
: As usual, briefly (1-2 sentences) recap your major findings, then discuss limitations and directions for future research.  
    Resist the temptation to treat your findings as conclusive or as vindicating (or challenging) some larger theory.  Instead, emphasize the ways future research can improve our understanding of the phenomena:  how new data might be collected to mitigate the limitations of this dataset, how different kinds of data might complement the kind of data used here, and how further studies might trace out the scope of the phenomena found in this dataset.  
    Finally, come back to the reflexivity questions in the introduction.  Were your expectations met?  (Probably a mix of both yes and no; explain.)  What implications might your findings have for people affected by the topic?  How should these implications shape the trajectory of future research on this topic?  


# Feedback #

I'll give you feedback on the following areas: *[todo]*

