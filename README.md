# NNPopAssign

This project shows how to use neural networks to perform population assignment with genetic data. I test the neural network classification on genomic data simulated with SLiM3. For the most basic test, I simulated a 5 population stepping stone model (see below) with the following parameters:

* 500 individuals/population
* 1e-6 mutation rate
* 1 mb length genomic region
* 1e-8 recombination rate

I used an elevated mutation rate to quickly accumulate variants. Migration rate among connected populations was bidirectional and set at 0.1, 0.001, 0.00001 for high, medium, low levels of gene flow, respectively.


<img src="./images/stepping-stone.png" alt="stepping-stone-model" width="200"/>

