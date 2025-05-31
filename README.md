
Este repositório contém a planilha `Base de Dados XBOX.xlsx`, que centraliza informações e análises referentes às assinaturas fictícias do serviço Xbox Game Pass. A planilha é organizada em quatro abas principais:

- `Assets`
- `Bases`
- `Cálculos`
- `Dashboard`

---

## 📁 Estrutura da Planilha

### 1. 🖼️ Aba: `Assets`
**Descrição:**  
Contém elementos visuais utilizados para compor o dashboard, como a paleta de cores. Essa aba serve como repositório de recursos auxiliares de design.

---

### 2. 📋 Aba: `Bases`
**Descrição:**  
É a aba central com os dados fictícios dos assinantes e suas respectivas informações sobre os planos contratados.

**Colunas:**
- `Subscriber ID` – Identificador único do assinante
- `Name` – Nome do assinante
- `Plan` – Tipo de plano (Ex: Ultimate, Core, Standard)
- `Start Date` – Data de início da assinatura
- `Auto Renewal` – Indica se a renovação automática está ativa (`Yes` ou `No`)
- `Subscription Price` – Valor da assinatura principal
- `Subscription Type` – Periodicidade da assinatura (Ex: Monthly, Annual, Quarterly)
- `EA Play Season Pass` – Indica se possui EA Play (`Yes` ou `No`)
- `EA Play Season Pass Price` – Preço do EA Play (pode conter `'-'` se não contratado)
- `Minecraft Season Pass` – Indica se possui Minecraft Pass (`Yes` ou `No`)
- `Minecraft Season Pass Price` – Preço do Minecraft Pass
- `Coupon Value` – Valor de desconto recebido
- `Total Value` – Valor total calculado considerando descontos e passes

---

### 3. 📊 Aba: `Cálculos`
**Descrição:**  
Contém cálculos e análises relacionadas a perguntas de negócio baseadas nos dados da aba `Bases`.

**Perguntas analisadas:**
- Qual o faturamento total de vendas de planos anuais (com todas as assinaturas agregadas)?
- Qual o faturamento total dos planos anuais, separado por assinaturas com e sem auto renovação?
- Total de vendas de assinaturas do EA Play.
- Total de vendas de assinaturas minecraft season pass.

---

### 4. 📈 Aba: `Dashboard`
**Descrição:**  
Painel de visualização de dados criado com base nos cálculos e dados da aba `Bases`. Apresenta indicadores visuais, gráficos e insights para acompanhamento de vendas e assinaturas.

---

## 🧠 Objetivo do projeto

O objetivo da planilha é consolidar, analisar e apresentar os dados de assinaturas do Xbox Game Pass, permitindo a tomada de decisões baseada em dados, como:

- Análise de receita por plano
- Impacto de auto renovação
- Eficácia de cupons e passes adicionais
- Visualização de desempenho em dashboards

