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
Basta rodar o script principal:
