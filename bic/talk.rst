
.. Teaching FMRI slides file, created by
   hieroglyph-quickstart on Sat Jan 11 20:01:57 2014.

Teaching fMRI
=============

.. consider starting with some questions?
.. What kind of researchers do we want to produce?
.. What kind of researchers are we producing now?
.. What does a bad neuroimaging researcher look like?
.. What does a good neuroimaging researcher look like?
.. How do we get from here to there?

Teaching fMRI
-------------

By JB Poline and Matthew Brett

Why - What - How
----------------

* Of the three - the why is the most important
* Of the three - the what is the one that evolves fastest 
* Of the three - the how is the most delicate

Why ? 
==============

Why ?  
--------------

* We make fewer mistakes
* We work more efficiently
* We think more clearly - enabling us to develop new ideas
* We collaborate better (and more efficiently)
* We allow others to build on our work

Mistakes
--------------------

The "Mistakes" argument : an unpopular topic.

- Ioannidis 2005
- Anatomy of an Error
- The Left/Right issue
- The ADHD 1000 connectome

.. Ioannidis : although many may not be convinced, the arguments are
.. Add reference to Simmons analysis? http://sciencereview.berkeley.edu/article/false-positives/
.. Glenn Begley and Lee Ellis "Raise standards for preclinical cancer research" Nature 483 (2012)
.. L/R
.. scripts contained an error - new release

Efficiency
--------------------

The "Efficiency" argument: 


- Can I find out if there's a mistake?
- How long to find out that there's a problem in the analysis ?
- Knowing your tools - knowing them well enough to be fluent
- learning the right tools  
   * the difference between walking or on a good motorbike

Clarity / Empowering
--------------------

* Knowing how to create the tools will free your mind for new ideas. 
* New tools are constantly emerging - but they never are exactly what's needed
* Constructing the tool may take time - it will save some. 

.. Again : we need to empower students and researcher with the freedom to analyse the data the way they want, rather than having to re-use scripts and be constraint by those

Collaboration
-------------

A new era for collaborative science

- *Specialization* and rapid advances of science require *collaboration*
- Collaborations today are mostly "internet" 
- Internet collaborations allow a new type of science
    * neurosynth, neurovault, brainspell, brainspell, neurobureau hackathon, etc
    * shared tools and data are growing fast 
    * decreasing the social barriers and increase work 
- from social coding to social science ? from open source project to open source science ?

.. more or more open data - from post office to internet
.. numpy competes with Matlab efficiently
.. is the era of close science giving away to the era of open science, as did software development?
.. The idea of open-science as social science - as open source is social coding.
   Radical improvement in quality and productivity.
.. Science as a social activity.  That is, that science is best and most
   efficiently done by constant checking and improvement by many eyes.
   http://en.wikipedia.org/wiki/Linus%27s_Law (first law on that page).
   We'll get there when we share a language and tools to communicate the
   analysis and data in a fluid way.
.. bitkeeper from Sun // Linus Torvalds git 
.. example of analysis done with a Chinese statistician
.. data being reviewed : nature initiative

Reproducibility
---------------

Building things such that they can be built upon

* Accountability
    - Working such that the next post-doc will need less than a week to start progress 
    - Working such that others in the community can check / build upon

.. ask audience how long a post-doc needs to get up and running analyzing
   another post-doc's data at the moment.  How about meta-analysis within lab?

* Openness 
    -  Working such that my colleague can check my work



What?
=====

What?
-----

- Code / script development 
- Applied math
- The collaborative tools

Code / script development 
-------------------------

- The "Loni" fantasy
- The current tools : between brainvoyager (closed) and nipy (requires programing skill) ?
- Example: I need to do data cleanup - but would like to down-weight rather than eliminate
- Testing ? 
- Visualization 
- Some elements of distributed computing 

What - Applied math
--------------------

* Applied statistics 
* Signal processing
* Image analysis 
* Machine learning (supervised / unsupervised)
* Graph Theory / ...

The collaborative tools 
-----------------------

- For myself first - for others
- Git / Github / google docs  

In the near future : 

- Semantic web technologies 
- Databasing and Datasharing techniques

How ?
=====

.. Consider putting PNA experience above.  As in something like - we concluded
   that we needed to teach students how to work with their data from the raw
   files up to the final analysis.  We wanted to combine teaching about the
   principles of analysis with practical experience of implementing toy analyses
   and exploring them. Examples of PNA notebooks.

How ?
-----

- Feedback from our course
- Motivate with practical analysis
- Find and make teaching material

What worked - what didn't  
------------------------------------

* We were young and ambitious 
    - underestimating the task + goal too broad 
* We relied on students to have more background than they did  

* The IPython notebook helped greatly
   - but makes teaching workflow harder 

.. I think the IPython notebook pointed us at something we really wanted to be
   able to do, but it also made us some problems - we didn't teach workflow
   properly and it was relatively hard to write exercises.  Need to work out a
   better flow.  Working with Jonathan on this.

* Details : curse and blessing - more curse than blessing 

.. _The course link: http://practical-neuroimaging.github.io/

http://practical-neuroimaging.github.io/


Motivate with practical analysis
--------------------------------

* PNA experience
        - From a 10 * 2 hours to 27 * 2h + ...
        - 47 IPython notebooks

* Make the teaching close to the research project
* Spend enough time that programing an analysis will be a confort zone


Find and make teaching material
-------------------------------

* Get the right material from online, many IP notebooks are available !
        - there is not enough time / teaching resources : some things must be learnt online. 

* Join forces with stat / CS / other departments 
        - development of courses that combine theoretical and coding aspects
        - BIDS


What kind of curriculum ? 
------------------------------------

* Several courses with dependencies:
        - Shell / OS installs - Introduction to Python / IPython 
        - Toolbelt of the collaborative computational scientist / Workflow (Git, Github, ...)
        - Toolbelt of applied mathematics / statistics 
        - The analysis pipeline (preprocessing to GLM) [rely on others to teach GLM?]
        - Other Neuroimaging packages : ML / MV-Connectivity 

.. two first components should be taught by BIDS
.. # 3 could be in conjunction with stat / engineering / neuroscience
.. 4 and 5 really specific

Conclusion
----------

* Make it so.  What kind of teachers ?

.. image:: ../pics/darth.png
   :width: 70%
   :align: center

.. My point of that graphic in the Havana talk is that we the current teachers
   have the history of the old system in us, so we are the Darth Vaders.  We
   need to teach our students to be the Luke Skywalkers instead.

