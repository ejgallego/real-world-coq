---
title: "Real World Coq Tutorial at Boston University"
layout: page
---
## "Real World Coq -- An introduction to mechanically verified mathematical proofs"

Aug 29-31st, 2023 | Boston University (BU), Boston, USA

- Instructor: Emilio J. Gallego Arias (Inria)
- Local Organizer: Marco Gaboardi (Boston University)

Duration of the tutorial: 3 days

See the [attending the course](#attending) section for more
information on attending and registration.

This course has been generously supported by Boston University.

## Attending

The course can be attended onsite at Boston University, or online
using Zoom.

- [Zoom link](https://bostonu.zoom.us/j/97034339058?pwd=cDRNUjRVYnAyK1R0bVhDcjhkVEJNUT09)
- Meeting ID: 970 3433 9058
- Passcode: 924665

### Is this course for me?

This course is for you if you would like to learn about formal proofs
of software and mathematics that are done using state-of-the-art
libraries and tools.

In particular, we will use the [Coq](https://coq.inria.fr/) system as
our theorem prover, and the [Mathematical Components Library](https://math-comp.github.io/)
as a library of choice.

The will focus on doing proofs using the large selection of tools the
mature math-comp library provides. Such tools and methodology lead to
a proof style that is pretty efficient and maintainable.

Previous knowledge of Coq and formal proofs is not required for this
course, but indeed experience with these subjects and / or functional
programming could be of help.

### Registration

Please register using this [form](https://forms.gle/zxfQUuur47i4nVMU9) .

### Location

The location at BU is CDS 1001. CDS building location:
- [Google](https://goo.gl/maps/AfXDHjexrkMb7K7KA)
- [OpenStreetMap](https://osm.org/go/ZfIvRQbqa?m=)

### Required Software

Each participant is expected to bring their own laptop. A laptop is
required as the course is interactive.

The course requires a recent version of the Chrome Web Browser. Other
browsers may work, but they are supported at your own risk.

Lessons will take place using the [jsCoq](https://coq.vercel.app/)
software. Please, click on the above link and **check the tutorial
works** on your computer.

Internet connection is much recommended but not required, let us know
if you can't connect to internet and we will find a way to distribute
the files.

### Tutorial Forum

We will open a Tutorial Forum using [Coq's Zulip Website](https://coq.zulipchat.com/).

## Introduction

Proofs constitute the backbone of both Mathematics and Computer
Science (CS). Doing a mathematical proof requires domain knowledge,
solid reasoning skills and applying reasoning techniques carefully
step-by-step. It is a tedious and error-prone task. For this reason,
computer scientists aim to develop programs for mechanizing and/or
automating the proof process. Coq is an interactive proof assistant
developed for this purpose. Using Coq, one can define mathematical
objects or computer programs, express theorems or assertions on these
entities, and mechanically check correctness of them by either
interacting with Coq or automatically by using so called proof tactics
depending on the availability of an applicable one.

[Coq](https://coq.inria.fr/) is an industrial-scale tool successfully
used for both research and commercial purposes. In 2005, famous four
color theorem was proven in Coq yielding a proof library as a by
product with general purpose features that could be used in many
settings. AbsInt company develops and maintains an optimized,
commercially used C compiler called CompCert. CompCert is specified,
programmed and verified in Coq, and its performance is comparable with
canonical GCC compiler.

Coq is a free open-source software developed and maintained by a large
and active [user community](https://coq.inria.fr/community.html). New
extensions and Coq based tools are frequently introduced.  It has a
[sub-reddit](https://www.reddit.com/r/Coq/) and active support can be
easily found on [Stack
Overflow](https://stackoverflow.com/questions/tagged/coq) and the new
[Stack Exchange](https://proofassistants.stackexchange.com/) for proof
assistants, the [Coq tag](https://stackexchange.com/questions/tagged/coq) is also useful.

Coq is mainly developed by Inria - French public computer science
institute. Its development and maintenance is managed by the [Coq
Team](https://coq.inria.fr/coq-team.html), but the development follows
a collaborative model and releases usually see dozens of external
contributors. Emilio J. Gallego Arias, the instructor for this
tutorial, is a member of the [Coq Core
Team](https://coq.inria.fr/coq-team.html).

This course aims to introduce the Coq proof assistant in a practical
way, highlighting the methodology used by the state-of-the-art
[Mathematical Components Library](https://math-comp.github.io/).

The Mathematical Components Library provides a comprehensive and
mature knowledge base for computer and mathematical objects that are
ready to re-use in our proofs. We will thus focus on discovering and
using the library, as well as to understand the math-comp proof
development methodology that has been successful in several
large-scale proof efforts.

## Schedule and Syllabus:

The tutorial will take place in the mornings, with a 90 minutes joint
teaching session, a 30 minutes break, and a 1 hour joint exercise
session. The instructor will be available in the afternoon for office
hours.

Attendants are expected to bring their own laptop and follow the
instructor along the lesson in their computer.

We will assume some basic familiarly with functional programming and
interactive proofs, but that's not a pre-requisite to join the
tutorial.

### Day 1 (Tue, Aug 29th, 2023): Core Coq Topics and Tactics

We will review the formal logical language that is at the base of
interactive proof assistants such as Coq or Lean, including functional
programming, inductive datatypes, and the SSReflect proof language.

#### Lesson links and schedule

|--------------|-----------------------------|------------------------------------------------------------------------------|
| Time         | Description                 | Links                                                                        |
|--------------|-----------------------------|------------------------------------------------------------------------------|
| 10:30--11:00 | Welcome, introduction       | [slides](https://x80.org/rwc/slides/coq-introduction.pdf)                    |
| 10:30--11:00 | Core Coq Topics and Tactics | [html file](https://x80.org/rwc/2023-bu/code/lesson_1.html)                  |
| 12:00--13:00 | Break                       |                                                                              |
| 13:00--14:00 | Exercise Session            | [html file](https://x80.org/rwc/2023-bu/code/exercises_1.html) [solutions]() |
|--------------|-----------------------------|------------------------------------------------------------------------------|

### Day 2 (Wed, Aug 30th, 2023): Verification of Core Data Structures

In this lesson, we will introduce the core data structures used in the
Mathematical Components libraries, as well as their associated
theories. In this process, we will study the class hierarchy used to
organize types according to their properties, such as being finite or
having decidable equality.

We will showcase a real-world inspired example illustrating the power
of the approach.

#### Lesson links and schedule

|--------------|---------------------------------------|------------------------------------------------------------------------------|
| Time         | Description                           | Links                                                                        |
|--------------|---------------------------------------|------------------------------------------------------------------------------|
| 10:30--12:00 | Data Structures and Class Hierarchies | [html file](https://x80.org/rwc/2023-bu/code/lesson_2.html)                  |
| 12-00--13:00 | Break                                 |                                                                              |
| 13:00--14:00 | Exercise Session                      | [html file](https://x80.org/rwc/2023-bu/code/exercises_2.html) [solutions]() |
|--------------|---------------------------------------|------------------------------------------------------------------------------|

### Day 3 (Thu, Aug 31st, 2023): Mathematics verification

In this session, we will discuss the proof style used to the
construction of proofs founds in the mathematics literature.

In particular, we will survey the available classes for (linear)
algebra in math-comp, including abelian groups, fields, matrices, and
polynomials, along with their theories.

We will conclude the tutorial with a brief overview of advanced topics
and trends in the field.

#### Lesson links and schedule

|--------------|--------------------------|---------------|
| Time         | Description              | Links         |
|--------------|--------------------------|---------------|
| 10:30--12:00 | Mathematics Verification | [html file](https://x80.org/rwc/2023-bu/code/lesson_3.html)                  |
| 12-00--13:00 | Break                    |               |
| 13:00--14:00 | Exercise Session         | [html file]() |
|--------------|--------------------------|---------------|

## Contact

For your questions related to the organization, please email to
[Emilio J. Gallego Arias](mailto:e@x80.org).
