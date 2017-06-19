# cn-rede

Desenvolvimento de um framework de redes mulilayer temporais para análise do congresso nacional <sup>[1](#myfootnote1)</sup>. O framework tem como características desejadas a modularidade, robustez e simplicidade. *Modularidade* pois permite a adição de novas redes sem perda de generalidade; *Robustez* por ser independente do tempo e de eventuais mudanças pontuais na estrutura organizacional do Congresso Nacional; e *Simplicidade* por buscar ter poucas premissas iniciais. 

### Objetivos

1. Analisar a estrutura macro da rede como as propriedades:
  - Tipo de rede (Random, Tree...)
  - Propriedades (Small World ...)
2. Encontrar subgrupos de parlamentares com atuação conjunta
  - Usar framework do paper em refrência para análise dos cores e dinâmica social <sup>[2](#myfootnote2)</sup>
3. Analisar importância e centralidade dos congressistas
  - Usar medidas de centralidade como PageRank, CI,... <sup>[3](#myfootnote3)</sup>
 
### Bases de Dados 

Algumas bases de dados podem ser usadas como indicadores de atividade parlamentar. Escolhemos duas delas (em negrito) para testar o modelo devido sua usabilidade e acessibilidade. Também, porque são dados atualizados com alta frequência, permitindo previsões do modelo no curto prazo.

- **Especies Legislativas** <sup>[4](#myfootnote4)</sup>
- **Votações em Plenário**
- Eventos
- Partidos
- Frentes Parlamentares
- Blocos
- Twitter
- UF
- Gastos
- Financiamento de Campanha
  

<a name="myfootnote1">1</a>: K. Wehmuth, ??ric Fleury, and A. Ziviani, “Multi aspect graphs: Algebraic representation and algorithms,” Algorithms, vol. 10, no. 1, pp. 1–59, 2017.

<a name="myfootnote2">2</a>: V. Sekara, A. Stopczynski, and S. Lehmann, “Fundamental structures of dynamic social networks,” Jun. 2017.

<a name="myfootnote3">3</a>: S. Luo, F. Morone, C. Sarraute, M. Travizano, and H. A. Makse, “Inferring Personal Economic Status from Social Network Location,” Nat. Commun., no. May, pp. 1–7, 2017.

<a name="myfootnote4">4</a>: W. K. Tam Cho and J. H. Fowler, “Legislative Success in a Small World: Social Network Analysis and the Dynamics of Congressional Legislation,” J. Polit., vol. 72, no. 1, pp. 124–135, 2010.
