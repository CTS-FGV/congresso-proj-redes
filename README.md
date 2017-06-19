# cn-rede

Development of a framework of temporal mulilayer networks for analysis of the national congress <sup>[1](#myfootnote1)</sup>. The framework has as desired characteristics the modularity, robustness and simplicity. * Modularity * because it allows the addition of new networks without loss of generality; * Robustness * because it is independent of time and occasional changes in the organizational structure of the National Congress; And * Simplicity * for seeking to have few initial premises.

The basic structure of the network has nodes as parliamentarians and database-related edges. For instance, in the case of *Law Proposals*, the edges will exist if the parliamentarians have acted in the same law.

### Goals

1. Analyze the macro structure of the network as the properties:
  - Type of network (Random, Tree ...)
  - Properties (Small World ...)
2. Finding subgroups of parliamentarians working together
  - Use the paper framework in reference to color analysis and social dynamics. [2](#myfootnote2)</sup>
  - Identify if subgroups are thematic: Health, Education ...
3. Analyze the importance and centrality of the congressmen
  - Use centrality measures like PageRank, CI, ... <sup>[3](#myfootnote3)</sup>
  - Identify topics that are more important for the congressman and their relevance in the theme.
 
### Data base

Some databases can be used as indicators of parliamentary activity. We chose two of them (in bold) to test the model due to its usability and accessibility. Also, the data is updated with high frequency which allows forecasts of a model in a short term period.

- ** Law Proposals ** <sup>[4](#myfootnote4)</sup>
- ** Roll Call **
- Events
- Matches
- Parliamentary Fronts
- Blocks
- Twitter
- UF
- Spending
- Campaign Funding
  

<a name="myfootnote1">1</a>: K. Wehmuth, ??ric Fleury, and A. Ziviani, “Multi aspect graphs: Algebraic representation and algorithms,” Algorithms, vol. 10, no. 1, pp. 1–59, 2017.

<a name="myfootnote2">2</a>: V. Sekara, A. Stopczynski, and S. Lehmann, “Fundamental structures of dynamic social networks,” Jun. 2017.

<a name="myfootnote3">3</a>: S. Luo, F. Morone, C. Sarraute, M. Travizano, and H. A. Makse, “Inferring Personal Economic Status from Social Network Location,” Nat. Commun., no. May, pp. 1–7, 2017.

<a name="myfootnote4">4</a>: W. K. Tam Cho and J. H. Fowler, “Legislative Success in a Small World: Social Network Analysis and the Dynamics of Congressional Legislation,” J. Polit., vol. 72, no. 1, pp. 124–135, 2010.
