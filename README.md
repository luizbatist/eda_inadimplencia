📊 Análise Exploratória de Crédito — Risco de Inadimplência
📌 Visão Geral

Este projeto realiza uma Análise Exploratória de Dados (EDA) sobre um conjunto de dados de clientes de cartão de crédito, com foco na identificação de padrões associados ao risco de inadimplência.

A análise busca compreender como características demográficas e variáveis financeiras se relacionam com a probabilidade de default, utilizando Python e bibliotecas voltadas à análise de dados.

🎯 Objetivos

Identificar padrões de comportamento associados à inadimplência

Avaliar a relação entre inadimplência e:

Limite de crédito (LIMIT_BAL)

Faixa etária

Estado civil

Produzir insights claros e comunicáveis, voltados à análise de risco de crédito

📂 Dataset

Fonte: UCI Machine Learning Repository

Descrição: Dados de clientes de cartão de crédito contendo:

Informações demográficas (idade, sexo, estado civil, escolaridade)

Limite de crédito

Histórico de pagamentos

Indicador de inadimplência no mês seguinte

⚠️ O dataset é utilizado exclusivamente para fins educacionais e de análise exploratória.

🧹 Etapas do Projeto
1️⃣ Exploração e Limpeza dos Dados

Verificação de tipos de dados

Validação de domínios (valores categóricos válidos)

Tratamento de categorias inconsistentes

Investigação de outliers e valores negativos

Decisões conscientes de manter ou não tratar dados plausíveis

2️⃣ Análise Exploratória (EDA)

Foram analisadas as seguintes relações com inadimplência:

Faixa de crédito (LIMIT_BAL)

Faixa etária

Estado civil

A inadimplência foi medida como a média da variável binária default.payment.next.month, representando a taxa de default por grupo.

3️⃣ Visualização dos Resultados

Gráficos de barras utilizando Matplotlib

Ênfase em clareza e interpretação

Visualizações preparadas para apresentação em PowerPoint

📈 Principais Insights

Clientes com menor limite de crédito apresentam maior taxa de inadimplência

A inadimplência diminui progressivamente à medida que o limite de crédito aumenta

A menor taxa de inadimplência ocorre entre clientes de 31 a 40 anos

A partir dos 40 anos, observa-se aumento gradual do risco

Clientes solteiros apresentam menor taxa de inadimplência em comparação a casados e outros estados civis

🔍 Observação: variáveis financeiras apresentaram maior poder explicativo do risco de inadimplência do que variáveis demográficas.
