# A Simpy/Z3 implementation of a fictional printer case
See:
- [Python executable](compute_cost_ecdfs.py)
- [Possible base DSL instance](dsl_instance.txt)
- [Possible base DSL grammar](dsl_grammar.txt)

A SimPy/z3 implementation of a fictional printer cases. The printer consists of multiple parts, which are prices either non-determinsitcally or probabilistically.

Monte Carlo simulation is used to deal with the probabilistic part by running many Z3 solver computations with different inputs for the probabilistic prices. The code executes according to the following flow diagram:
![Mermaid diagram](mermaid-diagram.png)

A PDF, eCDF, inverse eCDF, respectively, that each contain the lower bound and one for the upper bound are the result of executing the code, as follows.
![PDF](printer_cost_pdf.png)

![eCDF](printer_cost_ecdf.png)

![inverse eCDF](printer_cost_inverse_ecdf.png)
