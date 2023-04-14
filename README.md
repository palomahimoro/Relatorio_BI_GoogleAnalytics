# Relatorio_BI_GoogleAnalytics

 Mini Projeto 1

Uma empresa comercializa produtos online. A empresa configurou o Google Analytics para extrair dados sobre o perfil dos visitantes do portal de e-commerce e agora o Gestor da área de Marketing gostaria de ter as respostas às perguntas abaixo:

1.Como os clientes mais acessam nosso portal, por busca orgânica ou paga?
2.Quanto tempo em média um visitante permanece em nosso portal por dia do mês?
3.Qual a principal fonte de acesso ao nosso portal?4.Qual o sistema operacional mais usado para acessar nosso portal?
5.Qual o dispositivo mais usado para acesso ao nosso portal?
6.Qual o total de faturamento por dia?

KPI- indicador chave de performance 
-
Para conectar no Google Analytics> pag inicial> obter dados> serviços online> google analytics

O que é estatística?
conjunto de métodos usada para analisar dados, é um dos pilares da ciencia de dados

Probabilidade é o estudo da aleatoridade e da incerteza.

Estatística Inferencial é o processo de estimar informações sobre uma população a partir dos resultados observados em uma amostra.

Estatística  é  a área  de  conhecimento,  parte  da  Matemática  Aplicada,  que  fornece métodos para coletar, descrever, analisar, apresentar e interpretar dados, para a utilização dos mesmos na tomada de decisões.
Big Data Analytics é o termo que se refere a análise estatística de grandes quantidades de dados, para que se possa extrair informação relevante para a compreensão da situação atual e a tomada de decisões.

Parâmetro- característica sobre a população. Valores calculados usando dados da população.
Estatística- característica sobre a amostra.
Valores calculados usando dados da amostra.

Medidas de Posição: Média, mediana e moda.

A média de uma variável é a soma de todos os regisgtros de uma variável dividido pelo número de registros. 

Definimos a Mediana de um conjunto de dados como o valor que divide um conjunto de dados (ordenados) em duas partes com a mesma quantidade de dados. 

Moda é o valor de maior frequência na amostra, o que aparece mais frequentemente no conjunto de dados.

As duas principais medidas de dispersão: variância (mede a amplitude/ a variabilidade dos dados em relação à média) e desvio padrão (usado para medir a variabilidade entre os números em um conjunto de dados. Assim, o desvio padrão é um padrão de desvio (distância) da média. 

Medidas de Posição Relativa

Os dados podem ser medidos em termos de posição relativa, que compara a posição de um valor, em relação a outro valor dentro do conjunto de dados. 

Percentil e quartil são as medidas mais comuns de posição relativa. 

Percentil e Porcentagem não são a mesma coisa.

Porcentagem é a proporção calculada em relação a uma grandeza de cem unidades. A porcentagem pode ser encontrada multiplicando o valor numérico por 100. 

Percentil é o ponto de distribuição dos resultados ordenados da amostra (por ordem crescente dos dados) em 100 partes de igual amplitude. Por ex.: um resultado no percentil 90 significa que 90% dos resultados se situam nesse ponto ou abaixo dele. 

Quartis são valores que dividem uma tabela de dados em quarto partes iguais. 

Um arquivo batch é um arquivo texto contendo linhas com comandos que podem ser executados sequencialmente pelo interpretador de comandos do MS-DOS, Windows ou OS/2. São identificados pelas extensões .bat ou .cmd. 

Métodos Estatísticos para Análise de Dados
Média
Mediana
Moda
Quartis
Desvio Padrão
Variância
Intervalo Interquantil
Coeficiente de Variação
Coeficiente de Assimetria
Curtose
Coeficiente de Correlação Linear
Covariância
Coeficientes de Associação

A técnica utilizada vai depender do tipo de variável
Qualitativas ou Quantitavas

Qualitativas (nominais- profissão, sexo, religião ou ordinais- escolaridade, classe social, fila). 

Quantitativas (discretas- número de filhos, número de carros, número de acessos ou contínuas- altura, peso, salário). 

A Tabela de Frequência indica a frequência observada, ou seja, mostra a frequência com que cada observação aparece nos dados.Para descrevermos um conjunto de dados, definimoso que são classes de frequência, isto é, intervalos da variável de interesse, e verificaremos o número de dados neste intervalo.Isso nos  dá  a  Distribuição  de  Frequência,  que é  a  associação  das  frequências  aos  valores  obtidos correspondentes, o que nos permite ter uma representação gráfica da amostra, que já nos diz muitas coisas sobre a população.Para criar uma tabela de frequência precisamos definir:•Número de classes•Amplitude das classes•Ponto inicialA frequência pode ser:•Absoluta•Relativa

A Tabela de Contingência é outro tipo de ferramenta de análise de dados muito utilizada. Seu objetivo é analisar dados com mais de uma variável envolvida.

O Gráfico de Pareto éum tipo de gráfico de barras que permite ordenar as frequências das ocorrências de modo a priorizar os problemas vitais e eliminar futuras perdas.

O propósito de um histograma, é oferecer uma descrição geral sobre os dados e não sobre os dados individualmente. Um histograma pode resumir as características dos dados numéricos. O histograma se parece com um gráfico de barras, mas possui algumas diferenças. O objetivo é visualizar  de  que  forma  os  dados  se  distribuem  pelos  diversos  valores  diferentes  observados (onde é mais comum, onde é mais raro).

O propósito de um HISTOGRAMA é oferecer uma descrição geral sobre a distribuição de uma variável.

O   Gráfico   de   Dispersão   ou   Scatter   Plot, mostra   a   relação   entre   duas   variáveis quantitativas. Cada par observado de duas variáveis (x, y) é marcado como um ponto a partir de suas coordenadas.

O Boxplot (também chamado de whisker plot) exibe a distribuição de dados com base no resumo de cinco números: mínimo, primeiro quartil, mediana, terceiro quartil e máximo.Embora o  Box  plot  forneça  informação  sobre  localização  e  dispersão,  seu  verdadeiro  valor  está  na informação que fornece sobre a cauda da distribuição. Pontos extremos(Outliers) podem afetar de  forma  adversa  as  decisões  a  serem  tomadas  a  partir  da  análise  dos  dados  se  não  forem devidamente  considerados.  O  Box  Plot é  uma  ferramenta  gráfica  que  ajuda  a  identificar  a existência de possíveis outliers no conjunto de dados.

Os outliers (VALORES ATÍPICOS) são dados que se diferenciam drasticamente de todos os outros. Em outras palavras, um outlier é um valor que foge da normalidade

Cap 12.

Linguagem R 

Após baixar o app R base, o tools e o studio para customizar o rstudio, abrir ele> tools> global optations.

setwd serve para direcionar para onde está o trabalho então setwd("C:\Users\Paloma\Dropbox\Paloma\My PC (DESKTOP-B8PFO69)\Desktop\PowerBI\Cap12)"
getwd()

Caso apresente erro...

A linguagem R foi criada a partir da Linguagem C(Linux), dessa forma, não reconhece a contrabarra, somente a barra, então alterar para: 
("C:/Users/Paloma/Dropbox/Paloma/My PC (DESKTOP-B8PFO69)/Desktop/PowerBI/Cap12")
getwd()

Carregando o dataset
Vendas <- chamar a função: read.csv("vendas.csv",fileEnconding="windows-1252")

Resumo do dataset
View(vendas)
str(vendas)
summary(vendas$Valor)
summary(vendas$Custo)

Às vezes, é necessário alterar o Enconding(save with enconding, todo arquivo tem uma codificação) para o UT-8, assim, como no power bi, a forma vai ser um pouco diferente, mas o conceito é o mesmo. 

Variância e desvio padrão - medidas de dispersão

tabela de frequencia é uma tabela de contagem valores de uma variável.



