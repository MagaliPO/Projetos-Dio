# Dashboard de Vendas do Xbox

## Sobre o projeto

Este projeto apresenta um dashboard interativo criado no Microsoft Excel para explorar dados de assinaturas do Xbox. O painel permite visualizar os registros por tipo de assinatura e acompanhar informações relacionadas aos planos, à renovação automática e à compra de passes adicionais.

O arquivo foi desenvolvido como atividade de estudo para um curso de Excel. Os nomes e registros da base são fictícios e foram usados somente para fins didáticos; não representam dados oficiais de clientes ou vendas do Xbox.

## Arquivo

- [Dashboard de Vendas do Xbox.xlsx](Dashboard%20de%20Vendas%20do%20Xbox.xlsx) — planilha com a base de dados, cálculos, tabelas dinâmicas, segmentação e dashboard.

## Dados utilizados

A planilha contém **295 registros** de assinantes fictícios, com datas de início entre janeiro e dezembro de 2024. A base inclui os seguintes campos:

| Campo | O que representa |
|---|---|
| `Subscriber ID` | Identificador fictício do assinante |
| `Name` | Nome fictício |
| `Plan` | Categoria do plano: Core, Standard ou Ultimate |
| `Start Date` | Data de início da assinatura |
| `Auto Renewal` | Indica se a renovação automática está ativada |
| `Subscription Price` | Valor associado à assinatura |
| `Subscription Type` | Periodicidade: Monthly, Annual ou Quarterly |
| `EA Play Season Pass` | Indica a inclusão do passe EA Play |
| `EA Play Season Pass Price` | Valor do passe EA Play |
| `Minecraft Season Pass` | Indica a inclusão do passe Minecraft |
| `Minecraft Season Pass Price` | Valor do passe Minecraft |
| `Coupon Value` | Valor do cupom aplicado |
| `Total Value` | Valor total registrado para a assinatura |

Os valores são os que constam na planilha e não têm moeda especificada neste projeto. A pasta de trabalho organiza os dados nas abas `Bases`, `Cálculos` e `Dashboard`, além de uma aba de recursos visuais.

## Como reproduzir e explorar o dashboard

1. Baixe ou abra o arquivo **Dashboard de Vendas do Xbox.xlsx** desta pasta.
2. Abra-o no Microsoft Excel para desktop e habilite a edição, se solicitado.
3. Na parte inferior da janela, selecione a aba **Dashboard**.
4. Use o menu/segmentação à esquerda, identificado como **Subscription Type**.
5. Escolha **Monthly**, **Annual** ou **Quarterly** para filtrar o dashboard e observar os resultados correspondentes.

Para voltar a ver todos os tipos, limpe a seleção na segmentação (o ícone de limpar filtro, quando disponível).

## Atualização dos dados

O dashboard usa tabelas dinâmicas e uma segmentação de dados conectada ao campo `Subscription Type`. Alterar a seleção da segmentação filtra as visualizações. Se você editar valores na base, use **Dados → Atualizar Tudo** no Excel para atualizar as tabelas dinâmicas e o dashboard. Ao acrescentar novos registros, inclua-os na tabela de origem antes de atualizar. Evite editar diretamente as tabelas dinâmicas e os gráficos do dashboard.

## Observação

Este material é educacional e serve para praticar organização de dados, tabelas dinâmicas, segmentação de dados e criação de dashboards no Excel. Os resultados não devem ser interpretados como números oficiais de vendas do Xbox.