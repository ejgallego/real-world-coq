---
layout: home
---
## Title: "Real World Coq -- An introduction to mechanically verified mathematical proofs"

Aug 29-31st, 2023 | Boston University (BU)

Instructor: Emilio J. Gallego Arias (Inria)
Local Organizer: Marco Gaboardi (Boston University)

Duration of the tutorial: 3 days

See the [attending the course](#Attending) section for more
information on attending.

This course has been generously supported by Boston University.

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
contributors. Dr. Emilio Jesus Gallego Arias, the instructor for this
workshop, is a member of the [Coq Core
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

### Day 1 (Tue, Aug 29th, 2023): Introduction to type theory as a mathematical language

We will review the formal logical language that is at the base of
interactive proof assistants such as Coq or Lean, including functional
programming, inductive datatypes, and Coq and math-comp proving tactics.

#### Lesson links and schedule

|--------------|----------------------------------------|-----------------------------|
| Time         | Description                            | Links                       |
|--------------|----------------------------------------|-----------------------------|
| 10:30--12:00 | Type Theory as a Mathematical Language | [html file]()               |
| 12:00--12:30 | Break                                  |                             |
| 12:30--13:30 | Exercise Session                       | [html file]() [solutions]() |
|--------------|----------------------------------------|-----------------------------|

### Day 2 (Wed, Aug 30th, 2023): Verification of Core Data Structures

In this lesson, we will introduce the core data structures used in the
Mathematical Components libraries, as well as their associated
theories. A key part of this lesson will be the introduction of the
class hierarchy used in the Mathematical Components library which is
used to handle common properties among types, such as being
denumerable or finite.

We will build and verify a simple interpreter for a declarative
language using the pieces provided by the MC library.

#### Lesson links and schedule

|--------------|----------------------|---------------|
| Time         | Description          | Links         |
|--------------|----------------------|---------------|
| 10:30--12:00 | Core Data Structures | [html file]() |
| 12-00--12:30 | Break                |               |
| 12:30--13:30 | Exercise Session     | [html file]() |
|--------------|----------------------|---------------|

### Day 3 (Thu, Aug 31st, 2023): Mathematics verification

In this session, we will discuss the proof style used to the
construction of proofs founds in the mathematics literature.

In particular, we will survey the available classes for (linear)
algebra in math-comp, including abelian groups, fields, matrices, and
polynomials, along with their main theory.

We will conclude the tutorial with a brief overview of advanced topics
and trends in the field.

#### Lesson links and schedule

|--------------|--------------------------|---------------|
| Time         | Description              | Links         |
|--------------|--------------------------|---------------|
| 10:30--12:00 | Mathematics Verification | [html file]() |
| 12-00--12:30 | Break                    |               |
| 12:30--13:30 | Exercise Session         | [html file]() |
|--------------|--------------------------|---------------|

## Attending

### Location

TBA

### Registration

Are attendants expected to register?

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

## Contact

For your questions related to the organization, please email to
[Emilio J. Gallego Arias](mailto:e@x80.org).
