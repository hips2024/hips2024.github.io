![IPDPS 2024 Logo](/assets/IPDPS2023-300px.jpg)

# 29th International Workshop on High-Level Parallel Programming Models and Supportive Environments

# Overview
The 29th HIPS workshop, proposed as a full-day meeting at the IEEE IPDPS 2024
conference in San Francisco, California, USA, focuses on high-level programming
of multiprocessors, compute clusters, and massively parallel machines.
Like previous workshops in the series, which was established in 1996,
this event will serve as a forum for research in the areas of parallel
applications, language design, compilers, runtime systems, and programming
tools. It provides a timely forum for scientists and engineers to present the
latest ideas and findings in these rapidly changing fields. In our call for
papers, we especially encouraged innovative approaches in the areas of emerging
programming models for large-scale parallel systems and many-core architectures.

---
---

# Program
May 15th, 2023 \\
08:55 - 17:05 EDT

## Welcome Remarks
08:55 - 09:00 EDT

## Keynote 1
09:00 - 10:00 EDT

**Title: Three Insights Learned in Optimizing Deep Learning** \\
**Prof. Xipeng Shen**

Abstract: \\
Computing efficiency is crucial for Deep Learning. This talk summarizes three-fold key insights that Prof. Shen's group has attained in their years of research on high performance machine learning and real-time AI. In particular, Prof. Shen will draw on DNN and GNN optimization examples to explain the top factors to consider in ML compilation, the surprisingly large potential in approximation-based optimization, and how model-code co-optimization goes a long way in unleashing the performance potential of deep learning.

Biography: \\
Xipeng Shen is a Professor in the Computer Science Department at North Carolina State University. His primary research work lies in the field of programming systems and intelligent computing, with an emphasis on inter-disciplinary problems and cross-cutting approaches. His research has influenced the development of modern programming systems in multicore and heterogeneous computing as well as ML systems. He is a recipient of the DOE Early Career Award, NSF CAREER Award, Google Faculty Research Award, IBM CAS Faculty Fellow Award, and the NCSU University Faculty Scholars Award. He is an ACM Distinguished Member, ACM Distinguished Speaker, and a senior member of IEEE.

## Session One: Performance Portability
10:30 - 11:30 EDT

**Understanding Performance Portability of SYCL Kernels: A Case Study with the All-Pairs Distance Calculation in Bioinformatics on GPUs** \\
Zheming Jin, Jeffrey Vetter

**Evaluating performance and portability of high-level programming models: Julia, Python/Numba, and Kokkos on exascale nodes** \\
William Godoy, Pedro Valero-Lara, Elise Dettling, Christian Trefftz, Ian Jorquera, Thomas Sheehy, Ross Miller, Marc Gonzalez-Tallada, Jeffrey Vetter, Valentin Churavy

## Session Two: Memory Subsystem
13:00 - 14:00 EDT

**Evaluating Functional Memory-Managed Parallel Languages for HPC using the NAS Parallel Benchmarks** \\
Michael Wilkins, Garrett Weil, Luke Arnold, Nikos Hardavellas, Peter Dinda

**Memory Traffic and Complete Application Profiling with PAPI Multi-Component Measurements** \\
Daniel Barry, Heike Jagode, Anthony Danalis, Jack Dongarra

## Keynote 2
14:00 - 15:00 EDT

**Compiler Optimization for Tensor Computations: Challenges and Opportunities** \\
**Prof. Ponnuswamy Sadayappan**

Abstract: \\
Compiler technology today is very advanced with respect to lowering programs from high-level languages to low-level instruction sets so as to optimize the number of executed instructions.  However, the fundamental bottleneck in computers today is not the cost of executed arithmetic/logic instructions but the cost of data access and movement, whether it be between processors in a parallel system or through the memory hierarchy at each processor.  Although many compiler optimization techniques such as loop tiling/fusion and data layout transformations have been devised to address this critical bottleneck, the achievable performance from automatic compiler optimization today for key matrix/tensor computations is not comparable to that achieved by manually optimized libraries or auto-tuning frameworks like TVM. This talk will elaborate on some of the key challenges/opportunities for compilers, including design space exploration, effective performance modeling, and algorithm-architecture co-design.

Biography: \\
Sadayappan is a Professor in the School of Computing at the University of Utah, with a joint appointment at Pacific Northwest National Laboratory. His primary research interests center around compiler/runtime optimization for high-performance computing, with an emphasis on matrix/tensor computations. He collaborates closely with computational scientists and data scientists in developing high-performance domain-specific frameworks and applications. Sadayappan is an IEEE Fellow.

## Session Three: Tuning and Analysis
15:30 - 17:00 EDT

**Runtime-Adaptable Selective Performance Instrumentation** \\
Sebastian Kreutzer, Christian Iwainsky, Marta Garcia-Gasulla, Victor Lopez, Christian Bischof

**Designing secure performance metrics for last level cache** \\
Probir Roy, Birhanu Eshete, Pengfei Su

**OptiCPD: Optimization For The Canonical Polyadic Decomposition Algorithm on GPUs** \\
Srinivasan Subramaniyan, Xiaorui Wang

## Closing Remarks
17:00 - 17:05 EDT

---
---

# Committees

## Workshop Co-chairs
- Harshitha Menon (Lawrence Livermore National Laboratory, USA), gopalakrishn1 at llnl.gov
- Jens Domke (RIKEN Center for Computational Science, Japan), jens.domke at riken.jp

## Steering Committee
- Rudolf Eigenmann, University of Delaware, USA
- Michael Gerndt, Technische Universität München, Germany
- Frank Mueller, North Carolina State University, USA
- Martin Schulz, Technische Universität München, Germany

## Program Committee
- Florina M. Ciorba, Universität Basel, Switzerland
- Miwako Tsuji, RIKEN Center for Computational Science, Japan
- Nikela Papadopoulou, Chalmers University of Technology, Sweden
- Qijing Jenny Huang, NVIDIA, USA
- Alexander Weinert, Deutsches Zentrum für Luft- und Raumfahrt (DLR), Germany
- Balazs Gerofi, Intel, USA
- Christian Terboven, RWTH Aachen University, Germany
- Giorgis Georgakoudis, Lawrence Livermore National Laboratory, USA
- James Lin, Shanghai Jiao Tong University, China
- Jeffrey Young, Georgia Institute of Technology, USA
- Konstantinos Parasyris, Lawrence Livermore National Laboratory, USA
- Seyong Lee, Oak Ridge National Laboratory, USA
- Tomohiro Ueno, RIKEN Center for Computational Science, Japan
- William Moses, Massachusetts Institute of Technology, USA
- Melih Elibol, NVIDIA, USA

---
---

# Registration
Attendance at this workshop is part of the registration for IPDPS 2023. See [here](http://www.ipdps.org/ipdps2023/2023-registration.html) to register.

# Topics of Interest
Topics of interest to the HIPS workshop include but are not limited to:
- High-level and domain-specific programming systems
- Languages and compilers for post-Moore's-Law (or Post Von Neumann)
- Language/compiler support for AI/ML and Cybersecurity/Privacy (e.g., ML-based auto-tuning)
- Task-based programming systems
- (Scalable) programming tools and tools for power & performance analysis, modeling, monitoring, and debugging and core correctness
- Compiler analysis and optimization techniques
- OS and architectural support for parallel programming and debugging
- Software and system support for extreme scalability including fault tolerance and power-aware HPC
- Programming environments for heterogeneous multicore systems and accelerators such as GPUs and FPGAs
- Solutions for programming paradigms for GPUs from different hardware vendors
- Dynamism in applications and system resources
- Performance portability
- Efforts for improving the sustainability of scientific software
- Languages and runtime support for multi-science/coupled codes, including but not limited to ensemble computing and uncertainty quantification
- New programming languages and constructs for exploiting parallelism and locality
- Higher-level programming support for quantum computing/quantum simulation

# Important Deadlines
Submission due date: ~~January 19th~~ February 3rd, 2023 Anywhere on Earth (AoE)

Author notification: February 21th, 2023 AoE

Camera-ready papers: March 7th, 2023 AoE

# Submission
The HIPS paper style is identical to the IPDPS paper style.

**Full papers** may not exceed 10 single-spaced double-column pages using
10-point size font on 8.5x11 inch pages (IEEE conference style), including
figures, tables, and references.

**Short papers** may not exceed 4 single-spaced double-column pages using
10-point size font on 8.5x11 inch pages (IEEE conference style), including
figures, tables, and references.

[IPDPS 2024 Call for Papers](http://www.ipdps.org/ipdps2024/2024-call-for-papers.html)

[Submission Website](https://ssl.linklings.net/conferences/ipdps/?page=Submit&id=HIPSWorkshopFullSubmission&site=ipdps2024)

---
---

# History

| Workshop                                                                       | Date            | Location                            |
|--------------------------------------------------------------------------------|-----------------|-------------------------------------|
| [28th HIPS 2023](https://hips2023.github.io/)                                  | May 15th 2023   | St. Petersburg, Florida, USA        |
| [27th HIPS 2022](https://hips2022.github.io/)                                  | May 30th 2022   | Virtual                             |
| [26th HIPS 2021](https://www.cs.wm.edu/~bren/HIPS_2021.htm)                    | May 17th 2021   | Virtual                             |
| [25th HIPS 2020](https://faculty.ucmerced.edu/dong-li/HIPS_2020.htm)           | May 18th 2020   | New Orleans, Louisiana, USA         |
| [24th HIPS 2019](https://hosting.cs.vt.edu/hips2019/)                          | May 20th 2019   | Rio de Janeiro, Brazil              |
| [23rd HIPS 2018](http://hips2018.mnm-team.org/)                                | May 21st 2018   | Vancouver, British Columbia, Canada |
| [22nd HIPS 2017](https://inside.mines.edu/~bwu/sites/HIPS2017/)                | May 29th 2017   | Orlando, FL, USA                    |
| 21st HIPS 2016                                                                 | May 23rd 2016   | Chicago, IL, USA                    |
| [20th HIPS 2015](https://hpc.pnl.gov/conf/hips/2015/)                          | May 25th 2015   | Hyderabad, India                    |
| [19th HIPS 2014](https://www.eecis.udel.edu/~cavazos/hips/)                    | May 19th 2014   | Phoenix, AZ, USA                    |
| 18th HIPS 2013                                                                 | May 20th 2013   | Boston, MA, USA                     |
| 17th HIPS 2012                                                                 | May 21st 2012   | Shanghai, China                     |
| [16th HIPS 2011](http://www.unixer.de/hips2011/)                               | May 20th 2011   | Anchorage, Alaska, USA              |
| 15th HIPS 2010                                                                 | April 19th 2010 | Atlanta, GA, USA                    |
| 14th HIPS 2009                                                                 | May 25th 2009   | Rome, Italy                         |
| 13th HIPS 2008                                                                 | April 14th 2008 | Miami, FL, USA                      |
| [12th HIPS 2007](https://www.cs.rochester.edu/~cding/Announcements/HIPS07/)    | March 26th 2007 | Long Beach, California, USA         |
| 11th HIPS 2006                                                                 | April 25th 2006 | Rhodes Island, Greece               |
| 10th HIPS 2005                                                                 | April 4th 2005  | Denver, Colorado, USA               |
| 9th HIPS 2004                                                                  | April 26th 2004 | Santa Fe, New Mexico, USA           |
| 8th HIPS 2003                                                                  | April 22nd 2003 | Nice, France                        |
| 7th HIPS 2002                                                                  | April 15th 2002 | Fort Lauderdale, FL, USA            |
| 6th HIPS 2001                                                                  | April 23rd 2001 | San Francisco, CA, USA              |
| 5th HIPS 2000                                                                  | May 1st 2000    | Cancun, Mexico                      |
| 4th HIPS 1999                                                                  | April 12th 1999 | San Juan, Puerto Rico, USA          |
| 3rd HIPS 1998                                                                  | March 30th 1998 | Orlando, FL, USA                    |
| 2nd HIPS 1997                                                                  | April 1st 1997  | Geneva, Switzerland                 |
| 1st HIPS 1996                                                                  | April 16th 1996 | Honolulu, HI, USA                   |
