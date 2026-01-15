# Desenvolvimento do Dashboard – Xbox Game Pass Subscriptions Sales

Este dashboard foi desenvolvido com o objetivo de analisar o desempenho de vendas das assinaturas do Xbox Game Pass, 
integrando indicadores financeiros, comportamento de renovação, uso de cupons e evolução mensal de novas assinaturas. 

A construção do painel envolveu a aplicação prática de conceitos de modelagem de dados, agregações, segmentação, análise temporal e visualização interativa.

🔗[Acesse o Dashboard](Dashboard-de-Vendas-do-Xbox-com-Excel/Dashboard_Vendas_Xbox.xlsx)

## 1. Definição do Contexto e Escopo da Análise

No topo do dashboard, foram definidos e exibidos o Calculation Period (01/01/2024 a 31/01/2024) e a Update Date (14/01/2026 às 12:00).
Essa etapa reforça boas práticas de análise de dados, garantindo clareza temporal, confiabilidade e rastreabilidade das informações apresentadas.

O título Xbox Game Pass Subscriptions Sales sintetiza o escopo do relatório, deixando explícito que o foco está nas vendas de assinaturas.

## 2. Implementação de Filtros para Exploração dos Dados

Na lateral esquerda, foram configurados filtros interativos, permitindo ao usuário segmentar toda a análise:

_Subscription Type:_ Annual, Monthly e Quarterly

_Plan:_ Core, Standard e Ultimate

Esses filtros aplicam o conceito de análise dinâmica, possibilitando observar como diferentes tipos de assinatura e planos impactam os valores, 
os gráficos e os indicadores do dashboard.

## 3. Criação dos Indicadores-Chave de Receita (KPIs)

Foram desenvolvidos três KPIs principais, com foco em consolidar o valor total arrecadado por tipo de produto:

➡️ Xbox Game Pass

➡️ Minecraft Season Pass

➡️ EA Play Season Pass

Esses indicadores utilizam medidas de soma e permitem uma leitura rápida do desempenho financeiro individual de cada produto, reforçando a importância de KPIs para análises executivas.

## 4. Análise do Valor das Assinaturas por Tipo de Renovação

O gráfico Total Subscriptions Value by Renewal Type foi construído para comparar o valor total das assinaturas de acordo com a existência ou não de renovação automática:

✅ Yes (com renovação automática)

❌ No (sem renovação automática)

Esse gráfico aplica o conceito de agrupamento por categoria e permite avaliar o impacto da renovação automática no faturamento, apoiando análises de retenção e estratégia comercial.

## 5. Avaliação de Receita e Cupons por Plano

O gráfico Total Subscriptions and Coupon Value apresenta uma análise conjunta de:

➡️ Total Value (valor total das assinaturas)

➡️ Total Coupon Value (valor total concedido em cupons)

Segmentado por plano: Core, Standard e Ultimate

Esse visual utiliza colunas empilhadas, permitindo analisar simultaneamente receita e descontos, além de avaliar a efetividade das estratégias promocionais por plano.

## 6. Análise Temporal de Novas Assinaturas

O gráfico Monthly New Subscriptions foi desenvolvido para acompanhar a quantidade de novas assinaturas ao longo dos meses.

Permitindo identificar tendências, padrões de crescimento e possíveis efeitos sazonais.

## 7. Padronização Visual e Experiência do Usuário

Todo o dashboard foi construído seguindo a identidade visual do Xbox, com predominância do verde institucional. Além disso, foram aplicados princípios de:

 - Hierarquia da informação

- Organização do layout

- Clareza visual e consistência entre gráficos e KPIs

Essas decisões reforçam a usabilidade e facilitam a interpretação dos dados.
