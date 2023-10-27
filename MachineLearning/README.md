# Projeto de Machine Learning para MBA FLAI/FAMESP

## Descrição do Projeto
No Projeto Data Analytics foi construído um dashboard para controle de contas de condomínio, sendo que os dados usados no projeto foram obtidos de lançamentos contábeis desde junho de 2017.

Dentre as principais despesas mensais do condomínio destaca-se a conta de água, cujo percentual da despesa pode chegar a quase 25% do total.

Este trabalho tem como objetivo avaliar a série de dados relativos ao consumo de água nos últimos anos e construir um modelo de machine learning para prever o consumo dos próximos meses. A expectativa é que se possa fornecer alertas ao síndico do condomínio para que esse possa tomar ações para evitar o aumento de consumo de água. Por exemplo, fazendo campanhas para que os condôminos economizem água.

Para atingir o resultado esperado, o projeto foi construído utilizando técnicas de Séries Temporais com aprendizado de máquina.

Neste notebook estão as análises feitas sobre a série histórica, validações técnicas para garantir o uso de modelagem ARIMA e SARIMA, identificação de parâmetros de configuração dos modelos de machine learning a análise final sobre o melhor modelo obtido.

O conteúdo aqui apresentado foi construído com apoio de material dos módulos de Machine Learning do MBA FLAI/FAMESP. Também foram adaptados outros materiais colhidos em blogs que discorrem sobre as técnicas de modelagem para Séries Temporais.

## O que encontrar aqui

### Repositório do projeto 
[Repositório](https://bit.ly/kunyosi_mba_dashboard_dados_projeto) com os componentes utilizados no projeto:
- Notebook criado com a linguagem Python:
   - Consolidação de dados históricos para serem usados pelo Power BI.
   - Testes para integração entre Power BI e Python: geração de gráficos 
- Arquivos auxiliares utilizados no desenvolvimento do projeto

## Detalhes do projeto
Um pouco mais sobre o problema tratado
A série histórica utilizada neste projeto compreende dados de junho de 2017 a julho de 2023. Os dados foram obtidos em lançamentos contábeis registrados pela administradora do condomínio.

Os dados correspondem às cobranças emitidas pela companhia de fornecimento de água (SABESP). Nessa cobranças há o consumo de água, que o objeto de estudo deste projeto, e valor da cobrança.

O modelo de cobrança considera o número de residências no condomínio para que chegar a uma média de consumo por resisdência. Essa média é usada para identificar qual tarifa deverá ser paga. Na verdade, a tarifa possui um modelo de "degrau tarifário" de tal form aque quanto mais água é utilizada mais caro passa a ser o valor por metro cúbido.

De uma forma simplificada, se o consumo mensal de água for infereir a 2.300 m³, a conta tem valor em torno de R$ 20.000. Caso o consumo exceda o "degrau" de 2.300 m³, com um pequeno acréscimo de consumo da ordem de 10%, a conta pode aumentar em 40%.

Por se tratar de um despesa que pode desequilibrar as contas orçamentárias do condomínio, é importante monitorar o consumo de água e, sendo possível, antecipar ações que possam fazer com que o consumo fique abaixo do limite de 2.300 m³.

Expectativas e conclusções gerais
No início deste projeto a expectiva era usar as ferramentas de predição de dados aplicadas a Séries Temporais com o objetivo de se gerar predições que pudessem ser usados como alertas para o administrador do condomínio estar ciente de eventuais riscos de aumento nas despesas. Claramente, sabendo do aumento do consumo, também poderiam ser tomadas ações para evitar esse aumento.

No decorrer do desenvolvimento do projeto foi ficando claro que a análise gerada poderia certamente cumprir seu papel, porém com um "poder de assertividade" inferior ao inicialmente imaginado.

Como um "produto", talvez não seja adequado utilizar as análises produzidas como única fonte para tomada de decisão, por outro lado, esse "produto" poderia ser utilizado para apoiar determinadas decisões e servir de alerta para que outras análise pudessem ser avaliadas.

Do ponto de vista de aprendizado, o projeto aqui exposto explora os modelos tradicionais ARIMA e SARIMA e serve como roteiro para outros projetos aplicados a outros dados.

Que você leitor, aproveite este trabalho!

Ficarei contente em receber seus comentários!

Marcos Kunyosi out/2023

 

