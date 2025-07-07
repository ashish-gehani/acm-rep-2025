---
title: Tutorials
---

## Improving FAIRability of your research outcomes with RO-Crates and Bioschemas

**When:** July 29th 2025, 9am

**Where:** Allard 121, in-person presentation

**Authors:** <u>Phil Reed</u> (The University of Manchester) and Abigail Miller (The Jackson Laboratory)

**Abstract:** RO-Crate is a lightweight method to package research outputs along with their metadata. Bioschemas provides metadata schemas to add structured metadata to webpages on Life Science. Schemas.science extends this provision into non-bio domains.
The combination of RO-Crates, Bioschemas and schemas.science make resources easy to navigate by machines, provide an unambiguous way for machines to access FAIR metadata and content in a single request, and reduce content-negotiation hassle that can give unpredictable results.
This combination is of benefit for researchers and data providers whenever they want to improve FAIRability of their resources as they can support RO-Crate imports and align with Bioschemas specifications, making FAIR-compliant digital objects achievable with existing technologies such as Web Linking over HTTP.

The benefits of adopting RO-Crates are evident in a diverse range of applications. For example, Five Safes RO-Crate [https://w3id.org/5s-crate/](https://w3id.org/5s-crate/) specifies a profile of RO-Crate for the purpose of workflow execution in a distributed trusted research environment (TRE). The TRE-FX Project (delivered with HDR-UK) is providing safe, federated access to TREs, using the Five Safes RO-Crate standard.
Following a Bring Your Own Resource hands-on style, in this tutorial we will showcase how to use RO-Crates, and Bioschemas to improve FAIRability and will accompany attendees to apply the technologies to their own resources.

## Workflow Mini-Apps: Evaluating Performance Reproducibility in Scientific Workflows

**When:** July 29th 2025, 9am

**Where:** Allard 113, remote presentation

**Authors:** <u>Ozgur Kilic</u> (Brookhaven National Laboratory), Tianle Wang (Brookhaven National Laboratory), Matteo Turilli (Brookhaven National Laboratory), Mikhail Titov (Brookhaven National Laboratory), Andre Merzky (RADICAL-Computing Inc.), Line Pouchard (Sandia National Laboratories), and Shantenu Jha (PPPL, Princeton University)

**Abstract:** Scientific workflows have become indispensable for managing complex computational tasks in high-performance computing (HPC) environments. However, their increasing complexity, scale, and heterogeneity often hinder reproducibility. Workflow mini-apps address these challenges by offering simplified yet faithful representations of complex workflows, enabling easier development, testing, and optimization. This three-hour tutorial introduces participants to workflow mini-apps and demonstrates their practical application to enhance reproducibility. The tutorial comprises three main segments:
- Introduction to Workflow Mini-Apps: Participants will learn what workflow mini-apps are, their role in addressing the reproducibility crisis in scientific computing, and the balance between simplicity and fidelity in their design.
- Building Workflow Mini-Apps (Interactive Session): Using the wfMiniAPI, an open-source Python and C++ library, participants will interactively construct executable mini-apps. They will learn how to emulate key computational kernels and workflows components, tuning parameters to match performance profiles of original workflows.
- Executing and Analyzing Mini-Apps (Interactive Session): Participants will run their constructed mini-apps on HPC resources, collect performance metrics, and analyze reproducibility. Hands-on exercises will highlight portability across platforms and demonstrate mini-apps' utility in capturing essential characteristics of original workflows at a significantly reduced computational cost.

This tutorial targets an introductory to intermediate audience familiar with basic Python programming and HPC concepts. By the conclusion, participants will be equipped to leverage workflow mini-apps to simplify the reproducibility and portability challenges of scientific computing workflows, aligning closely with the themes and goals of ACM REP 2025.

## From your source code to a reproducible online demonstration

**When:** July 29th 2025, 1:30pm-5pm

**Where:** Allard 121, in-person presentation

**Authors:** <u>Miguel Colom</u> (Centre Borelli, ENS Paris-Saclay)

**Abstract:** This is a short hands-on tutorial on how to arrive at a complete reproducible research article, with a special focus on building a complete online demonstration of a particular method. The techniques explained and the recommendations given are general and applicable to any journals or platforms. We'll focus more on the practical aspects of the source code and the online interface for the online demo. Eventually, the objective of this practical tutorial is to show that many of the recommendations on computation reproducibility have strong reasons why they should be followed, and with the tools that currently exist today it is straightforward to implement them and reach good reproducibility and replicability in computational sciences. The participants are expected to finish this tutorial with an interactive online demonstration of their proposed methods.

## Computational Reproducibility With Scientific Workflows: Analysing viral genomes with Nextflow

**When:** July 29th 2025, 1:30pm-5pm

**Where:** Allard 113, remote presentation

**Authors:** <u>George Marchment</u> (Université Paris-Saclay), Sarah Cohen-Boulakia (Université Paris-Saclay), Frédéric Lemoine (Institut Pasteur)

In an era of generation of large datasets and complex scientific analyses, ensuring the reproducibility of data analyses has become paramount. Workflow management systems have emerged as a key solution to this challenge, offering structured, automated, and scalable frameworks for handling data processing tasks, allowing for the development of scientific workflows. However, while they are becoming more popular, workflow management systems have not yet gained wide adoption within the scientific community, largely due to established practices and the perceived high learning curve associated with their use.
This tutorial aims at demonstrating the critical role of workflow management systems in implementing reproducible data analyses, with an emphasis on their capacity to encapsulate heterogeneous code, manage software environments, scale with the data size, and leverage heterogeneous computational resources efficiently. To do so, we will use the Nextflow workflow system and a viral genome sequence reconstruction pipeline as a use case. This will demonstrate the fundamentals of Nextflow and illustrate how it can be used to easily implement, execute, and share a simple workflow.
