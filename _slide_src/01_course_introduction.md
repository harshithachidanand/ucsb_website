# Course Introduction
.fx: title

__CS290B__

Dr. Bryce Boe  
(Bryce is preferred)

September 24, 2015


---


# Welcome to CS290B

Please grab an index card and write:

* Your name
* Your email address
* Your education level and year (e.g., 2nd year MS)
* Your prior experience with Internet technology
* What you hope to get from this class


---


# About Me

* UCSB CS Alum (BS: 2008, Ph.D.: 2014)
* As a graduate student:
    * Taught 3 undergraduate CS courses
    * TA-ed for numerous other courses
* Took this course in Winter 2009 (CS290N at the time)
* Senior Software Engineer @ AppFolio
* Assisted with the Fall 2014 course
* 13+ years of web "development" experience
    * Learned HTML in 1996
    * Learned PHP & MySQL around 2002


---


# My Teammates "Pear" Programming

![Jon and Adam 'Pear' Programming](img/pear_programming.png)


---


# Today's Agenda

* Course Overview
    * Course Motivation
    * Course Structure
    * Course Grading
    * Course Info
* The Life Cycle of a Web Request
    * Group Exercise
    * Review


---


# Pull requests, pull requests, pull requests!

![Pull Requests! Pull Requests! Pull Requests!](img/developersdevelopers.gif)

If you notice an issue with or wish to make an improvement to any of the course
content (e.g., slides, web pages) please edit them and make a pull request.

Website source:  
[https://github.com/scalableinternetservices/ucsb_website/](https://github.com/scalableinternetservices/ucsb_website/)

Slide source:  
[https://github.com/scalableinternetservices/ucsb_website/tree/master/slides](https://github.com/scalableinternetservices/ucsb_website/tree/master/slides)


---


# Questions and Feedback

At any point during this course:

Stop me to:

* ask a question
* ask for clarification
* provide an additional example

Communicate to me:

* how I can help you succeed in this course
* ideas for making the course more engaging
* any other feedback you may have


---


# Course Motivation


---


# Thought Experiment #1

How do you find a place to rent?


---


# Thought Experiment #1

* [Rent.com](http://www.rent.com/)
* [Apartment Guide](http://www.apartmentguide.com/)
* [Rental Houses](http://www.rentalhouses.com/search/Goleta-CA)
* [Zillow](http://www.zillow.com/homes/for_rent/)
* [Realtor](http://www.realtor.com/apartments/Goleta_CA)
* [Trulia](http://www.trulia.com/for_rent/Goleta,CA)
* [PadMapper](http://www.padmapper.com/)


---


# Thought Experiment #2

How do you find your way in a new city?


---


# Thought Experiment #2

* [Google Maps](https://www.google.com/webhp?sourceid=chrome-instant&ion=1&espv=2&ie=UTF-8#safe=off&q=map+of+goleta)
* [mapquest](http://www.mapquest.com/maps?city=Goleta&state=CA)
* [tripadvisor](http://www.tripadvisor.com/LocalMaps-g32438-Goleta-Area.html)
* [Yelp](http://www.yelp.com/c/goleta-ca-us/restaurants)


---

# Thought Experiment #3


How do you find someone to date?


---


# Thought Experiment #3


* [Zoosk](https://www.zoosk.com/)
* [Match](http://www.match.com/)
* [OurTime](http://www.ourtime.com/)
* [Elite Singles](http://dating.elitesingles.com/)
* [Christian Mingle](http://www.christianmingle.com/)
* [JDate](http://www.jdate.com/)
* [SingleParentMeet](http://www.singleparentmeet.com/)
* [OkCupid](https://www.okcupid.com/)
* [Tinder](https://www.gotinder.com/)


---


# Internet (or Web) Services!

Each of the problems can be solved by a variety of Internet services.

Every day billions of people use various Internet services to solve problems
like these.

As an Internet service grows in popularity, supporting the increased amount of
Internet traffic results in increased complexity of the Internet service.


---


# Internet Services, what's that?

![Question Mark](img/question_mark.jpg)


---


# Internet Services, what's that?

There are many application-level protocols that could be used to build out an
Internet Service.

For this class Internet services will refer to HTTP-based services.

The interface to your web service may be the web browser (e.g., Chrome,
Firefox), a REST-based API, or both.


---


# What about mobile?

 We will discuss some optimizations
 ([HPBN chapter 5](http://chimera.labs.oreilly.com/books/1230000000545/ch05.html))
 designed for mobile users.

Many native mobile apps are backed by Internet services via an API.

![Mobile v. Desktop from 2010 through 2014](img/mobile_v_desktop.png)


---


# Scalable, what does that mean?

![Question Mark](img/question_mark.jpg)


---


# Scalable, what does that mean?

An Internet service is scalable if increasing demands can be effectively met
with increasing capacity.

Demands could be:

* Web traffic quantity (typical association)
* Dataset size


---


# Effectively meet demands: Explanation

* Internet service remains available
* Response time does not excessively degrade

## Think about it

Assume you have a web service designed to run on a single server with a plan to
use a bigger server when it can no longer effectively meet demand.

__Is this scalable?__


---


# What you will do:

In this course you will learn and utilize some of the technologies behind
building large-scale Internet services.

You will test and support to the best of your abilities one or more of:

* Exponential growth in the amount of traffic to your web service
* Exponential growth in the dataset your web service relies upon


---


# In Summary

This course won't teach you how to build a web application that obtains
worldwide attention and usage.

However, this course will teach you how to build a web application __that can
respond to__ worldwide attention and usage.


---

# Other Topics

In addition to scaling, we will learn about:

* Performance
* Security
* Agile software development
* Test driven development
* Web clients (e.g., web browsers)


---


# Course Structure


---


# Lectures and Labs

## Lectures

* Meets Tuesday and Thursday from 3--4:50PM in Phelps 2510 (here)
* The lectures and associated reading will cover the concepts you are expected
  to learn in this class

## Labs

* Meets Thursday from 5--6:50PM in Phelps 3523 (upstairs)
* The labs will focus on the course project
* During the labs you will:
     * Work with your team
     * Demo your progress


---


# Course Project

You will apply your learnings from this course to your course project. The
project entails:

* Working in teams of 4
* Developing an _interesting_ Internet service
* Deploying your service to Amazon EC2
* Measuring your service's performance and scalability
* Applying techniques presented in class to improve your service's performance
  and scalability
* Documenting these improvements via a detailed write-up and presenting the
  results at the end of the quarter


---


# Course skills

__This course is fairly demanding, but is one of the most industry-applicable
courses you can take.__ You will learn and develop the following skills:

* Programming in __Ruby__
* Building web services using the __Rails__ framework
* Experience with Amazon Web Services (__AWS__): __EC2__, __S3__,
  __CloudFormation__
* Load testing internet services via __Tsung__
* Test-Driven Development (__TDD__)
* __Agile__/__Scrum__ software development
* Development using __Git__ with a _feature-branch_ flow via __github__ _pull
  requests_


---


# This course is _not_

a deep-dive into:

* Cloud Computing
* Distributed Systems
* Networking
* Relational Databases
* Security


But we will touch on all of the above.


---


# Industry Focused

The skills you learn in this course are the same that I use everyday at work.

The projects will all be open source so if you're proud of your team's work
(you should be) then put a link to the project on your résumé.

Industry related tools you will use:

* Git via Github (project source version control)
* Ruby on Rails (development _stack_)
* Pivotal Tracker (project management)
* Travis CI (automated testing)
* NewRelic (performance metrics)


---


# Why Ruby on Rails?

Ruby is an interpreted language, thus it is not terribly __fast__, nor is very
__memory efficient__.

However, it is very easily scalable, and for most Internet services developer
time ($$$) is going to be much more significant than the efficiency of the
service.

Building Rails Internet services quickly with zero prior experience makes this
class possible.


---

# $$$

![Average Salary Value of a Skill](img/average_salary_value_of_skill.png)

Source (November 2014):
[http://qz.com/298635/these-programming-languages-will-earn-you-the-most-money/](http://qz.com/298635/these-programming-languages-will-earn-you-the-most-money/)


---


# Texts

## "High Performance Browser Networking"

* by Ilya Grigorik
* Available free online (more recent updates)


## "Agile Web Development with Rails 4"

* by Sam, Ruby, Dave, Thomas, David Heinemeier Hansson
* two copies available in Library Reserves for 2-hour check-outs


---


# Course Grading


---

# Project Grade (assigned to your group)

* 30% web service complexity
* 50% load testing and subsequent scaling (explained in presentation and
  write-up)
* 10% quality of presentation
* 10% quality of write-up

---


# Individual Grade

* 5% participation (in-class, on piazza, slide/material corrections)
* 95% _Project grade_ * your relative group project involvement percent

## How is relative involvement computed?

* Privately, everyone has 100% to assign between the other members of their
  group
* The relative percent for each individual is the sum of what their group-mates
  assign them (can go above 100%)

We will compute these scores __four__ times during the quarter. Only the last
score will be used for your grade.

Any moderate deviations from near-equal grades will prompt communication from
me.


---

# Course Info

* [http://cs290.com](http://cs290.com)
* [https://github.com/scalableinternetservices/](https://github.com/scalableinternetservices/)
* [https://piazza.com/class/idgkoaxbvg14lx](https://piazza.com/class/idgkoaxbvg14lx)
    * Set up email notifications
    * It is strongly encouraged for you to respond to questions, and improve
      upon the "student answer" by making edits.
    * For clarifications on existing questions, please make a comment on an
      existing post
    * For related but separate questions, please create a "new post"


---


# First Five Weeks

* The basics (HTTP and HTML)
* _Industrial_ software engineering: _Agile_, _TDD_, Continuous Integration
  (CI), Pair Programming
* HTTP Application Server architectures
* High availability via load balancing: a share-nothing web stack
* Client-side and server-side caching
* Relational databases with web applications: concurrency control and query
  analysis
* Scaling via:
    * Sharding
    * Service-Oriented-Architecture (SOA)
    * Read-slaves


---


# Later Course Topics

* Web security: _firewalls_, _https_, _XSS_, _CSRF_
* HTTP 2.0
* Content-delivery networks
* Non-relational data stores (NoSQL)
* Client-side frameworks
* And more (maybe):
    * Asm.js, Emscripten, Webruby
    * Elixir and Phoenix


---


# Guest Lectures


## Confirmed (talk topics may vary)

* __November 10__: Darren Mutz on Challenges with Content Delivery Networks  
  Principal Software Engineer @ AppFolio  
  (formerly SDE @ Amazon Web Services)
* __November 12__: Sean Maloney on Analyzing Customer Metrics Using AWS  
  Data Engineer @ Riot Games

## Hopeful

* Colin Kelley -- CTO @ Invoca
* Vinod Kone -- Technical Lead for _Apache Mesos_ @ Twitter
* Jonathan Kupferman -- Former Lead Developer @ Turntable.fm
* Lead Programmer @ reddit
* Software Engineer @ Google Photos


---


# Questions / Brief Break

![Question Mark](img/question_mark.jpg)


---


# The Life Cycle of a Web Request


---


# The Two Endpoint Basics

A web browser is a process (at least one) that runs on an operating system. It:

* responds to user input
* renders the display
* utilizes the network

A web server is a process (at least one) that runs on an operating system. It:

* responds to network requests
* loads resources that may come from file system, database, other servers

---


# Web Request Life Cycle Group Exercise

Prompt: What _things_ (e.g., events, protocols, actions) (might) occur when
someone types [https://www.reddit.com](https://www.reddit.com) in their web
browser and presses return.

## Part 1 (~10 minutes)

Discuss in pairs, and write down in-order the components you come up
with. Start generic, and leave space to provide additional detail for
sub-sequences.

## Part 2 (~10 minutes)

Merge your pair with a near-by pair. Start by comparing the lists you've come
up with, and then write-down your combined lists. (~10 minutes)

## Part 3 (as long as it takes)

Alternating people from each larger group, one member will write one of their
components on the whiteboard in-place and explain it. At the end we'll should
have a pretty definitive list.


---


# Core Components of a Web request

* Web server: Opens a TCP socket to listen for requests
* Browser: Makes a DNS query to obtain an IP address for www.reddit.com
* Browser: Establishes a TCP connection to the IP address
* Web server: Accept the TCP connection
* Web server: Add TLS context to the TCP connection
* Browser: Wraps a TLS session on-top of the TCP connection
* Browser: Sends an HTTP request over the TLS session
* Web server: Parse the request, fetch and send the requested resources


---


# What about scalability?


Let's add a load balancer in there!

![Load balancer and three web servers](img/load_balancer_simple.jpg)

Source:
[http://www.laymance.com/blog/apache-load-balancers-and-log-files/](http://www.laymance.com/blog/apache-load-balancers-and-log-files/)


---




# TO-DO

## By next class

* Join the class on [Piazza](https://piazza.com/class/idgkoaxbvg14lx)
* Read chapters 1 and 2 in
  [High Performance Browser Networking](http://chimera.labs.oreilly.com/books/1230000000545/ch01.html)
* Read the list of project ideas: [http://cs290.com/project_ideas/](http://cs290.com/project_ideas/)
* Post or comment on at least one idea on Piazza under the `project_idea`
  "folder"
* Start Learning Ruby (begin
  [Ruby Code Academy](https://www.codecademy.com/tracks/ruby))
