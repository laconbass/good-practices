Web development best practices
==============================

## License ##

This work is licensed under the Creative Commons Attribution-ShareAlike 3.0 Unported License. To view a copy of this license, visit http://creativecommons.org/licenses/by-sa/3.0/.

## Notice to the reader ##

This document attempts to address the topics with objectivity, but the conclusions are subjective.

Conclusions are my personal criterion, formed after hours of self-taught reading of books and articles, and my experience and knowledge on programming.

Any developer should consider personally if agree or not each conclusion written here. Read further about each topic and make your own decisions.

Ensure to read news often and evolve your best practices manual continuously. Tomorrow something may have changed, or nothing, or everything.

## Structure of this document ##

This document has several parts which group topics and provide resources to introduce them. Each topic has two special subsections:

- *Dilemma*: A decision that must be done. Introduces the existing solutions.
- *Conclusion*: The decision and arguments for how and why. If needed, a new option is created here, either from scratch or by merging some of the existing ones.

Part 1: The development process
===============================

Developing a website or web app is, essentially, developing software. The human knowledge about the software development process has evolved during the years, looking for processes that improve productivity and quality. It's important to study this evolution and conclude what we will use on our daily practices.

There are lots of articles and books to read about this topic. A good quick start point, as overview, is [this article on wikipedia](http://en.wikipedia.org/wiki/Software_development_process), and its references.

Reading about this topic raises to the foreground the concept of *software development methodology*.

### Conclusion ###

## The software development methodology ##

[This slide show written by Hamid Faridani](http://www.gtislig.org/HamidFaridani_GuideToSelectingSWMethodologies_SOC_PDD_20110305.pdf) introduces well the concept of *software development methodology* and some existing key methodologies. It also gives keys to decide the methodology to be used for a concrete project.

Notice the slide show presents two approaches: The classical ones, also known as *heavy*, and the newer ones, also known as *light* or *agile*. The turning point in the approaches is [the agile manifesto](http://agilemanifesto.org/), the base of all agile methodologies.

### Dilemma ###

Should i follow a software development methodology? Which one should i choose?

### Conclusion ###

Definitely, following a development methodology I will improve the quality of the development process and optimize my productivity.

The agile methodologies seem to fit better with web development for the following reasons:

* The nature of a web app is to evolve continuously, as the web does.
* (FREELANCE) The full process is done by small teams, often with only 1 programmer.
* Often, the client does not know exactly what she wants. This implies there will probably be changes during the development.
* To avoid wasting time, the client must be visited often to have feedback about the development progress.

The methodology used should depend for each project theoretically. As any of them are well known to me, seems better to define a mix of the existing agile methodologies and use it for all the projects, while i'm evolving my experience on the matter.

The methodology should focus on the teamwork, and be adapted to the size of the development team.

* Scrum. It puts the focus on the teamwork and the interaction with the client.
* Pomodoro Technique. It helps managing tasks and enhances productivity. Also helps to estimate the time that each task consumes.
* Xtreme Programming, its principles and philosophy are the day-to-day working basis of a good programmer.
* Test driven development is the best way to define objectives and reach them quickly.
    * PRINCIPIOS¿?¿?
    * TEST DRIVEN DEVELOPMENT

-----

The methodology should deal with the following:
* Project management: Tasks and time.
* Programming: principles, philosophy, and conventions.

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
