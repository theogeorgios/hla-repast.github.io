---
layout: default
---

# HLA_RePast

Large Scale Distributed Simulation of MAS via HLA

HLA_RePast is a framework and a middleware system that allows the integration, through a High Level Architecture (HLA) federation, 
of multiple instances of the Java-based lightweight sequential MAS simulation toolkit RePast.  

HLA_RePast has been the *very first effort to distribute MAS simulation executives in general and RePast in particular with the HLA*, 
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


# HLA_RePast on the Grid

![](/assets/images/hla-repast/esci-logo.png)

In the Spring of 2003, the e-Science Core Programme issued a call for high quality proposals for international projects 
(referred to as “Sister Projects”) to establish synergistic links between individual UK e-Science projects 
and leading Grid/e-Science projects from around the globe. DS-Grid was one of only four such projects that received funding 
(e-Science Sister Project [GR/S82862/01](https://gow.epsrc.ukri.org/NGBOViewGrant.aspx?GrantRef=GR/S82862/01)). 

The vision of the DS-Grid project was a “Grid plug-and-play distributed simulation system", 
a distributed collaborative simulation environment where researchers with different domain knowledge and expertise, 
at different locations, develop, modify, assemble and execute distributed simulation components over the Grid. 
While HLA enables the construction of large-scale distributed simulations using existing and possibly distributed simulation components, 
Grid technologies enable collaboration and the use of distributed computing resources, 
while also facilitating access to geographically distributed data sets. 

As part of the project, HLA_RePast was ported onto Globus Toolkit v3 and experiments were conducted in WAN environments, 
where different HLA_RePast Federates executed in different countries, including across UK and Singapore. 
This was the first ever time such a cross-continental HLA infrastructure for MAS simulations was set up 
and the first time a RePast simulation was partitioned across 2 continents!

The project was underpinned by the organisation of two conferences:
1.	 International Workshop on Distributed Simulation on the Grid, in conjunction with CCGRID 2006, Singapore, 16-19 May 2006 (pages  62-69)
2.	The Challenges of working with Grids for Simulations, Birds of a Feather Session, e-Science All Hands Meeting 2006, UK,  20 September 2006.

![](/assets/images/hla-repast/flow.png)

![](/assets/images/hla-repast/global.png)
