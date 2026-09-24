# Python Insights: Análise de Cancelamento de Clientes.

Projeto desenvolvido durante a **Jornada Python**, focado em Análise de Dados para identificar e mitigar os principais motivos de cancelamento de clientes em uma base de dados.

---

## Contexto do Problema

Uma empresa com uma ampla base de clientes identificou que a maioria deles estava inativa. O objetivo principal deste projeto foi analisar os dados históricos para entender a raiz do problema e propor soluções práticas para reduzir os índices de cancelamento.

---

## Tecnologias e Bibliotecas Utilizadas

- **Python**
- **Pandas**: Limpeza, tratamento e manipulação dos dados.
- **Plotly Express**: Criação de gráficos interativos para análise visual de padrões.

---

## Passo a Passo da Análise

1. **Importação e Preparação dos Dados**:
   - Carregamento da base de dados contendo as informações dos clientes.
   - Remoção de colunas irrelevantes que não impactavam a análise.
   - Tratamento de valores nulos e remoção de linhas vazias (*data cleaning*).

2. **Análise Exploratória Inicial**:
   - Mapeamento e contagem do número total de clientes ativos vs. cancelados.

3. **Visualização de Dados**:
   - Geração de histogramas e gráficos interativos com Plotly para identificar discrepâncias por perfil de cliente, tipo de contrato, forma de pagamento e chamados ao suporte.

4. **Simulação de Cenários e Soluções**:
   - Aplicação de filtros baseados nos cenários identificados na análise gráfica.
   - Recálculo da taxa de cancelamento para medir o impacto direto das ações corretivas propostas.

---

## Principais Aprendizados

- Aplicação prática do ciclo completo de um projeto de dados: Limpeza ➔ Análise ➔ Visualização ➔ Tomada de Decisão.