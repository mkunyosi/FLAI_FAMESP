# Projeto de Data Analytics para MBA FLAI/FAMESP

## Descrição do Projeto
Este projeto de Data Analytics foi desenvolvido como parte do programa MBA da FLAI/FAMESP. Foi desenvolvido um _dashboard_ para o controle de contas de condomínio, criando-se, assim, uma ferramenta eficaz para a gestão financeira e operacional de condomínios.

## O que encontrar aqui
### Vídeo de apresentação do projeto 
[Vídeo de apresentação do projeto]( https://bit.ly/kunyosi_mba_dashboard) 
contendo uma visão geral de como o projeto foi desenvolvido.

### Dashboard 
Acesso ao [_Dashboard web_]( https://bit.ly/kunyosi_mba_dashboard_web) desenvolvido.

### Apresentação do projeto
O arquivo  [Apresentação_do_Projeto.pdf]( https://github.com/mkunyosi/FLAI_FAMESP/blob/learning/DataAnalytics/Apresenta%C3%A7%C3%A3o_do_Projeto.pdf) contém ilustrações utilizadas no vídeo de apresentação.

### Repositório do projeto 
[Repositório](https://bit.ly/kunyosi_mba_dashboard_dados_projeto) com os componentes utilizados no projeto:
- Notebook criado com a linguagem Python:
   - Consolidação de dados históricos para serem usados pelo Power BI.
   - Testes para integração entre Power BI e Python: geração de gráficos 
- Arquivos auxiliares utilizados no desenvolvimento do projeto

## Detalhes do projeto
### Descrição do problema
O conselho administrativo de um condomínio é uma entidade eleita por outros condôminos e deve, entre outras atividades, analisar as contas do condomínio (adimplência, despesas gerais, fundo de obras etc.) a auxiliar o síndico em tomada de decisões sobre eventuais benfeitorias no condomínio. 

As contas são apresentadas em livros contábeis contendo todos os lançamentos ocorridos no mês. Os livros são físicos e devem ser guardados para consulta futura. 

Analisar os livros contábeis, aparentemente é simples, pois a tarefa mensal é verificar os lançamentos de despesas, se os valores estão coerentes, quais foram as receitas e, por fim,  decidir se tudo está correto. O problema é que há muitos números para validar, há despesas parceladas, obras com arrecadação de longo prazo etc. Contudo, mais importante do que validar os dados de um mês, é acompanhar o histórico das contas durante alguns períodos, pois somente assim é possível identificar variações de despesas/receitas para, por exemplo, decidir quanto há disponível nas reservas do condomínio para novos investimentos em obras ou qual o índice de correção que deveria ser aplicado em cotas futuras.

Considerando que é comum a falta de conhecimento contábil e financeiro por parte de outros conselheiros e também dos demais condôminos, faz-se necessário ter uma ferramenta que facilite a análise das contas.


### Proposta para o trabalho de Data Analytics 
_Ao lado de cada proposta o símbolo [&#10003;] indica que o item foi implementado._

Desenvolver um _dashboard_ que possa responder às seguintes questões:
- [x] A arrecadação mensal está suficiente para cobrir as despesas?
- [x] Como está a evolução do saldo das contas contábeis e dos saldos em banco?
- [ ] Quais são as projeções de receitas e despesas para os próximos meses?
  - [ ] (parcial) Em quanto seria necessário aumentar a cota condominial para equilibrar receita e despesa?
- [x] Dentre as despesas quais são as maiores?
- [x] Ser possível identificar detalhes de lançamentos (descrição, valor e, talvez, comentários adicionais feitos sobre o lançamento)
- [x] (Outras questões pertinentes)

Etapas para construção do dashboard:
- [x] Criar mecanismos para ler os dados mensais e guardá-los em banco de dados relacional ou em arquivos no formato CVS ou Excel. 
  - A definição do formato dos dados consolidados será feita oportunamente.
  - Serão analisadas ferramentas de uso gratuito.
  - Para processar os dados mensais e fazer a consolidação, preferencialmente, será usada a linguagem Python, porém talvez seja usada outra linguagem de programação disponível na ferramenta escolhida.
- [ ] Implementar interface que permita a inclusão de novos dados como comentários a respeito de determinado lançamento e dados sobre parcelamento de despesas.
- [x] Criar o dashboard que consumirá os dados consolidados.
- [x] O dashboard será criado no Power BI conforme as condições listadas para apresentação do trabalho final.
- [ ] Etapas opcionais (futuras):
  - Criar controle de acesso para permitir que somente usuários conhecidos e liberados possam ter   - acesso ao dashboard.
  - Criar sessões de visualização para cada perfil de usuário.
  - Criar interfaces diferenciadas com perfil de administrador e usuário comum. 
  - Criar interface para simular a inclusão de novas despesas às quais serão parceladas. Por exemplo, uma nova obra.



 
