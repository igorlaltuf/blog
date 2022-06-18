---
date: "2022-06-18T10:00:00Z"
external_link: ""
type: project
image:
  caption: Logo by r-project.org
  focal_point: Smart
summary: Acesse os pedidos, as respostas e recursos realizados via Lei de Acesso à Informação (LAI) no R.
tags:
- Linguagem R
- Pacotes
- Software
links:
- name: CRAN
  url: https://cran.r-project.org/web/packages/dail/index.html
title: O pacote DAIL - Data from Access to Information Law
url_code: "https://github.com/igorlaltuf/dail"
url_pdf: ""
url_slides: ""
url_video: ""
---

A Lei de Acesso à Informação brasileira ([Lei nº 12.527/2011](http://www.planalto.gov.br/ccivil_03/_ato2011-2014/2011/lei/l12527.htm)) entrou em vigor em 16 de maio de 2012 e representou uma evolução no acesso aos dados públicos. Ela permite, de forma gratuita, o acesso a qualquer informação pública produzida ou custodiada pelos órgãos e entidades da Administração Pública, salvo algumas exceções. Tampouco existe a necessidade de justificar a razão pela qual os dados estão sendo solicitados.

Entretanto, nem tudo são flores. Existe um prazo de 20 dias, prorrogável por mais 10 dias, para que os órgãos públicos respondam ao pedido. Pela minha experiência pessoal, imagino que pela quantidade de demandas que estas instituições recebem, as respostas costumam ser enviadas perto do fim do prazo. Ou seja, dificilmente você terá a sua resposta na mesma semana em que realizou o pedido. 

O pacote [DAIL](https://cran.r-project.org/web/packages/dail/index.html) (Data from Access to Information Law/Dados da Lei de Acesso à Informação) foi desenvolvido pensando na possibilidade de que alguém já tenha feito a mesma pergunta que você pretende fazer e até mesmo auxiliar na etapa de análise exploratória de uma pesquisa. Ele permite acessar via R os dados dos pedidos e recursos no âmbito da Lei de Acesso à Informação (LAI) - Lei 12.527/2011 - disponibilizados pela Controladoria-Geral da União (CGU).

Vale ressaltar que os conteúdos dos pedidos, das respostas e dos recursos foram disponibilizados apenas a partir do ano de 2015. Segundo a CGU, isso se dá em função das necessidades de regulamentação e da prévia orientação/capacitação operacional dos órgãos federais para tal abertura de dados, o que só aconteceu em 18 de maio de 2015 por meio da [Portaria Interministerial nº 1.254/2015](https://www.gov.br/acessoainformacao/pt-br/assuntos/legislacao-relacionada-1/cgu-prt-inter-1254.pdf). Por esta razão não é possível acessar os dados contendo os pedidos e recursos do ano de 2012 até 2014.

Em breve será disponibilizado no blog um tutorial sobre como usar o pacote. Por enquanto, existe um passo a passo na página do projeto no [GitHub](https://github.com/igorlaltuf/dail). 
