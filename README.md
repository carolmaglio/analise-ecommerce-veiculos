# 🚗 Análise de Dados: E-commerce de Veículos
Projeto prático desenvolvido durante o curso de SQL para Análise de Dados: do básico ao avançado da @Midori Toyota.

## 1. Sobre o projeto
Este projeto simula um cenário de e-commerce automotivo com foco em análise de vendas e perfil de clientes. O objetivo é aplicar conceitos de SQL na resolução de problemas de negócio, por meio da construção de indicadores e geração de insights estratégicos.

## 🎯 2. Objetivo
O objetivo central é acompanhar o desempenho de vendas e analisar o perfil dos clientes.

## 🛠️ 3.	Ferramentas e Tecnologias
* SQL – queries utilizando filtros, agregações, joins, subqueries, CTEs e manipulação de datas
* PostgreSQL – modelagem relacional e execução das queries
* Excel – tratamento de dados e construção do dashboard

## 4.	Schema
A análise foi construída a partir de um banco de dados relacional composto pelos schemas `sales` e `temp_tables`. O diagrama do relacionamento entre as tabelas pode ser visualizado abaixo:

<img width="1304" height="635" alt="Diagrama img" src="https://github.com/user-attachments/assets/a24b7e7b-5abb-4b01-9661-dbb7554a41e5" />


## 5.	Período de análise
* Para os indicadores de Receita, Ticket Médio, Leads e Conversão, foram utilizados dados históricos no período de setembro de 2020 a agosto de 2021.
* Para os demais indicadores, foi considerado o mês de referência de agosto de 2021.

## 📊 6.	Indicadores monitorados
### Vendas
* Receita e ticket médio
* Leads e conversão
* Estados que mais venderam
* Marcas mais vendidas
* Lojas que mais venderam
* Visitas ao site por dia da semana

### Perfil dos Leads
* Gênero
* Status profissional
* Faixa etária
* Faixa salarial
* Classificação do veículo
* Idade do veículo
* Modelo mais visitado

## ❓ 7.	Perguntas norteadoras de negócio

1.	Quais estados concentram maior volume de vendas?
2.	Quais dias da semana apresentam maior volume de visitas e maior potencial para campanhas?
3.	Quais marcas concentram maior participação nas vendas?
4.	Qual é a evolução do volume de leads e a taxa de conversão ao longo dos meses?
5.	O crescimento da receita entre maio e agosto de 2021 foi impulsionado pelo aumento do ticket médio ou pelo volume de vendas?
6.	Qual é a distribuição de gênero dos leads?
7.	Qual é o perfil profissional predominante?
8.	Qual é a faixa etária mais representativa?
9.	Qual é o perfil de renda dos leads?
10.	O interesse está concentrado em veículos novos ou seminovos?
11.	Qual é a idade média dos veículos mais buscados?
12.	Quais modelos concentram maior volume de visitas?

## 💡 8.	Insights
* A **região Sudeste concentra o maior volume de vendas**, com destaque para **São Paulo** (**734 vendas** no período analisado).
* O tráfego é mais concentrado na **segunda e terça-feira**, enquanto domingo apresenta o menor volume de visitas.
* **Fiat e Chevrolet** concentra a maior participação nas vendas, indicando preferência por marcas tradicionais.
* Entre **abril a agosto de 2021**, houve um **crescimento no volume de leads**, acompanhado por **aumento na taxa de conversão**.
* Entre maio e agosto de 2021, a receita apresentou um crescimento contínuo, enquanto o ticket médio permaneceu estável, indicando que o aumento da receita foi impulsionado principalmente pelo maior volume de vendas.
* O público é predominantemente **feminino (60%)**.
* Cerca de **65% dos leads** possuem vínculo empregatício **CLT**.
* A maior concentração etária está entre **20 e 40 anos**.
* A maioria pertence à classe média, com **renda entre R$ 5.000 e R$ 10.000**.
* Aproximadamente **70%** demonstram **interesse por veículos seminovos**.
* Há maior interesse por veículos com **mais de 6 anos de uso**.
* Os modelos mais visitados são **Palio, Gol e Fiesta**, todos veículos populares.

## 🔵 9.	Recomendações práticas baseadas nos insights
* Priorizar **campanhas regionais no estado de São Paulo**, considerando sua alta representatividade nas vendas.
* Concentrar **investimentos em mídia paga no início da semana (segunda e terça-feira)**, quando o tráfego é mais elevado.
* **Reduzir investimento publicitário aos domingos**, visando otimizar o ROAS (Retorno sobre o Investimento em Publicidade).
* **Ampliar o portfólio e ações promocionais para as marcas Fiat e Chevrolet**, reforçando as categorias de maior demanda.
* Desenvolver **campanhas direcionadas ao público feminino**, que representa a maior parcela dos leads.
* Criar **ofertas de financiamento e condições facilitadas**, considerando o perfil majoritário CLT.
* Reforçar a **estratégia digital com foco em público jovem-adulto**, priorizando canais online e mobile.
* Destacar veículos seminovos e com melhor custo-benefício nas campanhas, alinhando-se ao perfil de consumo identificado.


## 10.	Dashboard
<img width="1916" height="1017" alt="1" src="https://github.com/user-attachments/assets/81ec6cb5-badf-484b-a92e-9667c99fe6ab" />
<img width="1918" height="1017" alt="2" src="https://github.com/user-attachments/assets/d676775f-7a12-453e-b000-9656a1e69b66" />

⬇️ [Clique aqui para baixar o Dashboard](https://markdownlivepreview.com/)





