Neural Module Networks for Reasoning over Text (NMN)

General View

- Parsed a reasoning question into an executable program, which captures the abstract compositional reasoning structure required to answer the question correctly.
- Defined embeddings for several modules to perform reasoning: find, filter, relocate, find-num, find-date, count, compare-num-lt time-diff, find-max-num, span

Motivations

- To understand the compositional reasoning structure of the questions:

Perform accurate information extraction from the passage (eg. extract lengths, kickers, etc. for the field goals and touchdowns)

Perform symbolic reasoning (eg. counting, sorting, comparisions, couting etc.)

Contributions

- Introducing differentiable modules that perform symbolic (such as arithmetic, sorting, counting) reasoning over text and symbols in a probabilistic manner. 
- Proposing an unsupervised auxiliary loss to help extract arguments associated with the events in text.
- Interpretability, compositionality, and improved generalizability

Expriment 

- Mannuly categorize question types
- Using curriculum learning and injecting inductive bias using unsupervised auxiliary losses to improve learning.

Quesitons

- Auxiliary supervision: why should define auxiliary loss for find-num, find-date, relocate module? (injecting inductive bias using unsupervised auxiliary losses significantly helps learning.)
- How to improve the expressivity of NMN as compared to more black box models?
