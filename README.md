# 📊 Análise de Evasão de Clientes (Churn) - Telecom X 

Este projeto realiza uma análise exploratória de dados de clientes de uma empresa (fictícia) de telecomunicações, com foco na identificação de fatores que influenciam a evasão de clientes (Churn). O desenvolvimento foi feito integralmente no Google Colab utilizando bibliotecas de ciência de dados em Python.

---

## 📂 Estrutura do Projeto

- **Notebook:** Análise completa de dados (`TelecomX_BR.ipynb`)
- **Gráficos:** Visualizações salvas em arquivos de imagem (`/imagens/`)
- **Dados:** Dataset carregado via JSON hospedado em repositório externo.

---

## 🚀 Tecnologias Utilizadas

- Python 3 (Google Colab)
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Plotly
- Kaleido (exportação de imagens)

---

## 🎯 Objetivos da Análise

- Compreender o comportamento de cancelamento dos clientes.
- Identificar quais variáveis estão associadas ao churn.
- Gerar insights acionáveis para estratégias de retenção de clientes.

---

## 🔎 Etapas Realizadas

1. **Importação dos Dados:** carregados via URL no formato JSON.
2. **Limpeza e Tratamento:** normalização de dados aninhados, conversão de tipos e tratamento de nulos.
3. **Análise Descritiva:** métricas estatísticas como média, mediana e desvio-padrão.
4. **Visualizações:** gráficos de barras, pizza, boxplots e histogramas com Plotly.
5. **Identificação de Perfis de Risco:** segmentação de clientes com maior propensão à evasão.
6. **Exportação de Gráficos:** geração de imagens em alta qualidade para relatórios.

---

## 📊 Principais Insights

- **Contrato mensal** está altamente associado ao churn.
- **Baixo tempo de contrato (tenure)** aumenta a chance de evasão.
- **Método de pagamento automático** (cartão/débito automático) reduz o risco.
- **Clientes com baixo gasto total** tendem a cancelar com mais frequência.

## 🔐 Observação sobre os dados
O dataset foi utilizado apenas para fins educacionais e acadêmicos, simulando um problema real de negócios em telecomunicações.

## 👨‍💻 Autor: Bruno Leite

Email: bmendoncal@hotmail.com <br>
LinkedIn: <a href="www.linkedin.com/in/bruno-leite-085115a7/"> bruno-leite-085115a7 </a> <br>
Ano: 2025
