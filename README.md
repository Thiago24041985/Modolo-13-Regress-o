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

