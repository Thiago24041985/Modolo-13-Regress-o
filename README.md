# Modolo-13-Regress-o
Explorando a base de gorjetas

Exercicios 01 - Carregando os pacotes e a base, crie as variáveis necessárias como na aula, e reproduzindo esta regressão.

. Reproduzindo também o gráfico de dispersão dessas duas variáveis.

2. Mudança de perspectiva
Agora ajustei um modelo de regressão de tip_pct por net_bill. Construindo o gráfico de dispersão correspondente.

3. Comentando
Comparando os dois gráficos e comentando (de forma objetiva e suscinta) a relação entre eles e a diferença do ajuste. Podemos comparar diretamente os  R2 s?

4. Ajustando do modelo em outra escala
Com o modelo no item 3, obtendo a preditiva do valor da gorjeta:

obtendo o valor predito pred para tip_pct (dica, veja o atributo reg.fittedvalues)
obtendo o valor predito para tip como tip_pct * net_bill
calculando o  R2  do modelo para tip
comparando esse  R2  com o do item 1

O modelo utilizando tip ~ net_bill obteve uma pontuação maior quando olhamos o  R2 , explicando apoximadamente 33% do nosso modelo.


Exercicos 02 
1. Melhorando o ajuste no percentual de gorjetas
2. Vamos partir do modelo feito na última tarefa, o que relaciona tip_pct e net_bill. Carregando a base, os pacotes e reproduzindo este modelo aqui.
3.  ajustando o modelo de tip_pct em função do logaritmo de net_bill.
4.  ajustando o modelo de tip_pct em função de um polinômio de segundo grau em net_bill.
5.  ajustando um modelo no log do tip_pct em função de net_bill. Calculando o  R2  também em tip_pct
6.  ajustando um modelo no log do tip_pct em função do log de net_bill. Calculando o  R2  também em tip_pct.

Exercícios 03 
Carregando os pacotes necessários e a base de gorjetas.

I. Modelo no valor da gorjeta
Criando a matriz de design (e a matriz y) utilizando o Patsy, para um modelo em tip, explicada por sex, smoker, diner e net_bill.
Removendo as variáveis não significantes.
observando o gráfico de resíduos em função de net_bill
teste transformando net_bill no log e um polinômio. Escolhendo o melhor modelo.

II. Modelo no valor do percentual da gorjeta
Criando a matriz de design (e a matriz y) utilizando o Patsy, para um modelo no log de tip, explicado por sex, smoker, diner e net_bill.
Removendo as variáveis não significantes.
Observando o gráfico de resíduos em função de net_bill
Testando transformar net_bill no log e um polinômio. Escolha o melhor modelo.
Do modelo final deste item, calculando o  R2  na escala de tip (sem o log). Compare com o modelo do item 1. Qual tem melhor coeficiente de determinação?

Verificamos que as variáveis insignificantes são: sex e dinner

III. Previsão de renda
 trabalhar a base que você vai usar no projeto do final deste ciclo.

Carregando a base previsao_de_renda.csv.

  

