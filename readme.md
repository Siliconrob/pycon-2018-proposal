# PyCon 2018 Proposal

## Title
**Map it with Python! Intro to GIS and Python mapping modules.**

_Guidelines: Puns, jokes, or “hooks” in titles are okay, but make sure that if all someone knew was the title, they still would have some idea what the presentation is about._

## Description
Maps showing all kinds of data are powerful tools that we use in various parts of our lives every day. Python is well-equipped to handle spatial data and has plenty of libraries to help you perform spatial analysis and create beautiful maps. In this talk, we'll discover the fascinating world of GIS by covering topics like projections and coordinate systems, best practices for map making, static maps verses web maps, and how Python can be used to solve spatial problems and visualize spatial data.

_Guidelines: Both your title and this description are made public and displayed in the conference program to help attendees decide whether they are interested in this presentation. Limit this description to a few concise paragraphs._

## Who and Why (Audience)
This talk is for anyone with a curiosity of how maps are made and how Python can be used for spatial analysis and map making. No previous GIS knowledge is required, but a basic understanding of Python is expected. An interest in maps is a must!

After the talk, attendees will have a broad understanding of GIS and know about several Python libraries that can be used to do GIS. If they are already familiar with Python, they will be ready to answer spatial questions using the tools outlined.

_Guidelines: 1–2 paragraphs that should answer three questions: (1) Who is this talk for? (2) What background knowledge or experience do you expect the audience to have? (3) What do you expect the audience to learn or do after watching the talk?_

_Committee note: The “Audience” section helps the program committee get a sense of whether your talk is geared more at novices or experienced individuals in a given subject. (We need a balance of both lower-level and advanced talks to make a great PyCon!) It also helps us evaluate the relevance of your talk to the Python community._

## Outline
1. **Let's talk about maps** (3 minutes)
    * **Maps are Cool, Useful, and Beautiful** I've always loved looking at maps, which sparked my interest in GIS.
    * **Story Telling with Maps** Maps can tell long and interesting stories spanning spatial and temporal dimensions.
    * **Maps in Modern Times** On our phones, computers, everywhere. We use maps every day to choose destinations and get directions.
    * **Historical Spatial Analysis** Maps have been used for hundreds of years to solve spatial problems.

2. **Hasn't everything already been mapped?** (5 minutes)
    * **There are infinitely-many maps to be made** It is not possible for all maps to be made. GIS departments exist in many industries keeping spatial data and producing maps. Let's make a distinction between reference maps and thematic maps.
    * **Reference Maps** Reference maps are used for reference, they show what is actually there. Several examples will be given. I'll give Planet basemaps an example, since Planet uses Python to find the best satellite images and stitch them together.
    * **Thematic Maps** Thematic maps have some theme on top of a reference map. Several examples will be given.
    * **Non-Earth Maps** There are also maps of other planets and galaxies, and even fictional places.

3. **What is GIS?** (10 minutes)
    * **Used to Answer Spatial Questions** How do we get to restaurant x? What is traffic like right now? Where can I go to see the total solar eclipse? These are spatial questions we ask every day.
    * **The GIS Stack** The tools you need to do GIS - Software that allows you to read, modify, save, and display spatial data, a database or flat data files, and hardware such as powerful computers, GPS units, and large-format plotters.
    * **Vector and Raster Data** The two kinds of spatial data. Vector for isolated objects, Raster for continuous surfaces.
    * **Projections and Coordinate Systems** The Earth is a sphere, yet our maps are flat. How do we deal with this?

4. **Python Mapping Libraries** (10 minutes)
    * **Mapping Applications** There are desktop mapping applications like the proprietary ArcMap and the open source QGIS, both of these have Python APIs built right in (which is how I got my start with Python). For our purposes, the combination of Python and Jupyter Notebook will be a perfectly suitable mapping application.
    * **GDAL and OGR** All spatial analysis tools use these two old, tried and true libraries, written in C.
    * **Our Spatial Problem** Let's use Python to answer a spatial question! In what cities in Oregon can I see the total solar eclipse? I'll demo finding the answer with the following open source libraries:
    * geopandas - Extends the datatypes used by pandas to allow spatial operations on geometric types. We will use it to read, examine, analyze, and plot our spatial data. Depends on fiona, a Python wrapper for OGR.
    * matplotlib - a Python plotting library which produces publication quality maps and diagrams in both static and interactive formats. We'll use it to customize our maps. We'll also use seaborn, a Python visualization library based on matplotlib.
    * shapely - a Python package for manipulation and analysis of planar geometric objects.

5. **How to Lie with Maps and Conclusions** (2 minutes)
    * **Maps are models** All maps are inherently wrong because they leave out some variables. Maps can also be used to intentionally mislead.
    * **Conclusions** Now you know about GIS and Python mapping libraries. Happy mapping!

_Guidelines: The “outline” is a skeleton of your talk that is as detailed as possible, including rough timings for different sections._

_Committee note: The outline is extremely important for the program committee to understand what the content and structure of your talk will be. We hope that writing the outline is helpful to you as well, to organize and clarify your thoughts for your talk! The outline will not be shared with conference attendees._

## Additional notes
-----

* **Speaker public speaking experience**

I am faculty at the University of Washington in the Masters in GIS program (3 years) and the Python certification program (1 year). Through these programs, I have taught multi-day on-site workshops, weekly on-site classes, and fully online classes on GIS and Python. I am involved in my local GIS and Python communities by co-organizing Maptime Seattle and PyLadies Seattle. I have enjoyed presenting talks and tutorials throughout my career at conferences, user groups, PyLadies Seattle, and Maptime Seattle.

* **Speaker subject matter experience**

I am a GIS professional and Python advocate with 10+ years of experience working in the public and private sectors and education. As an organizer of MapTime Seattle, I promotes public open source adoption of GIS, while blogging for the Python Software Foundation and attending PyLadies Seattle to assist and build the Python community and support underrepresented groups in technology.  

* **Experience presenting similar materials**

*Links to recordings and slides:*

Intro to GIS for Maptime Seattle (2017): http://maptimesea.github.io/img/IntroToGIS_MaptimeSea_20170906.pdf

A simple GIS workflow in Python and R for the CUGOS Spring Fling (2017): https://github.com/christyheaton/Cugos_SpringFling_2017

*Videos of me speaking:*

Data Disarray for UW GIS Day 2015: https://www.youtube.com/watch?v=SYCi5z05hu4

Networking for Interesting Career Opportunities for UW GIS Day 2014: https://www.youtube.com/watch?v=z-q4znBqokw&t=1s

* **Specific needs or special requests**

I have no special requests or needs.

_Guidelines: Anything else you would like to share with the committee:
Speaker public speaking experience.
Speaker subject matter experience.
Have the speaker(s) given this presentation before elsewhere?
Links to recordings, slides, blog posts, code, or other material.
Specific needs or special requests — accessibility, audio (will you need to play pre-recorded sound?), or restrictions on when your talk can be scheduled._
