## Description
This project was completed as part of the graph theory course by Enzo Di Maria and Yassir El Bsita. <br/>
The objective is, from a graph representing a population, to compare different models of virus propagation, then to determine who is patient zero.

## To use it
In order to see the spread of the virus according to the models, go to the _gen_ folder. In the initial state, files take the form **init-population.png**. <br/>
After a certain time, t+100 for example, the files appear as **model-population+100.png**. <br/>
There are three models: SIS, SIR, and SAIR.
The color code is as follows:
* S - susceptible to infection - blue
* I - infected - orange
* R - restored - purple
* A - case contact - green


In the **karat7_Q22_1.png**, **karat7_Q22_2.png** and **grid50_Q22.png** files, you can see the difference in efficiency of the patient zero search algorithms. <br/>
The code is as follows:
* Z - true patient zero
* J - center of the graph via Jordan's algorithm
* C - center of the graph via the centrality distance algorithm
