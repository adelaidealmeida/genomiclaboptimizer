
# GenomicLabOptimizer

Optimal Resource Allocation in Genomic Laboratories using Integer Linear Programming
Based on the article: "Optimal Allocation of Laboratory Resources for Genomic Experiments Using Integer Linear Programming"
Authors: Tavares, J.W.R., Evangelista, A., De Oliveira, A.
This repository implements an Integer Linear Programming (ILP) model to optimize resource allocation in genomic laboratories, based on the aforementioned article.
Features:

Mathematical formulation of the problem (variables, objective function and constraints)
Modeling and solving via Pyomo with support for GLPK and CBC solvers

Analysis of:

Experiment efficiency (p/t, p/r and p/h ratios)
Resource usage and bottleneck resource identification
Performance comparison between solvers (total time, solving time and objective value)

Generation of graphical visualizations:

Optimal quantity of experiments
Resource utilization
Efficiency ratios
Performance comparison between solvers

Main dependencies:

Python ≥ 3.8
Pyomo
GLPK and/or CBC installed and accessible via PATH
Matplotlib, Pandas, NumPy, Seaborn

▶How to Run:
1- Run pli_v3_20250717.ipynb
2- Run variancy.ipynb
3- Select the attributes from step 2 and run graphic_solution.ipynb






# GenomicLabOptimizer
Alocação Ótima de Recursos em Laboratórios Genômicos usando Programação Linear Inteira Baseado no artigo: "Optimal Allocation of Laboratory Resources for Genomic Experiments Using Integer Linear Programming" Autores: Tavares, J.W.R., Evangelista, A., De Oliveira, A. 

Este repositório implementa um modelo de Programação Linear Inteira (PLI) para otimizar a alocação de recursos em laboratórios genômicos, com base no artigo:

Funcionalidades:
Formulação matemática do problema (variáveis, função objetivo e restrições);
Modelagem e resolução via Pyomo com suporte aos solvers GLPK e CBC;

Análises de:
Eficiência dos experimentos (razões p/t, p/r e p/h);
Uso de recursos e identificação do recurso gargalo;
Comparação de desempenho entre solvers (tempo total, tempo de resolução e valor objetivo);

Geração de visualizações gráficas:
Quantidade ótima de experimentos;
Utilização de recursos;
Razões de eficiência;
Comparativo de desempenho entre solvers.

Dependências principais:
Python ≥ 3.8
Pyomo
GLPK e/ou CBC instalados e acessíveis via PATH

Matplotlib, Pandas, NumPy, Seaborn

▶Como executar:
1- Execute pli_v3_20250717.ipynb
2- Execute variancy.ipynb
3- Selecione os atributos do passo 2 e rode graphic_solution.ipynbgraphic_solution.ipynb
