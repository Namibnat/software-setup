# Software Setup

## Purpose

Having successfully entered the marketplace as a beginner software developer I have learned a great deal about what it takes
to become a software developer.  I know many beginners find this incredibly hard, and one problem is the difficulty of having access to modern project development as it is done in industry.

I propose an open source project where we develop initially in sprints, with the distinct aim of building it with contributions
from new Python developers.

I suggest we have sprints every single weekend, perhaps on Saturday, where anyone can join and get helped towards contributing
one or more commits.


## Contributing

The main goal here is that members of the Python Namibia community are able to participate in the development of an open-source project.  However, I suggest that we welcome contributions from anyone, but anyone who is not a member of the community should be there primary to coach a Namibian developer in a pair-programming capacity to make commits.

If this works well, we could perhaps open up the scope to include developers from other communities that are in communities similar to ours, such as people from other African Python communities.

Any developer with more experience at setting up and running projects like this is welcome to help, make suggestions, etc, to help us
make this successful and to help teach best-practices.

Participation will not be limited to just writing Python code.  It will include writing tests, documentation, and the front end as well (Javascript, HTML, CSS).


## Proposed Project

These are the main ideas I have in point form:

- Build a website
- The website will allow users to join
- The goal of the site is to allow a 'recipe' approach to setting up software.  See the 'why' section below.
- Each 'recipe' for software set-up will be very specific, for example:
  - Operating system: Ubuntu 20.04.4 LTS
  - Programming Language: Python 3.9
  - Using: Poetry
  - etc, etc.
- The goal would be to have as complete a resource as possible for setting up any software of any version on any machine, given any number of requirements and conditions as possible.
- The software we'll have on here will include any open source software, regardless of language, etc.
- We can build web scrapers to find any recent updates to known software projects to alert users of the need for a new set of recipes.
- A voting system on recipes.
- Build onto this can be a forum, an app, an many other potential related ideas.
- A way to embed Youtube videos that describe set-ups in detail.


## What will be included

- A python django website
- Build in a docker container
- Using postgreSQL server, also hosted in a docker container
- An Apache server, hosted in another docker container
- A division between dev and productions site, as might be used in a proper modern context.
- A full test suite, and perhaps built using test driven development.
- Full documentation.
- Front end.  Perhaps using Vue.js?


### Why

This has been an idea buzzing around my head for a while.  I think many courses online, such as those found on Udemy,spend way to much time describing how to set up software in their course.  Same with book authors.  And, often when you're doing the course, you find some aspect of the set-up that just doesn't match your own desired software stack.

So, the idea is that those authors can simply point to our site for the set-ups.
