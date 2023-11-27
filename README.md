# Dashboard Análise de dados Financeiros

O projeto foi desenvilvido durante as aulas do curso de Microsoft Power BI Para Business Intelligence e Data Science. E tem por objetivo explorar algumas informações do setor Financeiro de uma empresa.

| :rocket: Vitrine.Dev |    |
| -------------  | --- |
| :sparkles: Nome        | **Análise de Dados Financeiros**
| :computer: Tecnologias | Power BI (tecnologias utilizadas)
| :globe_with_meridians: URL         | [https://shre.ink/915C](https://acesse.dev/cgIG5)
| :bar_chart: Demais Projetos     | https://l1nk.dev/portfolio-mateus-alves-dos-santos


<!-- Inserir imagem com a #vitrinedev ao final do link -->
![](https://github.com/gitmattalves/Dashboard_analise_de_dados_financeiros/blob/main/dadosFinanceiros_IA.jpg#vitrinedev)

## Detalhes do projeto

O projeto tem por objetivo apresentar uma visão das receitas e despesas desta empresa, que solicitou a criação de um dashboard que permita analisar os seguintes indicadores financeiros:

1- Total de Receitas

2- Total de Despesas

3- Margem de Lucro

4- Total de Receitas Por Componente

5- Total de Despesas Por Componente em relação à média de Despesas

6- Total de Receitas e Despesas Por Componente e Por Ano, com a hierarquia
Tipo/Componente.

Além disso a empresa precisa identificar os segmentos onde Receitas e Despesas são
maiores e menores a fim de traçar seu plano estratégico.

#### Tratamento dos dados
Primeiramente, foi realizado algumas transformações para adequarmos os dados para as próximas etapas, como transformaros valores de datas e Valores em colunas. 
![](https://github.com/gitmattalves/Dashboard_analise_de_dados_financeiros/blob/main/tabelainicial.png#vitrinedev)

Para realizar a tranformação, foi utilizada  a função UnpivotOther:
![](https://github.com/gitmattalves/Dashboard_analise_de_dados_financeiros/blob/main/tabelaunpivot.png#vitrinedev)


#### Tabela de Medidas
Após a limpeza e tratamento dos dados, foi realizado a criação da tabela Medidas de Indicadores Financeiros e tambem a criação de novas medidas para facilitar a realização dos calculos desejados.
Foi então criada 4 as novas medidas: **Total de Receitas**, **Total de Despesas**, **Lucro** e **Margem de Lucro**.

![](https://github.com/gitmattalves/Dashboard_analise_de_dados_financeiros/blob/main/tabelademedidas.png#vitrinedev)

#### Primeiras Métricas
Os primeiros dados apresentados, foram criados através dos cartões de visualização por trazer infromações simples, com valores únicos em cada cartão.
Trazendo assim o total de receitas e despesas, assim como a margem de lucro da empresa.


![](https://github.com/gitmattalves/Dashboard_analise_de_dados_financeiros/blob/main/primeiras-metricas.png#vitrinedev)

#### Despesas e Receitas por componentes

Optou-se por realizar a representação dos valores em gráficos distintos para uma melhor representividade dos dados analisados.
Para o Total de Despesas x Componentes foi gerado o gráfico de área com uma representação da linha média de despesas da empresa.
Já para Receitas x Componentes, optpou-se por realizar o gráfico de barras para uma melhor quantificação dos dados das receitas apuradas pela empresa.

![](https://github.com/gitmattalves/Dashboard_analise_de_dados_financeiros/blob/main/metricas_secundarias.png#vitrinedev)

#### Matriz

A matriz traz de forma especificada, os dados de Despesas e Receitas por componentes e anos disponibilizados nos dado.


![](https://github.com/gitmattalves/Dashboard_analise_de_dados_financeiros/blob/main/matriz_financeira.png#vitrinedev)

Posteriormente, será explorado um pouco mais esses dados para a geração de mais métrica sobre os setor.
