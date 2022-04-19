# **Latency Function Parameters**

This repo includes the latency function parameters used in the paper "Traffic Optimization Using a Coordinated Route Updating Mechanism". Three networks, Braess, ND (Nguyen & Dupuis) and Sioux Falls, are experimented. There are two types of latency functions. One is linear, and its parameters involve a free-flow time (fft) and a driver-dependent time (ddt). The other one is BPR, and its parameters include the free-flow time, an edge capacity and two constants (alpha and beta).

Traffic demand for each OD pair as well as the SO edge flow are also given. For each network under a latency function, all parameters are stored in a netlist file (.ntl file).