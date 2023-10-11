---
title: "Dynamic symbolic executor "
collection: projects
permalink:
venue: "University Of Pennsylvania"
date: 2021-01-01
location: "Philadelphia"
---

Built a dynamic symbolic executer (DSE) with LLVM and Z3 that automatically generates inputs to efficiently explore different program paths for C programs. Defined symbolic manipulation functions for each LLVM instruction and instrumented the input C program to enable DSE to interact with Z3 at runtime.