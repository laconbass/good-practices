My web development best practices manual
========================================

## License ##

This work is licensed under the Creative Commons Attribution-ShareAlike 3.0 Unported License. To view a copy of this license, visit http://creativecommons.org/licenses/by-sa/3.0/.

## Notice to the reader ##

This document attempts to address the topics with objectivity, but the conclusions are subjective.

Conclusions are my personal criterion, formed after hours of self-taught reading of books and articles, and my experience and knowledge on programming.

Any developer should consider personally if agree or not each conclusion written here. Read further about each topic and make your own decisions.

Ensure to read news often and evolve your best practices manual continuously. Tomorrow something may have changed, or nothing, or everything.

## Structure of this document ##

This document has several parts which group topics and provide resources to introduce them. Each topic has special subsections:

- *Dilemma*: A question representing a decision that must be done.
- *Conclusion*: The decision and arguments for how and why.

Part 1: The development process
===============================

Developing a website or web app is, essentially, developing software. The human knowledge about the software development process has evolved during the years, looking for processes that improve productivity and quality. It's important to study this evolution and conclude what we will use on our daily practices.

There are lots of articles and books to read about this topic. A good quick start point, as overview, is searching for [Software development process on Wikipedia](http://en.wikipedia.org/wiki/Software_development_process), and follow its references.

Prior to introduce the concept of *"software development methodology"* and the benefits of following one,  we will identify the common activities or sub-processes of the development process.

## Sub-processes of the software development process ##

### Planing
During this sub-process the primary task is define the *objectives*. Objectives are the features the software must have.

### Analysis
Given an objective, the goal is define the software requirements to accomplish it. To do that, analysts must keep in consideration the user types and its access limits to the app. This sub-process transforms *objectives* into *requirements*.

### Design
Given a *feature*, it's the moment to design how it's going to be implemented. Depending on the feature, several sub-processes are performed, each one producing as result different kind of *designs*.

#### Content design
Semantic web - http://schema.org/
book: Information Architecture for the World Wide Web - O'Reilly
* Sitemap
* Definition and categorization of contents
* Data model design
     * conceptual design
     * logic design
     * implantation of the database

#### Visual design
The action of designing the *User Interface (UI)*. This process implies several sub-processes: 
* Wireframing: The action of sketching the UI.
* Iterations design: The action of designing how the UI responds to the user input.
* Graphics design: The action of transforming *wireframes* onto a graphic design through art.

### Implementation
The writing of the code itself. On web development, *back-end* refers to the server-side code, while *front-end* refers to the client-side code. *Full-stack* refers to the whole application code. This sub-process transforms *designs* onto *features*.

### Test, Verification or Evaluation
This process ensures that the *features* meet the *requirements*. 

### Deploy
The action of deliver the software to the client.

### Upkeep and Optimization
This sub-process includes the tasks related to bug fixes and improvements on appearance or performance. 

## The software development methodology ##

[This slide show written by Hamid Faridani](http://www.gtislig.org/HamidFaridani_GuideToSelectingSWMethodologies_SOC_PDD_20110305.pdf) introduces well the concept of *software development methodology* and some existing key methodologies. It also gives keys to decide the methodology to be used for a concrete project.

Notice the slide show presents two approaches: The traditional ones, also known as *heavy* or *predictable*, and the newer ones, also known as *light* or *agile*. The turning point in the approaches is [the agile manifesto](http://agilemanifesto.org/), the base of all agile methodologies.

[This presentation by Eugenia Bahit](http://www.youtube.com/watch?v=W8CuRtCHWD8) (ES) explains the agile manifesto principles demonstrating the differences between predictable methodologies and agile ones, and shows the key existing agile methodologies: *Scrum*, *Kanban* and *XP (eXtreme Programming)*.

Notice that the presentation puts on the table the difference between predictable and agile methodologies: **the adaptability to changes**.

### Dilemma 1 ###

Should i use a predictable or an agile methodology for web development?

### Conclusion 1 ###

The agile methodologies seem to fit better for web development for the following reasons:

* The nature of a web app is to evolve continuously, as the web does.
* Often the full process is done by small teams, sometimes with only 1 programmer, or even 1 person.
* Often the client does not know exactly what she wants. This implies there will probably be changes during the development.
* Working close to the client on a daily basis produces a valuable feedback that avoids wasting time.

### Dilema 2 ###

There are lots of agile methodologies, but it seems *Kanban*, *Scrum* and *XP* are the best options as they are the most used. What methodology should i choose? The methodology should focus on the teamwork and be adapted to the size of the development team because sometimes I work as freelance, sometimes as a lone.

### Conclusion 2 ###

The methodology used should depend for each project theoretically, but the fact is that it depends more on the people on the developing team when using an agile methodology. This includes the client, designers and anyone who has something to do with the project, not only the programmers.

The fact is the key existing agile methodologies focus on different aspects of the process:

- **Kanban** focuses on optimizing the workflow, with 3 easy-to-apply rules.
- **Scrum** focuses on the integrating the client as a team member and on the iteration process, which must deliver a usable and improvable product often. It also helps to show where the problems are and leads the way to solve them each time one appears.
- **XP** focuses on writing code itself. It raises the values and practices that should be considered *good*, the day-to-day working basis to be a better programmer.

Either if you work in team or alone, as freelance, an agile methodology could help. Delivering often a usable product to the client results in that client collaborates rather than observing the process, giving a valuable feedback. On the freelance case, the relation between the client and the freelance would be considered a "team", because both work together.

I asked [this question on freelancing stackexchange Q&A](http://freelancing.stackexchange.com/questions/381/agile-methodologies-when-developing-software-as-a-freelance) to get feedback about this conclusion.

### Dilema 3 ###

Should I mix all the methodologies or simply pick the good things of each one? What things are the best from each methodology?

### Conclusion 3 ###

It depends on the people on the team, and its experience. *KanBan* is reported to work better for teams used to work with predictable methodologies by its ease, while *Scrum* and *XP* are reported to work well together because the first manages the project progress while the second standarizes the day-to-day programming practices.
 
Any technique from any methodology is good if it improves the productivity and/or quality, helping to do something like:

- Definition, distribution, and prioritization of **tasks**.
- Estimation and optimization of **time**.

## Tasks and time ###

The management of tasks and time is path to *get the job done*.

# Topics to write about #

* Pomodoro Technique. It helps managing tasks and enhances productivity. Also helps to estimate the time that each task consumes.


## Software design patterns ##

MVC vs MVA: http://www.palantir.com/2009/04/model-view-adapter/
MVA != [MVP](http://en.wikipedia.org/wiki/Model%E2%80%93view%E2%80%93presenter

## Software development process ##
Test Driven Development
http://c2.com/cgi/wiki?TestDrivenDevelopment
wikipedia?

Behaviour Driven Development 
http://dannorth.net/introducing-bdd/
http://www.codeproject.com/Articles/148043/Say-Hello-To-Behavior-Driven-Development-BDD-Part
User Stories
http://en.wikipedia.org/wiki/User_story


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
    
    * choosing the software development method. 
    * Enhancing the methodology with support disciplines
      

* Project structure
