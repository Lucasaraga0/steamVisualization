# Os jogos bem avaliados

Para analisar os jogos mais bem avaliados fizemos o seguinte processo:
- Iniciamos com o scraping da página de busca de jogos, obtendo todos os jogos classificados como **extremamente positivos**.
- Desses jogos, filtramos para deixar apenas os 100 jogos com maior número número de avaliações.
- Depois disso, obtivemos as informações dos jogos utilizando a API da steam. 
- Por fim, para ter as notas do [metacritic](https://www.metacritic.com/), das notas dos jogos, tanto de críticos quanto de usuários.

Com isso esclarecido, podemos prosseguir para as visualizações. Algumas perguntas que podemos fazer:
- Existe um padrão de ocorrência dos gêneros desses jogos?
-  Quais os países de origem desses jogos?

Adendo: por convenção, nas visualizações a seguir utilizaremos a terminologia "Mais bem avaliados" ou somente "Bem avaliados", mesmo que o mais correto seja "Jogos bem avaliados com maior número de avaliações", por questões de espaço.

### Estudo de gênero

Na visualização a seguir a distribuição dos gêneros nos jogos bem avaliados

Percebe-se que existe uma certa margem entre os três primeiros para os demais, sendo eles, Ação, Indie e Aventura. Ação e Aventura são gêneros consagrados na indústria e sua presença não é nenhuma surpresa.

Jogos indie, por outro lado, aparecem como uma alternativa às frustrações recentes em relação as grandes empresas. Normalmente sendo feitos por equipes reduzidas, algumas vezes por uma única pessoa, esses jogos são procurados muitas vezes pois, segundo os jogadores, eles possuem *alma*.   


### Visualização final 
<iframe width="100%" height="637" frameborder="0"
  src="https://observablehq.com/embed/341a0af66730c2da?cells=viewof+dashboardBemAval2"></iframe>