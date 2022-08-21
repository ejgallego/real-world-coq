---
layout: home
---
## Title: "Real World Coq -- An introduction to mechanically verified mathematical proofs"

Sept 5-9, 2022 | Sabanci University, Istanbul

Instructor: Emilio J. Gallego Arias (Inria)
Coordinator: Süha Mutluergil (Sabanci University)
Teaching Assistant: Ali Caglayan

Duration of the course: 5 days

## Introduction

Proofs constitute the backbone of both Mathematics and Computer Science (CS). Doing a mathematical proof requires domain knowledge, solid reasoning skills and applying reasoning techniques carefully step-by-step. It is a tedious and error-prone task. For this reason, computer scientists aim to develop programs for mechanizing and/or automating the proof process. Coq is an interactive proof assistant developed for this purpose. Using Coq, one can define mathematical objects or computer programs, express theorems or assertions on these entities, and mechanically check correctness of them by either interacting with Coq or automatically by using so called proof tactics depending on the availability of an applicable one.

[Coq](https://coq.inria.fr/) is an industrial-scale tool successfully used for both research and commercial purposes. In 2005, famous four color theorem was proven in Coq yielding a proof library as a by product with general purpose features that could be used in many settings. AbsInt company develops and maintains an optimized, commercially used C compiler called CompCert. CompCert is specified, programmed and verified in Coq, and its performance is comparable with canonical GCC compiler. 

Coq is a free open-source software developed and maintained by a large and active [user community](https://coq.inria.fr/community.html). New extensions and Coq based tools are frequently introduced.  It has a [sub-reddit](https://www.reddit.com/r/Coq/) and active support can be easily found on [Stack Overflow](https://stackoverflow.com/questions/tagged/coq) and [Stack Exchange](https://cstheory.stackexchange.com/questions/tagged/coq). Main supporter of COQ is INRIA - French public computer science institute. Its development and maintenance is managed by the [Coq Team](https://coq.inria.fr/coq-team.html). Dr. Emilio Jesus Gallego Arias, the instructor for this workshop, is a member of the core team.

This course aims to introduce Coq proof assistant through basic concepts and various exercises. The course will be conducted by Dr. Emilio Jesus Gallego Arias (primary instructor), a member of the [Coq Core Team](https://coq.inria.fr/coq-team.html), and Ali Caglayan (teaching assistant), also a member of the [Coq team](https://coq.inria.fr/coq-team.html). The course will consist of lectures including interactive and hands-on exercises. 

The first edition of the course will be held at Sabanci University, Istanbul as a workshop between 5-9 September. Lectures will be hybrid. The attendance is limited to 20 physical and 10 online participants. Application information and further details on the workshop is provided below. 

## Important Dates

Application Deadline: 29 August
Notifications: 30-31 August
Workshop: 5-9 September

## Registration

In order to apply for the workshop, please email to [Yagiz Kilicarslan](mailto:ykilicarslan@sabanciuniv.edu) with the following information:
- Name, Surname
- Institution
- Email Address
- Are you a student?
- Do you want to attend physically or online?
- Do you want to stay at Sabanci University dorms? If so, do you want to stay alone or share the room with another person? (see the difference in rates under Accommodation section.)

## Transportation

Sabanci University is located at Tuzla. It is adjacent to Istanbul Anadolu Highway (TEM, E-80) and 20 minutes drive away from Sabiha Gokcen International Airport. 

Transportation serviceses are mainly provided by shuttles of Gursel Turizm. Shuttle schedule can be seen at https://www.sabanciuniv.edu/en/shuttle-hours 

Otherwise, IETT bus: KM18 can be taken, which has a stop directly inside of Sabanci University.

Another alternative is taking a taxi from from Tavsantepe metro station, which can be more costly but more comfortable as well.

Note that Gursel Shuttles also have departures from Pendik metro station, which can be useful for those who want to use metro-shuttle combination.

## Accommodation

There are no housing options inside Sabanci University Campus. Unfortunately, the guesthouse will be closed for maintenance during the workshop dates. Only in campus accommodation option for workshop participants is student dormitories. 2-person rooms are reserved for participants. Rates for staying single in the room is 800 try/night and sharing the room with another person is 400 try/night.

## Online Participation

If you are registered for online participation, you can join us using the following Zoom link:

Recordings will be temporarily available here:

## Contact

For your questions related to the organization, please email to [Suha Mutluergil](mailto:suha.mutluergil@sabanciuniv.edu) or [Yagiz Kilicarslan](mailto:ykilicarslan@sabanciuniv.edu).


## Program/Schedule:

The course will take place using an intensive schedule, with 3 hours in
the morning for teaching, and 3 hours in the afternoon for exercises
(with the corresponding breaks of course)

Attendants are expected to follow the instructor along, as the lessons
themselves are interactive and allow the attendants to interact with them.

A laptop with internet connection is required, tho the lessons can be
downloaded locally if desired. The lessons require a modern web browser.

## Resumed syllabus:

- Day 1: Introduction to type theory as a mathematical language

       We will review the formal logical language that is at the base of
       interactive proof assistants such as Coq or Lean.

       We will introduce the concept of "functional programming", which
       lies at the root of the construction of Coq (or Lean) proofs, and
       review some common patterns often used in the field.

- Day 2: Core Coq tactics and proofs

       We will introduce the Coq proof assistant more in depth, and
       review how it is different from other programming languages.

       We will discuss Coq datatypes ("inductive types"), which are a
       powerful tool for the modelling of mathematical concepts, and we
       will discover the main proof techniques, tactics, and library
       objects available in Coq and the Mathematical components library.

       We will place special focus on the role of libraries and modular
       proofs.

- Day 3: Program verification

       We will give an overview of the main techniques used to verify
       the correctness of programs, including the definition of custom
       program logics, and compiler correctness by simulation.

       In this session, we will follow a proof style often found in the
       programming language literature.

- Day 4: Mathematics verification

       In this session, we will present a proof style a bit different
       from the previous one, which is more adapter to the construction
       of mathematical proofs.

       We will discuss libraries and proof techniques for (linear)
       algebra, classical analysis, and group theory.

- Day 5: Advanced topics and Extended Exercise session.

       We will briefly discuss some advances topics and trends in the
       area, to proceed with an extended tutorial session to allow
       participants to wrap their exercise sheets.
