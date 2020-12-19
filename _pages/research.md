---
title: "PurS3 Lab - Research"
layout: textlay
excerpt: "PurS3 Lab -- Research"
sitemap: false
permalink: /research/
---

# Research

The goal of PurS3 lab is to secure modern systems. To do so, we find, fix, and prevent vulnerabilities in both software and hardware. Consequently, we develop new systems that are secure by design.
We are interested in all systems: Smartphones, IoT devices, Web Services, etc.

We strongly believe in diversity and aim to be a diverse group with members from different backgrounds.

Here are some themes and techniques that we currently work on:

**Retrofitting Memory Safety to C.** Checked C extends legacy C with checked pointer types that are restricted by the compiler to safe uses. Checked pointer types can coexist with legacy pointers, thus admitting incremental conversion of legacy C to Checked C, in the style of migratory typing. We are working on a technique to port an existing C program to Checked C by converting its pointers to have checked type. [More Details](https://github.com/correctcomputation/checkedc-clang).


**Machine Learning + Security.** Machine Learning (and Deep Learning) provides us very useful techniques to achieve best-effort solutions in the presence of a large corpus of data. Many problems in security are proven to be intractable; however, providing a best-effort solution is reasonable.
On this front, we are exploring the use of various Machine Learning techniques to handle the following problems:

 * __Vulnerability Detection__
 * __Binary Analysis__
 * __Mobile Privacy__


**Fuzzing : New Frontiers**. In general, fuzzing or automated dynamic testing of complex systems (IoT devices, Kernel Drivers, Network Programs, etc.) is still a very hard problem. We explore different techniques that will enable a security researcher to help the fuzzing techniques to test these complex programs effectively. We have exciting ideas in this direction. Get in touch to know more.

**Assured Micropatching (DICER).** DICER is a recompilation pipeline, performing assured recompilation of a patched binary, leveraging information extracted from the original binary. Specifically, DICER is able to optimally recompile a patched binary (minimizing the differences with the original binary), and, at the same time, assure its functionality using multi-layer verifications. This is part of a DARPA funded project and has various interesting problems to be explored.

### ... and more.
