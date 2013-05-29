Web development best practices
==============================

## License ##

This work is licensed under the Creative Commons Attribution-ShareAlike 3.0 Unported License. To view a copy of this license, visit http://creativecommons.org/licenses/by-sa/3.0/.

## Notice to the reader ##

This document stores my thoughts so most of the conclusions are subjective, althought most of them are based on articles linked here and there.

Any developer should consider personally if agree or not each conclusion written here. Read further about each topic and make your own decissions.

Ensure to read news often and evolve your best practices manual continuosly as I am trying to do here. Tomorrow something may have changed, or nothing, or everything.

## Structure of this document ##

This document has several parts which group topics and provide resources to introduce them. Each topic has two special subsections:

- *Dilemma*: A decision that must be done. Introduces the existing solutions.
- *Conclusion*: The decision and arguments for how and why. If needed, a new option is created here, either from scratch or by merging some of the existing ones.

Part 1: The development process
===============================

Developing a website or web app is, essentially, developing software. The human knowledge about the software development process has evolved during the years, looking for processes that improve productivity and quality. It's important to study this evolution and conclude what we will use on our daily practices.

There are lots of articles and books to read about this topic. A good quick start point, as overview, is [this article on wikipedia](http://en.wikipedia.org/wiki/Software_development_process), and its references.

Reading about this topic raises to the foreground the benefits of following a *software development method*.

## The software development methodology ##

[This slide show written by Hamid Faridani](http://www.gtislig.org/HamidFaridani_GuideToSelectingSWMethodologies_SOC_PDD_20110305.pdf) introduces well the concept of *software development methodology* and some existing key methodologies. It also gives keys to decide the methodology to be used for a concrete project, but before taking

Notice the slide show presents two approaches:
* The classical ones, also known as *heavy*.
* The newer ones, also known as *light* or *agile*.

Notice the turning point in the approaches is [the agile manifesto](http://agilemanifesto.org/), the base of all agile methodologies.

TEST DRIVEN DEVELOPMENT

### Dilemma ###

Choose a development methodology.

- Classical or heavy methodologies
    * Waterfall
    * Unified Process
    * Spiral
- Light or agile methodologies
    * Scrum
    * Xtreme programming (XP)

First, we must decide

Light vs Heavy methodologies.

### Conclusion ###

Choosing the right software development methodology depends on each project.

The agile methodologies seem to be the better for web development for the following reasons:

1. 

Key project characteristics considered:
- Size of the project team
- Rate of expected change 
- Primary project goal
- Requirement Management
- Project Communication
- Customer Relationship 
- Customer Organizational Culture Project Characteristic Analysis
General comments:
- A decision tree analysis is used to compare various 
methodologies
- They do not constitute parts of one large decision tree- it is a 
one-dimensional analysis
- The ranking of the seven characteristics would have to be 
done by the project manager and architect with the assistance 
of the project leaders.
- The results are not meant to be a substitute for sound project 
management and technical direction but as guidelines for 
practitioners. 
- The methodology used can also depends on the customer 
request

# Topics to write about #

## Software design patterns ##

MVC vs MVA: http://www.palantir.com/2009/04/model-view-adapter/
MVA != [MVP](http://en.wikipedia.org/wiki/Model%E2%80%93view%E2%80%93presenter

## Software development process ##
Test Driven Development
http://c2.com/cgi/wiki?TestDrivenDevelopment
wikipedia?

## Programming principles ##

Don't Repeat Yourself - http://programmer.97things.oreilly.com/wiki/index.php/Don't_Repeat_Yourself
Keep It Simple Stupid - http://people.apache.org/~fhanik/kiss.html
You Aren't Gonna Need It - http://en.wikipedia.org/wiki/You_Aren%27t_Gonna_Need_It

Abstraction principle <=> Rule of three

## Programming language ##

[the book *learning node*, by Shelley Powers](http://shop.oreilly.com/product/0636920024606)
[the article *Node: References and resources*, by Shelley Powers](http://tech.burningbird.net/article/node-references-and-resources)

Interaction design & User experience: http://www.interaction-design.org/
* The development process
    * Common tasks, phases, activities, or processes
        * Planing, Analysis, objective/requeriments definition or Planing and Analysis
          * Objectives definition
          * Identify the user types and its access limits to the app
          * Requirements list
        * Design
          * Content design
            Semantic web - http://schema.org/
            book: Information Architecture for the World Wide Web - O'Reilly
              * Sitemap
              * Definition and categorization of contents
              * Data model design
                  * conceptual design
                  * logic design
                  * implantation of the database
          * Visual design
              * wireframing
              * iterations design
              * graphics design
        * Implementation
          * back-end
          * front-end
        * Test, Verification or Evaluation
        * Optimization
        * Deploy
    * choosing the software development method. 
    * Enhancing the methodology with support disciplines
      http://www.gtislig.org/HamidFaridani_GuideToSelectingSWMethodologies_SOC_PDD_20110305.pdf
      

* Project structure

