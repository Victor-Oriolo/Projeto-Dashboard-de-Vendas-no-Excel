Visão geral
Este projeto apresenta um dashboard desenvolvido no Excel para analisar
a renovação automática de assinaturas do Xbox. O painel foi construído
para responder à pergunta de negócio:
Qual é a distribuição de renovação automática entre os diferentes
planos de assinatura (Core, Standard e Ultimate)?

O objetivo é comparar o comportamento de renovação entre os planos e
apoiar decisões relacionadas à retenção de assinantes e à estratégia de
assinaturas.
Indicador principal

- Taxa média de renovação automática: proporção de assinantes com
  renovação automática habilitada em relação ao total de assinantes da
  base.
  
A taxa geral oferece uma visão consolidada. Para responder plenamente à
pergunta de negócio, a análise deve comparar também a quantidade e/ou o
percentual de assinantes com renovação automática habilitada em cada
plano: Core, Standard e Ultimate.
Dados utilizados

A aba Bases contém os registros de assinantes e campos como: -
Identificador e nome do assinante; - Plano contratado (Core,
Standard ou Ultimate); - Data de início da assinatura; - Status de
renovação automática (Yes/No); - Tipo e preço da assinatura; -
Serviços adicionais e respectivos valores; - Valor de cupom e valor
total.

A aba Cálculos reúne as fórmulas usadas para consolidar a contagem de
assinantes e calcular a taxa geral de renovação automática. A aba
Assets concentra recursos visuais e a paleta de cores do projeto. A
aba Dashboard apresenta o indicador e a visualização principal.

Como interpretar
- Taxa por plano: percentual de assinantes de cada plano que têm a
  renovação automática habilitada.
- Comparação entre planos: ajuda a identificar em qual plano a
  renovação automática é mais ou menos frequente.
- Taxa geral: serve como referência agregada, mas não substitui a
  comparação segmentada por plano.
Para calcular a taxa de cada plano, utilize:
Taxa de renovação automática do plano = assinantes do plano com Auto Renewal = "Yes" ÷ total de assinantes daquele plano
Multiplique o resultado por 100 para apresentar o indicador em
percentual.
Principais perguntas que o dashboard deve apoiar
1. Qual plano apresenta a maior taxa de renovação automática?
2. Qual plano apresenta a menor taxa?
3. Qual é a diferença, em pontos percentuais, entre os planos?
4. Quantos assinantes têm renovação automática habilitada e
   desabilitada em cada plano?
5. Como cada plano se compara à taxa geral?
Como atualizar os dados
1. Atualize os registros na aba Bases, mantendo os nomes das colunas
   e os valores categóricos consistentes.
2. Verifique se as fórmulas da aba Cálculos abrangem todos os
   registros atualizados.
3. Atualize as tabelas dinâmicas e/ou gráficos, se aplicável, usando os
   comandos de atualização do Excel.
4. Confira se os indicadores e gráficos da aba Dashboard foram
   recalculados corretamente.
Observações e limitações
- Os registros usam Yes e No no campo Auto Renewal; mantenha
  esse padrão ou ajuste as fórmulas caso os valores sejam traduzidos.
- A taxa geral isolada não mostra a distribuição por plano. A
  comparação por Core, Standard e Ultimate é essencial para
  responder diretamente à pergunta de negócio.
- Os dados e indicadores refletem a base disponível no arquivo e a
  data de apuração indicada no dashboard.
- Antes de tomar decisões, confirme se a base está atualizada e se os
  cálculos consideram todos os registros.
Ferramentas
- Microsoft Excel
- Fórmulas e visualizações do Excel
Projeto: Dashboard Xbox --- análise de renovação automática
Data de apuração indicada no painel: 15/10/2026
