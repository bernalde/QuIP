---
title: "47-779 - Quantum Integer Programming - CMU Fall 2020"
layout: home
menuItem: "Basic info"
menuPosition: 1
---
<h1>{{ site.courseName }}</h1>

<img src="{{ site.baseurl }}/style/header.jpg" width="100%">

Tuesdays and Thursdays 5:20p.m. - 7:10p.m. EST. Lectures on Zoom.

Prof. Sridhar Tayur (4216 Tepper Quad), Dr. Davide Venturelli (online), David Bernal (DH3116).

## News

Our collaboration with USRA and Amazon Web Services was recently featured in [this news release](https://www.cmu.edu/tepper/news/stories/2020/october/quantum-computing-course.html) from the Tepper School of Businees at Carnegie Mellon Univerity.
The article also mentions the motivation of creating this course, so enjoy the read!


## Objectives

This course is primarily designed for graduate students (and advanced undergraduates) across CMU campuses interested in integer programming (with non-linear objective functions) and the potential of near-term quantum computing for solving combinatorial optimization problems.
By the end of the semester, someone enrolled in this course should be able to:
- Identify the current status of quantum computing and its potential uses for integer programming
- Access and use quantum computing resources (such as DWave Quantum Annealers)
- Set up a given integer program to be solved with quantum computing 
- Work in groups collaboratively on a state-of-the-art project regarding applications of quantum computing and integer programming

This course is not going to focus on the following topics:
- Quantum Gates and Circuits
- Computational complexity theory
- Quantum Information Theory
- Analysis of speedup using differential geometry, algebraic topology, etc.

Students with backgrounds in operations research, industrial engineering, chemical engineering, electrical engineering, physics, computer science, or applied mathematics are strongly encouraged to consider taking this course.
[Enroll here.](https://s3.andrew.cmu.edu/sio)

## Prerequisite classes and capabilities

Although this class has no explicit prerequisites we consider a list of recommended topics and skills that the student should feel comfortable with.
An undergraduate-level understanding of probability, calculus, statistics, graph theory, algorithms, and linear algebra is assumed.
Knowledge of linear and integer programming will be useful for this course.
Programming skills are strongly recommended.
Basic concepts in physics are recommended but lack of prior knowledge is not an issue as pertinent ones will be covered in the lectures.
No particular knowledge in quantum mechanics or algebraic geometry is required.


## Basic course structure

**Weeks 1-2:** Integer programming: classical methods, Grobner Basis. Test-sets.

**Week 3:** Graver Basis, Ising model. 

**Week 4:** Quadratic Unconstrained Binary Optimization (QUBO), Graver Augmented Multiseed algorithm (GAMA).

**Week 5:** Quantum methods for solving Ising/QUBO: Adiabatic Quantum Computing (AQC), Quantum Approximate Optimization Algorithm (QAOA).

**Week 6:** Specialized hardware for solving Ising/QUBO.

**Week 7:** Applications, Compiling and Final Project presentations.


## Grading
Weekly homework and quizzes (50%), Final Project (50%).
- Each week will have a short quiz to evaluate the concepts covered in class. The two worst quizzes won't be counted towards the final grade.
- The final project will be submitted in groups and it will require the implementation and solution of an integer programming instance using quantum computing resources. This final project deliverable will be a report and a presentation.

## Highlights
The specific skills that students will gain that will make them "quantum ready" for industry or further academic research in this course are:

A. Classical

1. Given a practical problem (from supply chain or physics or anything else), formulate it as a non-linear integer program. We will provide a few practical problems, but we encourage you to suggest one that you are already working on or are interested in.
2. Solve such formulations via classical solvers.

B. Quantum

3. Reformulate the problem to be “quantum ready” by making it in the form of a QUBO. 
4. Solve the QUBO “brute force” through D-Wave or IBM (via QAOA).

C. Hybrid Quantum-Classical

5. Reformulate the problem again in the form suitable for GAMA.
6. Solve GAMA compatible formulation via D-Wave and/or via QAOA.

USRA Collaboration
- Access to D-Wave systems might be available via written proposals to the University Space Research Association (USRA). See [RIACS website](https://riacs.usra.edu/quantum/rfp) for terms and conditions. The course will discuss proposal preparation.
- Students of this course are encouraged to apply to the [Feynman Academy Internship program](https://riacs.usra.edu/quantum/qacademy) that sponsors research projects at NASA Ames Research Center.

Amazon Braket Collaboration
- Access to [D-Wave](https://aws.amazon.com/braket/hardware-providers/dwave/), [IonQ](https://aws.amazon.com/braket/hardware-providers/ionq/) and [Rigetti](https://aws.amazon.com/braket/hardware-providers/rigetti/ ) is also made possible through [Amazon Braket](https://aws.amazon.com/braket/).  


# Full Syllabus
The complete syllabus can be downloaded <a href="syllabus_tex/QuIP_Syllabus-4.pdf" download>here.</a>
