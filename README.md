# 📊 Análise de Vendas – Alura Store Brasil

Este repositório contém uma análise exploratória das vendas de quatro lojas da **Alura Store Brasil**, realizada a partir de diferentes bases de dados contendo informações de preços, categorias, avaliações, produtos e fretes.  
O objetivo é identificar padrões de desempenho, produtos mais e menos vendidos, comportamento dos clientes e fatores que influenciam o faturamento.

---

## 🎯 Objetivo da Análise

A análise busca responder às seguintes perguntas principais:

- **Qual é o faturamento total de cada loja?**
- **Quais categorias mais vendem em cada unidade?**
- **Como se comparam as avaliações médias entre as lojas?**
- **Quais produtos têm melhor e pior desempenho em vendas?**
- **Existe diferença no frete médio cobrado por cada loja?**

Essa visão integrada suporta decisões de planejamento, estoque, precificação e estratégias de marketing.

---

## 📁 Estrutura do Projeto

- **AluraStoreBrasil.ipynb** — Notebook principal com toda a análise  
- **Relatoria da Venda da Loja.pdf** — Relatório fornecido como anexo  
- **README.md** — Documento explicativo  
- **/dados** — Bases carregadas via URLs  

---

## 📈 Principais Análises, Gráficos e Insights

### **1. Faturamento por Loja**
Cálculo da soma total dos preços em cada base de dados para identificar qual loja apresenta maior faturamento.  
**Insight:** há diferenças significativas de desempenho entre as lojas.

---

### **2. Vendas por Categoria**
Agrupamento por **Categoria do Produto**, destacando quais segmentos mais geram vendas.  
Categorias analisadas incluem: eletrodomésticos, móveis, instrumentos musicais, utilidades domésticas, livros, esporte e lazer.  
**Insight:** algumas lojas apresentam especialização em categorias específicas.

---

### **3. Avaliação Média das Lojas**
Cálculo da média de `Avaliação da compra` por loja.  
**Insight:** variações na satisfação do cliente podem indicar oportunidades de melhoria no atendimento e logística.

---

### **4. Produtos Mais e Menos Vendidos**
Ranking dos **5 produtos mais vendidos** e **5 menos vendidos** de cada loja.  
**Insight:** produtos de alto giro se repetem entre lojas; itens com baixo desempenho podem exigir revisão de estoque.

---

### **5. Frete Médio por Loja**
Cálculo da média dos valores de frete por unidade.  
**Insight:** diferenças logísticas podem afetar margem e experiência do cliente.

---

### **6. Exemplos de Gráficos Gerados**
O notebook inclui visualizações como:

- Gráfico de barras de faturamento por loja  
- Comparação das avaliações médias  
- Gráficos de frete médio  
- Faturamento total consolidado  

Essas visualizações tornam os insights mais claros e comparáveis.

---

## ▶️ Instruções para Executar o Notebook

### **1. Clonar o repositório**
```bash
git clone https://github.com/seuusuario/seurepositorio.git
cd seurepositorio
