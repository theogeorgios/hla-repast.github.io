---
layout: default
---

# HLA_RePast

Large Scale Distributed Simulation of MAS via HLA

HLA_RePast is a framework and a middleware system that allows the integration, through a High Level Architecture (HLA) federation, 
of multiple instances of the Java-based lightweight sequential MAS simulation toolkit RePast.  

HLA_RePast has been the **very first effort to distribute MAS simulation executives in general and RePast in particular with the HLA**, 
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



