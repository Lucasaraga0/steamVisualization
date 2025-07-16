# Os jogos mais vendidos

Os dados coletados aqui foram retirados do [SteamSpy](https://steamspy.com/), onde pegamos os 100 jogos mais vendidos da história da Steam, assim como nos [jogos bem avaliados](https://lucasaraga0.github.io/steamVisualization/bemAvaliados), fizemos o enriquecimento com as informações dos jogos fazendo requisições à API da Steam.

### Distribuição geográfica

É perceptível que existe uma grande vantagem dos Estados Unidos para os demais países, o que não é surpreendente uma vez que são os maiores expoentes do mercado ocidental de jogos, público majoritário da Steam.

[Visualização mapa]

Entretanto


### Distribuição de preço 

<iframe width="100%" height="473" frameborder="0"
  src="https://observablehq.com/embed/341a0af66730c2da?cells=viewof+histMV"></iframe>

- Mais 70% dos jogos custam menos de 20 dólares.
- 55% menos de 10 dólares.
- 37% são gratuitos.

Entretanto, quando observamos o último intervalo, vemos que ainda sim, existem jogos que conseguem performar bem, mesmo vendendo o jogo em seu preço máximo, de 60 dólares, são os chamados jogos AAA (*Triple A´s*). Esses jogos são caracterizados por terem orçamentos altíssimos e grandes equipes de desenvolvimento.

### Análise conjunta

Aqui temos as visualizações mostradas acima, juntamente de outras que abordam diferentes aspectos desses jogos.

<iframe width="100%" height="564" frameborder="0"
  src="https://observablehq.com/embed/341a0af66730c2da?cells=viewof+dashboardMaisVend"></iframe>

Diferentemente do scatterplot dos [bem avaliados](https://lucasaraga0.github.io/steamVisualization/bemAvaliados/), aqui crítica e usuários discordam bastante, em sua maioria, o público coloca a nota do jogo para baixo, tendo seu ponto máximo no jogo [NBA 2K20](https://store.steampowered.com/app/1089350/NBA_2K20/). Mas por que isso acontece, se tantas pessoas compraram o jogo como elas podem avaliá-los de forma tão baixa? 
- A primeira hipótese é que muitos usuários adquiriram jogos gratuitos para suas contas e, nesse caso, qualidade difere de quantidade, ou seja, os jogos foram adicionados à biblioteca e esquecidos lá.

- Lançamento problemático. É comum que um jogo extremamente antecipado tenha um lançamento ruim, com muitos problemas técnicos e performance abaixo do esperado. Alguns conseguem sair melhorar, mas a nota inicial é tão baixa que não é possível reverter a situação no metacritic. Um exemplo disso é [No Man's Sky](https://store.steampowered.com/app/275850/No_Mans_Sky/), que ficou possui userscore 41 no metacritic, mas em sua página da Steam possui 91% de aprovação em análises recentes.  

- Atualizações que pioram a performance do jogo e políticas desagradáveis, como excesso de microtransações.

Sobre os gêneros desses jogos, vemos que o gênero de ação é predominante, presente em 77 dos 100 jogos da lista. 

Além disso, os jogos, em sua maioria, foram lançados nos últimos 10 anos.