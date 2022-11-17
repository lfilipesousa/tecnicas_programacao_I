## Repositório referente ao projeto do final do módulo de técnicas de programação I 
___

 Módulo do curso de ciência de dados da let's code em parceria com a Suzano.
___

O trabalho consiste em fazer uma limpeza e extração de dados de alguns arquivos em csv. Os dados usados nesse projeto são de investidores e não são reais.

São 3 arquivos que devem ser carregados para responder as perguntas.

- Arquivo cadastro.csv

- Arquivo investimento.csv (dividido em 2 partes)

1 - Carregar os arquivos e cadastro, investimento1 e investimento2 e mostrar a quantidade de linhas de cada um, além das informações desses dataframes

2 - Juntar os dataframes de investimento1 e investimento2 em um só e ver a quantidade de linhas

3 - Crie um novo dataframe eliminando as linhas duplicadas

4 - Junte o dataframe de investimento com o de cadastro

5 - Ordene o dataframe pelo id, de forma crescente e redefina o índice

6 - Faça uma análise dos dados faltantes e trate-os

        Mostre todas as colunas com dados faltantes, sua quantidade/porcentagem e como tratar (preencher) cada uma delas explicando sua estratégia

7 - Manipule os dados a seguir:
- Criar coluna "Total" somando o valor de todos os ativos por investidor
- Criar coluna "Media" com a média das notas 1 e 2
- Criar coluna "Dominio" com apenas o domínio do email (dica: separar por @)
- Mudar o nome da coluna "Salário" para "Renda" e tratar a coluna (sem caracter $ e tipo numérica)
- Mudar os dados da coluna "Sexo" para Masculino e Feminino (tente usar o map)
- Transformar os dados da coluna Media em inteiro
- Criar coluna "NPS" onde o investidor é promotor se a média das notas é maior igual a 80, neutro se a média estiver entre 50 e 80, e detrator se for abaixo de 50

8 - Calcule os seguintes dados

- Calcule o total investido em cada coluna Ativo (tente usar o apply)
- Qual o menor valor investido em cada ativo?
- Mostre a média e desvio padrão de cada ativo
- Qual a idade do investidor mais velho?
- Qual a mediana da coluna Média?

9 - Responder as perguntas abaixo

- Quantos investidores são promotores?
- Quantos investidores são do sexo feminino?
- Quantos investidores investiram mais de 16000 no Ativo04?
- Quantos investidores investiram mais de 16000 no Ativo04 e menos de 5000 no Ativo05?
- Quantos investidores do sexo feminino tem mais de 25 anos e investiu menos de 10000? (bonus: por que esse dado seria importante para a estratégia da nossa empresa?

- Quantos investidores tem em cada estado (dica: use groupby)
- Qual é a soma do total investido por cada estado?
- Como os investidores se distribuem em promotores, detratores e neutros?
- Qual é a média do total investido por promotores, detratores e neutros?
.