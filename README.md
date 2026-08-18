# Computational Graph Theory

This repository contains computational investigations of graph-theoretic
problems using Python and NetworkX.

The project combines mathematical analysis with computational methods to
study structural and distance-based properties of graph families.

## Current Project

### Computational Analysis of Hypercube Graphs

The first notebook investigates the \(n\)-dimensional hypercube graph
\(Q_n\).

The computational analysis examines:

- number of vertices and edges;
- vertex degree;
- graph diameter;
- shortest-path distances;
- distance distributions;
- metric-degree sequences;
- vertex symmetry; and
- comparison of computational results with theoretical expressions.

For the hypercube \(Q_n\), the notebook computationally verifies:

$$
|V(Q_n)| = 2^n,
$$

$$
|E(Q_n)| = n2^{n-1},
$$

$$
\deg(v)=n,
$$

and

$$
\operatorname{diam}(Q_n)=n.
$$

The distance analysis also verifies that the number of vertices at
distance \(i\) from a given vertex is

$$
d_i(v)=\binom{n}{i}.
$$

Consequently, the metric-degree sequence corresponds to the binomial
coefficients in the \(n\)-th row of Pascal's triangle.

For example, for \(Q_3\),

$$
(1,3,3,1).
$$

## Mathematical Motivation

My academic background includes MPhil research in graph theory, particularly
the study of metric-degree sequences and metric-degree polynomials of graphs
associated with algebraic structures.

The hypercube investigation in this repository is a separate introductory
computational study and is not a reproduction of my MPhil thesis results.

Future work will extend the repository toward computational investigations
of selected algebraic graph structures related to my previous mathematical
research.

## Tools

- Python
- NetworkX
- Pandas
- Matplotlib
- Jupyter Notebook

## Repository Contents

- `01_hypercube_graph_analysis.ipynb` — computational and theoretical
  investigation of hypercube graphs.

## Future Development

Planned extensions include:

- computational analysis of graphs associated with algebraic structures;
- metric-degree sequence calculations for additional graph families;
- metric-degree polynomial computation;
- comparison of computational results with theoretical results from
  selected graph-theory problems.

## Author

**Farhana Anjum**

MPhil Mathematics  
Research interests: Graph Theory, Mathematical Modelling, Numerical Methods,
Stochastic Processes and Scientific Computing
