# Customer Shopping Behavior Analysis 🛒

Este projeto realiza uma análise detalhada do comportamento de compra de clientes com base em um dataset de 3.900 registros transacionais. O objetivo é identificar padrões de consumo, segmentar clientes por faixa etária e avaliar o impacto de assinaturas e métodos de envio no faturamento total.

## 🚀 Tecnologias Utilizadas

* **Python 3.x**: Processamento e limpeza de dados.
* **Pandas**: Manipulação de DataFrames e Engenharia de Atributos.
* **SQL (PostgreSQL)**: Consultas estruturadas para análise de receita e segmentação.
* **Power BI**: Criação de dashboard interativo para visualização de insights.

## 📈 Insights Extraídos

Durante a análise, foram identificados pontos chave para o negócio:
* **Segmentação por Idade:** O grupo de "Young Adults" lidera o faturamento, contribuindo com **$62.143**.
* **Fidelização:** Identificamos que a maioria dos compradores recorrentes (2.518 clientes) ainda não são assinantes, representando uma oportunidade de conversão.
* **Logística:** O método **Free Shipping** é a escolha predominante (675 pedidos), enquanto o envio **Express** apresenta o maior ticket médio unitário ($60.48).

## 🛠️ Processamento de Dados

A fase de preparação utilizou técnicas de Pandas para garantir a qualidade dos dados:
1. **Tratamento de Nulos:** Imputação de 37 valores ausentes na coluna `Review Rating` utilizando a mediana por categoria.
2. **Engenharia de Dados:** Criação da coluna `age_group` e conversão de frequências de compra em períodos numéricos.
3. **Integração SQL:** Exportação dos dados limpos para PostgreSQL via SQLAlchemy para análises relacionais.

## 📊 Dashboard

![Screenshot do Dashboard](img/Dashboard%20img.png)
*O dashboard interativo permite filtrar dados por gênero, status de assinatura e categoria de produto.*

## ✒️ Autor

* **João Thomaz Vieira** - [LinkedIn](https://www.linkedin.com/in/joãothomazvieira/)
