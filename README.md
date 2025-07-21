# 🍕 Projeto: Análise de Vendas - Pizzaria (Python/Excel)
Projeto de análise de vendas de uma pizzaria fictícia baseado em dados fornecidos pela Maven Analytics. O objetivo foi extrair insights relevantes a partir de um processo completo de tratamento, análise e visualização de dados, utilizando Python e Microsoft Excel.

---

# 📌 Visão Geral

- **Ferramentas utilizadas**: Python (pandas, openpyxl), Microsoft Excel
- **Foco**: Faturamento, performance por tipo/tamanho de pizza, horários de pico
- **Produto final**: Dashboard interativo em Excel

 ---

## 🧼 Etapas do Projeto

### 1. Tratamento de Dados (Python)
- Correção de colunas
- Junção de tabelas com `merge`
- Conversão de tipos
- Cálculo de colunas auxiliares (faturamento por pizza, horário etc.)

📄 Script: [`scripts/limpeza_dados_pizzaria.py`](./scripts/vendas-pizza.ipynb)

### 2. Análise e Dashboard (Excel)
- Tabelas dinâmicas
- Gráficos de linha, barras e pizza
- KPIs com caixas e ícones
- Formatação condicional

📊 Dashboard: [`entregas/dashboard_final.xlsx`](./entrega/Projeto_Final_Pizzaria.xlsx)

---

## 📷 Preview do Dashboard

![Dashboard Excel](imagem_dashboard/printdashboard1.PNG)

---

## 🎯 Insights Obtidos

- **R$ 1.635.720,10** em faturamento total
- Maior volume de pedidos entre **12h e 13h** e **17h e 18h**
- Tamanhos mais vendidos: **M e G**
- Pizzas mais vendidas: **Frango com Churrasco, Pepperoni e Havaiana**
- Pizzas com melhor faturamento: **Pizza de Frango Tailandesa**
- **Brie Carré** foi a menos vendida e teve menor faturamento por pedido
- Recomendação de **promoção para Soppressata** e **remoção da Brie Carré**

---

## 🔗 Sobre o Dataset
Dataset original: Pizza Sales – Maven Analytics  
Disponível em: [https://www.mavenanalytics.io/data-playground](https://www.mavenanalytics.io/data-playground)
