# Exploration of the Biham-Middleton-Levine Traffic Model
## Maya Cranor and Becca Flach

### Abstract goes here
In this project, we plan to use cellular automata to implement the Biham-Middleton-Levine traffic model. This is a 2d cellular automata based on rule 184 that is used as a model of a traffic system to simulate different states, including traffic jams, free flowing traffic, and intermittent phases. We plan to implement this in a jupyter notebook. 


### Annotated Bibliography 

[Self-organization and a dynamical transition in traffic flow models](https://sci-hub.ru/https://journals.aps.org/pra/abstract/10.1103/PhysRevA.46.R6124)
Ofer Biham, A. Alan Middleton, and Dov Levine 
This paper introduces the Biham-Middleton-Levine traffic model. The authors propose three variants of a two dimensional lattice, in each of which the grid has cars that can only move either right or up. In the first, there is a traffic light system that makes the different cars move at different times. The second model removes that, and the third model ignores interactions between the cars, making it essentially one dimensional. In these models, distinct phases of jams and free flowing traffic emerge and transition quickly. 

[Power-Law Distribution and 1/f Noise of Waiting Time near Traffic-Jam Threshold](https://sci-hub.ru/https://journals.jps.jp/doi/10.1143/JPSJ.62.2533)
Takashi Nagatani

Biham proposed a three-state CA on a square lattice, where each cell contains either a car moving upwards or left/right or it is empty. Musha used traffic flow in a one dimensional system says that it follows the Burgers equation. The paper explores the Biham model and looks to see at what density a traffic jam occurs.

[For what number of cars must self organization occur in the Biham-Middleton-Levine traffic model from any possible starting configuration?](https://arxiv.org/abs/math/0607759)
Tim D. Austin Itai Benjamini

This paper explores the Biham-Middleton-Levine model. Speed one is when every car is blocked from moving only finitely many times, and so after some finite time the cars all move freely. If the cars can’t move after awhile that means the model is stuck in a jam. The paper looks at initial configurations to determine when the model will hit speed one or get stuck. For any initial configuration of fewer than 1/2 N cars the BML model will self organize to attain speed one. On the other hand, there is a configuration of size m in which no car can move if and only if m is at least 2N.


### Experimentation

We plan on replicating the first paper, where they build the Biham-Middleton-Levine model. Once that is built, we want to explore the phase changes of the model along with different start conditions. 

As an extension we want to look into modeling rush hour and investigating the time it takes for traffic to return to a free flowing state once the density is decreased. We will probably base this work off some of the other papers we have found.

### Potential Results
We generally expect our model to produce results similar to the various implementations of the Biham-Middleton-Levine model, such as [this online simulator](https://www.jasondavies.com/bml/#0.39/769/512). We will also look at statistics like waiting time and compare them to the findings of the papers. 

### Interpret the Results
To interpret results we can measure the length of time the system takes to get stuck or hit speed 1, as well as the average time it takes for the cell to move across the screen.

### Cause for Concern
We are concerned about the feasibility of changing the number of cars in a currently running system. 

### Next Steps
This week, we plan to implement rule 184, the one dimensional version of the model. We will both work on this separately to gain a better understanding of the model. 
After that, we will plan and recreate the full model together, and then begin modifying it and exploring the results. 
