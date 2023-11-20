---
layout: default
---

# HLA_RePast

HLA_RePast is a framework and a middleware system that allows the integration, through a ]High Level Architecture (HLA](https://standards.ieee.org/ieee/1516/3744/) federation, 
of multiple instances of the Java-based lightweight sequential MAS simulation toolkit [RePast](https://repast.github.io/).  

HLA_RePast has been one of the **very first efforts to distribute MAS simulation executives in general and RePast in particular with the HLA**, 
thus pioneering the topic of HLA-based distributed MAS simulations.  

![](/assets/images/hla-repast/arch.png)

# Motivation and Rationale

Large, experimental multi-agent system (MAS) simulations are highly demanding tasks, both computationally and developmentally. 
Agent toolkits provide reliable templates for the design of even the largest MAS simulations, 
without offering a solution to computational limitations. Conversely, distributed simulation architectures offer performance benefits, 
but the introduction of parallel logic can complicate the design process significantly. 
The motivations of distribution are not limited to this question of processing power. 
True interoperation of sequential agent-simulation platforms would allow agents designed using different toolkits 
to transparently interact in common abstract domains. 

HLA_RePast aims to address this gap, harnessing the computational power of a distributed simulation infrastructure 
with the design efficiency of an agent toolkit. The system constitutes an approach to the distribution and interoperation 
of agent-modelling platforms utilising the HLA interoperability framework.



