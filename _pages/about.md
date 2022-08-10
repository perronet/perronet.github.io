---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

Hi there! I am a computer scientist broadly interested in software engineering, operating systems, and static program analysis. I moved to Germany after my Bachelor's degree to pursue a *Master+PhD* program at [Max Planck Institute for software systems (**MPI-SWS**)](https://www.mpi-sws.org/): in this program, students study for courses while working on research projects. After obtaining my Master's degree in Germany, I traveled to London for a three months internship at **Meta**, where I worked as a software engineer on the [Infer](https://fbinfer.com/) project.

My research at MPI-SWS
------

I worked in the field of *real-time systems*. In any operating system, functional correctness is important, but in a real-time system also timing correctness is essential. Real-time systems are typically safety-critical systems where timing bugs can have catastrophic consequences (for example, airplanes and cars). To ensure timing correctness, different types of *timing analysis* have been developed.

The real-time systems team works on the novel real-time operating system [TOROS](https://toros.mpi-sws.org/). Part of the mission of TOROS is to ensure, by design, that timing analysis is used to analyze the system behavior without requiring the user to have real-time expertise. To this end, we had many different sub-projects. For my project, I built [DMXtrace](https://gitlab.mpi-sws.org/perronet/rbf-trace): a tool in Rust that performs timing analysis at runtime on Linux systems. The long-term goal is to port DMXtrace and make it become part of TOROS.
