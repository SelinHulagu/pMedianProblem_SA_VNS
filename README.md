# pMedianProblem_SA_VNS
Solving the p-Median Problem using Simulated Annealing and Variable Neighborhood Search

Within this repository, the p-median problem for three data sets are solved using Simulated Annealing and Variable Neighborhood Search metaheuristics. They are called eil51, eil76, and eil101, and consist of 51, 76, and 101 customer locations, respectively. Each data set includes the x-coordinates, y-coordinates, and demand of customers. Customer locations are also potential facility location for opening facilities. For each data set, 4, 6, and 8 facilities should be located. This makes a total of 9 instances (3 data sets, 3 different p values). The distances between potential facility locations and customer locations are measure via Euclidean distance (not Squared Euclidean distance). Both algorithms are runned 10 times starting with 10 different initial solutions in order to reveal the robustness. 

Please note that this work is done as an assignment of Heuristic Methods in Optimization course Spring 2021, in Bogazici University.
