---
layout: page
title: "Module III: Randomized Algorithms for Linear Algebra (RALA)"
permalink: /teaching/randomized-linear-algebra/
description: "This module addresses the challenge of solving large-scale linear algebra problems in the big data era, where classical methods become computationally infeasible. The approach uses randomization to achieve good approximate solutions in shorter time while guaranteeing quality. The problem is solved in two stages: first, randomization is used to obtain a 'sketch' of the matrix and/or develop a basis for the range space; then classical algorithms provide provably good approximate solutions. Topics include sampling-based approaches for matrix-vector and matrix-matrix products, matrix sketching, SVD, CUR decomposition, and fast randomized methods for solving large-scale overdetermined linear least squares problems using both sampling and random projection approaches."
course_id: rala
type: "Short Course"
nav: false
parent_course: "/teaching/mathematics-bigdata-analytics/"
teaching_assistants: []
schedule:
  dates_time: "Tuesdays and Thursdays; 3:30 PM to 5:00 PM"
  classroom: "Room B303, EE Department, IISc"
  duration: "4-5 Lectures"
  meeting_link: ""
  
news:

lectures:
  - title: "Randomized Linear Algebra"
    notes: "/assets/teaching/randomized-linear-algebra/RandomizedLinear Algebra.pdf"
    description:

  - title: "Large Scale Matrices"
    notes: "/assets/teaching/randomized-linear-algebra/LargeScaleMatrices.pdf"
    description:


assignments:

resources:
 - title: "N. Halko, P.G. Martinsson, and J. A. Tropp (2011) Finding Structures with Randomness: Probabilistic Algorithms for constructing Approximate Matrix decompositions, SIAM Review, Vol 53, 217-288"
   url: "https://epubs.siam.org/doi/10.1137/090771806"


 - title: "One Hundred Years of the Design of Experiments on and off the Pages of Biometrika"
   url: "https://www.jstor.org/stable/2673675"
---

{% include course-materials.liquid %}
