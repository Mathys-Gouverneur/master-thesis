# Master’s Thesis — Towards an improved nonconvex optimization step in a compressive clustering algorithm

This repository provides the reference related to my Master’s thesis 
submitted for the M.Sc. in Applied Mathematics at École polytechnique de Louvain.

## Abstract
Machine learning, the process of learning from data, has revolutionized many fields but faces computational challenges as datasets expand exponentially. Compressive learning is an emerging approach to address this issue by first compressing datasets into low-dimensional sketch vectors, before performing learning tasks. One key application of compressive learning is compressive clustering, which aims to perform a clustering task, i.e., group together ’similar’ data samples, using only the sketch of a dataset. To tackle the compressive clustering problem, the standard approach is the heuristic algorithm CL-OMPR. However, CL-OMPR can be difficult to tune and may fail in certain cases. In this work, we carefully analyze CL-OMPR to overcome its limitations. We identify that these issues arise from optimization challenges related to the structure of a correlation function used in key steps of the algorithm. We propose methods to improve the nonconvex optimization of this function, enhancing the robustness of CL-OMPR and simplifying its tuning.

## Access to the Thesis
The full manuscript is available via the institutional repository:
[➡️ [Official thesis link]](https://thesis.dial.uclouvain.be/entities/masterthesis/f232023e-5c1f-4ce7-b96e-98faa7ec8574)
