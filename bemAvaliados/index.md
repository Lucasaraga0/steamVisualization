
<a href="https://lucasaraga0.github.io/steamVisualization/" style="display:inline-block; padding:8px 16px; background:#222; color:white; text-decoration:none; border-radius:4px; margin-bottom:1em;">
  ⬅ Início
</a>


# Os jogos bem avaliados

Para analisar os jogos mais bem avaliados fizemos o seguinte processo:
- Iniciamos com o scraping da página de busca de jogos, obtendo todos os jogos classificados como **extremamente positivos**.
- Desses jogos, filtramos para deixar apenas os 100 jogos com maior número número de avaliações.
- Depois disso, obtivemos as informações dos jogos utilizando a API da Steam. 
- Por fim, para ter as notas do [metacritic](https://www.metacritic.com/), tanto de críticos quanto de usuários e, os países de origem dos jogos, fizemos o preenchimento manual dos conjuntos de dados.

Com isso esclarecido, podemos prosseguir para as visualizações. Algumas perguntas que podemos fazer:
- Existe um padrão de ocorrência dos gêneros desses jogos?
- Crítica e usuários tendem a concordar sobre os jogos bem avaliados?

Adendo: por convenção, nas visualizações a seguir utilizaremos a terminologia "Mais bem avaliados" ou somente "Bem avaliados", pela praticidade, mesmo que o mais correto seja "Jogos bem avaliados com maior número de avaliações".

## Análise de gênero

Na visualização a seguir, temos a distribuição dos gêneros nos jogos bem avaliados


<div style="width: 100%; display: flex; justify-content: center; margin: 2rem 0;">
  <div style="width: 800px;">
    <iframe 
      src="https://observablehq.com/embed/341a0af66730c2da@1258?cells=viewof+barrasBA"
      style="width:  800px; height: 470px; border: none; display: block; background: white;"
      scrolling="no"
      frameborder="0"
      loading="lazy"
      allowfullscreen>
    </iframe>
  </div>
</div>




Percebe-se que existe uma certa margem entre os três primeiros para os demais, sendo eles, Ação, Indie e Aventura. Ação e Aventura são gêneros consagrados na indústria e sua presença não é nenhuma surpresa. Jogos indies, por outro lado, aparecem como uma alternativa às frustrações recentes em relação as grandes empresas, representando os jogos de menor escala e feitos por pequenas equipes de desenvolvedores.

Simulação, RPG e Estratégia formam um "segundo pelotão" de gêneros, também tendo uma participação significativa. 

---

## Crítica x Usuários

Não faltam, na história, exemplos de obras rejeitadas pela crítica e amadas pelo público ou o caminho inverso. No entanto quando observamos os resultados do nosso comparativo, é perceptível que na grande maioria dos casos, público e crítica concordaram sobre os jogos. Entretanto, existe apenas um *outlier*, [Postal 2](https://store.steampowered.com/app/223470/POSTAL_2/), conhecido pelo humor ácido e a violência extrema, um jogo polêmico e que divide opiniões, tendo esse comportamento refletido no scatterplot gerado abaixo.

<div style="width: 100%; display: flex; justify-content: center; margin: 2rem 0;">
  <div style="width: 1100px;">
    <iframe 
      src="https://observablehq.com/embed/341a0af66730c2da@1261?cells=viewof+scatBA"
      style="width: 1100px; height: 580px; border: none; display: block; background: white;"
      scrolling="no"
      frameborder="0"
      loading="lazy"
      allowfullscreen>
    </iframe>
  </div>
</div>

---

## Dashboard interativo

No painel abaixo agrupamos as visualizações já mostradas acima com outras que explorar demais aspectos dos jogos bem avaliados.


<div style="width: 100%; display: flex; justify-content: center; margin: 2rem 0;">
  <div style="width: 1100px;">
    <iframe 
      src="https://observablehq.com/embed/341a0af66730c2da?cells=mapaBemAvaliados%2Cviewof+dashboardBemAval2"
      style="width:  1100px; height: 1158px; border: none; display: block; background: white;"
      scrolling="no"
      frameborder="0"
      loading="lazy"
      allowfullscreen>
    </iframe>
  </div>
</div>



Voltando para a discussão sobre os gêneros ... Observamos que os jogos indie em sua maioria não passam de 20 dólares e tiveram um grande crescimento entre 2015 e 2020.

Além disso, temos apenas um jogo gratuito, [Life is Strange - Episode 1](https://store.steampowered.com/app/319630/Life_is_Strange__Episode_1/), que na verdade é apenas a primeira parte de um jogo completo, vendido em partes pela plataforma.

Sobre a distribuição geográfica, percebe-se um domínio dos Estados Unidos, com 33 jogos na lista, mais de 20 de distância do segundo colocado, o Canadá, que possui 12 jogos. 


- [Os jogos mais vendidos da steam.](https://lucasaraga0.github.io/steamVisualization/maisVendidos)
- [Os jogos em alta durante o mês de junho.](https://lucasaraga0.github.io/steamVisualization/emAlta)