
# 📊 Dashboard de Controle de Orçamento Empresarial

Este projeto é um painel interativo desenvolvido no Microsoft Excel para monitorar o orçamento corporativo, permitindo a análise ágil e detalhada das despesas planejadas (orçadas) versus os gastos reais (realizados).

<img width="1366" height="729" alt="Dash" src="https://github.com/user-attachments/assets/0d203d7b-8c46-49bf-b3ec-4bb3f9b82f3c" />

## 🎯 Objetivo do Projeto
Fornecer uma visão clara e imediata da saúde financeira da empresa, identificando rapidamente quais departamentos e categorias de despesas estão dentro da meta e quais estouraram o orçamento.

## 🛠️ Ferramentas e Técnicas Aplicadas
* **Arquitetura de Dados:** Separação do projeto em 3 camadas lógicas (Base de Dados, Tratamento, Visualização) para garantir escalabilidade.
* **Fórmulas Lógicas:** Automação de status de gastos utilizando a função `=SE()`.
* **Análise de Dados:** Uso avançado de **Tabelas Dinâmicas** para consolidação e cruzamento dos lançamentos financeiros.
* **Visualização de Dados e UI/UX:** 
  * Gráficos Dinâmicos (Colunas Agrupadas e Barras Horizontais para categorização longa).
  * Cartões de Resumo (KPIs) dinâmicos integrados com a função `=INFODADOSTABELADINÂMICA`.
  * Layout corporativo clean (remoção de linhas de grade e paleta de cores harmonizada).
* **Interatividade:** Implementação de **Segmentação de Dados (Slicers)** conectados a múltiplos gráficos e relatórios simultaneamente.

## 📂 Estrutura do Arquivo
O projeto foi construído com as melhores práticas de organização de planilhas, dividido nas seguintes abas:
1. **Bases_Dados:** Tabela oficial com os registros brutos das transações.
2. **Tabelas_Dinamicas:** O "motor" analítico do projeto, onde os cálculos e agrupamentos acontecem.
3. **Dashboard:** O painel visual interativo pronto para uso executivo.

## 🚀 Como testar
1. Faça o download do arquivo `.xlsx` disponível neste repositório.
2. Abra no Microsoft Excel.
3. Navegue até a aba **Dashboard** e utilize os botões de filtro (Departamento e Status_Mes) para interagir com os dados em tempo real.
