# Quantum-Implementation-of-the-Modified-Dijkstra-s-Routing-Algorithm
This repository provides the quantum implementation of the Modified Dijkstra's Routing Algorithm (https://users.utcluj.ro/~atn/papers/ATN_3_2010_14.pdf) in Qiskit.

# Prerequisites
In order to run quantum processes, we used Qiskit which is an open-source SDK for working with OpenQASM and the IBM Q quantum processors. 

Both, the Qiskit and IBM Q Experience are free to use; to use IBM Q Experience you need to login on their webpage using an IBMid or a third-party account such as Google, GitHub, LinkedIn or Twitter.

If you want to use Qiskit, you should have on your computer Python 3.6 or later. The official documentation recommend installing Anaconda which has Jupyter included. The installation steps can be found on the following link: https://qiskit.org/documentation/install.html

# Short Description of the Work
We intended to do a quantum implementation of our previous work, namely Modified Dijkstra's Algorithm (https://users.utcluj.ro/~atn/papers/ATN_3_2010_14.pdf). For this, we particularized the Travel Salesman Problem, obtaining the possible routes from a given source to a destination with a certain probability using a Phase Estimation Quantum Circuit.

After obtaining the routes, we used an optimized version of the Grover quantum search algorithm (https://arxiv.org/ftp/arxiv/papers/1908/1908.07943.pdf) to compute the shortest path between the source and the destination.

# Authors

Copyright © Robert BOTEZ, Iustin IVANCIU, Virgil DOBROTA: Robert.Botez@com.utcluj.ro, Iustin.Ivanciu@com.utcluj.ro, Virgil.Dobrota@com.utcluj.ro
