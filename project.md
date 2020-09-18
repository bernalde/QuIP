---
title: Project
layout: page
menuItem: Project
menuPosition: 6
---
{% if site.docsUrl != "" %}
Here you can access all the requirements for the final project.
{% endif %}

The final group project accounts for 50% of the total grade.
This project should reflect the understanding of the material covered in the course.

The components of this project are the following:
- Identify a problem that can be posed as an Integer Program. Discuss the importance of this problem.
- Solve instances of the identified problem using classical tools. Identify which are the sources of complexity while solving this problem.
- Model the problem as a Quadratic Unconstrained Binary Optimization (QUBO). Verify that the reformulation of the problem is valid, in the sense that it represents the original problem.
- Solve the resulting QUBO using non-conventional methods, e.g. Quantum Annealing, QAOA, simulated annealing in GPUs/TPUs, etc. Compare at least two different methods.
- Implement the Graver Augmented Multiseed Algorithm (GAMA) to solve your problem. Evaluate the validity of your formulation for this algorithm and apply other decomposition algorithms if possible.
- Write a report outlining the different approaches used and highlighting the knowledge obtained while developing the project.
- Make a final presentation to the class reporting the findings of the project.
