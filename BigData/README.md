# Projeto de Big Data para MBA FLAI/FAMESP

## **Exploração de Dados na Bolsa de Valores B3**

Este projeto analisa dados da bolsa de valores B3 com uma ferramenta bastante usada em ambientes de _big data_, o PySpark.

Os dados aqui trabalhados apresentam movimentações de negócios realizadas no ano de 2023, entre janeiro e outubro. O dados foram obtidos no [site da B3](https://www.b3.com.br/pt_br/market-data-e-indices/servicos-de-dados/market-data/historico/mercado-a-vista/cotacoes-historicas/) e também está disponível [neste link](https://drive.google.com/file/d/1ZWxJCKOgXmBnzkAa5GP2IhdDFCl4PEOw).

Os dados originais foram fornecidos em um arquivo compactado, cujo volume é de 58 MB, sendo que depois da descompactação, o conteúdo se expande para 465 MB. Apesar de não ter o volume expressivo do contexto de _big data_ trata-se de um arquivo grande para ser manipulado em ferramentas mais simples, assim, foi escolhido para ser usado neste projeto, que é parte integrante do MBA FLAI/FAMESP.

## O que encontrar aqui

### Notebook python
O notebook utilizado está [neste link](https://bit.ly/kunyosi_mba_nb_bd), nele há detalhes de como o código foi construído e como as análises foram feitas.

### Base de dados utilizada 
Os dados utilizados neste projeto estão disponíveis no [site da B3](https://www.b3.com.br/pt_br/market-data-e-indices/servicos-de-dados/market-data/historico/mercado-a-vista/cotacoes-historicas/) e também [neste link](https://drive.google.com/file/d/1ZWxJCKOgXmBnzkAa5GP2IhdDFCl4PEOw).


## **Plano de trabalho**

Neste trabalho, exploramos as seguintes etapas:

1. **Tratamento de Dados com PySpark:**
Utilizamos o PySpark para realizar a limpeza e preparação dos dados.
Esta etapa é fundamental para garantir a qualidade das análises subsequentes.

2. **Seleção de Dados com PySpark:**
Utilizamos o PySpark para selecionar dados relevantes da base de dados da B3, gerando uma espécie de resumo para as próximas etapas de processamento e análise.

3. **Geração de Dataframes em Pandas:**
Para análises mais específicas e detalhadas, transformamos os dados em dataframes do Pandas.
Isso nos permitiu realizar análises mais granulares, incluindo a geração de gráficos e visualizações, de onde é possível extrair _insights_ para novas análises e tirar conclusões para as perguntas formuladas a respeito do contexto do ambiente de negócios.

### **Prova de Conceito**

Embora os dados utilizados neste trabalho não atinjam a escala tradicionalmente associada ao _big data_,
o objetivo principal é demonstrar o potencial do PySpark na manipulação de grandes volumes de dados.

Dessa forma, o código aqui aparensetado serve como uma prova de conceito e pode ser referência para projetos futuros.

### **Análises Propostas**

As análises realizadas neste trabalho incluem:

- Análise dos tipos de mercados presentes na B3.
- Análise das empresas com ações listadas na bolsa.
- Análise da evolução de preços de ações negociadas ao longo dos meses.

Agradeço seu interesse neste conteúdo e ficarei ainda mais grato recebendo seus comentários!

*Marcos Kunyosi*  
*Outubro/2023*
