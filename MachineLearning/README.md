# Projeto de Machine Learning para MBA FLAI/FAMESP

## Descrição do Projeto
Este projeto de Machine Learning é uma extensão de um trabalho anterior de Data Analytics, no qual desenvolvemos um dashboard para monitorar as contas do condomínio, com histórico desde junho de 2017.

Dentre as despesas mensais mais significativas do condomínio, destaca-se a conta de água, que pode representar quase 25% do total.

O objetivo principal deste trabalho é avaliar a série temporal do consumo de água ao longo dos últimos anos e construir um modelo de machine learning capaz de prever o consumo para os próximos meses. A intenção é fornecer alertas ao síndico do condomínio, permitindo que ele tome medidas proativas para evitar aumentos excessivos no consumo de água. Isso pode incluir campanhas de conscientização para os condôminos sobre a importância da economia de água.

Para alcançar esse objetivo, aplicamos técnicas de Séries Temporais em conjunto com aprendizado de máquina. Neste notebook, você encontrará análises da série histórica, validações técnicas para garantir o uso adequado dos modelos ARIMA e SARIMA, além da identificação dos parâmetros de configuração dos modelos de machine learning e uma análise final do melhor modelo obtido.

O conteúdo apresentado foi desenvolvido com o apoio dos materiais dos módulos de Machine Learning do MBA FLAI/FAMESP, bem como a adaptação de informações provenientes de blogs especializados em técnicas de modelagem para Séries Temporais.

## O que encontrar aqui

### Notebook python
O notebook utilizado está [nesse link](https://bit.ly/kunyosi_mba_nb_ml_st), nele há detalhes da análise da série temporal de consumo de água.

### Repositório do projeto 
[Repositório](https://bit.ly/kunyosi_mba_ml_dados_projeto) com os componentes utilizados no projeto:
- Notebook criado com a linguagem Python com a análise da série temporal   
- Arquivos auxiliares utilizados no desenvolvimento do projeto


## Um pouco mais sobre o problema abordado

A série histórica utilizada neste projeto compreende dados de junho de 2017 a julho de 2023, obtidos a partir dos lançamentos contábeis registrados pela administradora do condomínio.

Os dados correspondem às cobranças emitidas pela companhia de fornecimento de água, no caso, a SABESP. Essas cobranças incluem informações sobre o consumo de água, que é o foco deste projeto, bem como o valor da cobrança.

O modelo de cobrança considera o número de residências no condomínio para calcular a média de consumo por residência. Essa média é usada para determinar qual tarifa deve ser aplicada. A tarifa segue um modelo de "degrau tarifário", onde o custo por metro cúbico de água aumenta à medida que o consumo ultrapassa determinados limites.

De forma simplificada, se o consumo mensal de água ficar abaixo de 2.300 m³, a conta geralmente tem um valor em torno de R$ 20.000. No entanto, se o consumo exceder esse limite de 2.300 m³, com um acréscimo relativamente pequeno de cerca de 10% no consumo, o valor da conta pode aumentar em até 40%.

Devido ao potencial de impacto nas finanças do condomínio, é fundamental monitorar de perto o consumo de água e, sempre que possível, antecipar ações que ajudem a manter o consumo abaixo do limite de 2.300 m³.

## Expectativas e Conclusões Gerais

No início deste projeto, a expectativa era utilizar técnicas de previsão de dados aplicadas a Séries Temporais, com o objetivo de gerar previsões que pudessem funcionar como alertas para o administrador do condomínio, auxiliando na identificação de potenciais riscos de aumento nas despesas. Com o conhecimento antecipado do aumento do consumo, seriam tomadas ações proativas para evitá-lo.

À medida que o projeto foi se desenvolvendo, tornou-se evidente que as análises produzidas poderiam desempenhar esse papel, mas com um grau de precisão um pouco inferior ao que inicialmente foi imaginado.

Como "produto", talvez não seja apropriado confiar exclusivamente nas análises geradas para a tomada de decisões. No entanto, essas análises podem servir como um suporte valioso para determinadas decisões e alertar para a necessidade de avaliar outras análises em conjunto.

Do ponto de vista do aprendizado, este projeto explora os modelos tradicionais ARIMA e SARIMA, servindo como um guia para projetos futuros em diferentes conjuntos de dados.

Agradeço por estar aqui, aproveite o conteúdo!

Fico à disposição para receber seus comentários.

Marcos Kunyosi
out/2023

 

