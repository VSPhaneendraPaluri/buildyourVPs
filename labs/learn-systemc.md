---
layout: page
title: Learn-SystemC
permalink: /labs/learn-systemc
---

## Welcome to Learning SystemC

I'll try keep maintain the sources with appropriate comments that showcases the simulation of a feature implementation using SystemC and it's usage within the simulator.

SystemC shares good analogy with HDL language VHDL.  So, VHDL readers might find it few similarities when an IP/Model is modelled at a granularity at which the hardware functions.  SystemC allows us to communicate between various SystemC simulation models using interfaces that can vary over basic types to custom-types, and SystemC interfaces also lays the foundation later on for TLM2 learnings.  

With the below mentioned learning plan, the user should be able to understand and hopefully appreciate the concepts

- Constructs made available by SystemC for hardware modelling
- How SystemC models communicate with each-other
- What is <b><i>co-operative multi-tasking</i><b>
- Understanding how SystemC kernel executes, operates
- Scheduling of SystemC processes
  - clock-based, or 
  - event-based, or
  - time-based scheduling, etcetera
- How can one create custom (user-defined) interfaces
- Building some basic custom IP/Model
- Some Good Practices

Well, that's it ...
