# 🛍️ Projeto Final – Análise de E-commerce Brasileiro (Olist)

Este projeto foi desenvolvido como conclusão da UFCD 10804 – Projeto de Business Intelligence, com o objetivo de aplicar práticas avançadas de modelagem de dados, análise exploratória e visualização estratégica de informações em ambiente Power BI. O estudo de caso foi baseado na base de dados da Olist, uma plataforma brasileira que conecta pequenos lojistas a grandes marketplaces, cujos dados estão disponíveis publicamente no Kaggle.

## 🎯 Objetivo
Construir um painel de Business Intelligence interativo que permitisse aos gestores da Olist acompanhar o desempenho de vendas, identificar gargalos logísticos e compreender o comportamento dos clientes ao longo da jornada de compra.

---

## 🧩 Estruturação do Projeto

### 📁 Importação e Modelagem de Dados
- Carregamento de arquivos CSV referentes a pedidos, itens, pagamentos, clientes, vendedores, produtos, avaliações e dados geográficos.
- Estruturação no modelo estrela com uma tabela fato principal e diversas tabelas dimensão.
- Estabelecimento de relacionamentos no Power BI para garantir a integridade das análises.

---

## 🧮 Medidas Criadas (DAX)

- **Receita Total**
- **Número de Pedidos**
- **Ticket Médio por Pedido**
- **Tempo Médio de Entrega**
- **Avaliação Média dos Clientes**
- **Quantidade Total de Produtos Vendidos**
- **Receita por Categoria**
- **Receita por Região**

Essas métricas foram fundamentais para revelar insights e orientar decisões estratégicas.

---

## 📈 Análises Realizadas

- Identificação das regiões com maior volume e valor de vendas;
- Avaliação do desempenho das categorias de produtos;
- Impacto do tempo de entrega na satisfação do cliente;
- Análise dos métodos de pagamento mais utilizados;
- Evolução mensal das vendas e sazonalidade.

---

## 🎨 Design e Experiência do Usuário

O design visual do dashboard foi aprimorado com a criação de um **fundo de tela personalizado no Figma**, alinhando a identidade visual da Olist com a apresentação dos dados, proporcionando uma experiência visual mais envolvente e profissional.

---

## 🛠️ Tecnologias Utilizadas

- Power BI Desktop  
- DAX  
- Excel  
- Figma  
- Kaggle  

🔗 [Base de dados – Kaggle: Olist Brazilian E-commerce](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)


##  Dashboard
<img src="1.png" alt="Análise Geral" width="800">
</p>

📊 Resumo do Dashboard – Análise de Vendas da Olist

Este dashboard possui filtros por Região e Ano: Permitem segmentar as análises por macrorregiões brasileiras e períodos entre 2016 e 2018.

    KPIs principais:

        Valor total por item vendido: R$ 15.843.553,24

        Média de valor por item: R$ 140,64

        Ticket médio por venda: R$ 160,58

        Quantidade de pedidos: 99.441

        Quantidade de itens vendidos: 112.650

    Análise Temporal: Gráfico de colunas mostra a evolução do total de vendas por ano, evidenciando crescimento consistente de 2016 a 2018.

    Categorias Mais Vendidas: Visual horizontal destaca as principais categorias por volume de vendas e receita, com destaque para cama_mesa_banho, moveis_decoracao e beleza_saude.

    Métodos de Pagamento: Gráfico combinado apresenta a contagem de vendas e o valor total movimentado por método de pagamento, com destaque para cartão de crédito e boleto.

    Status da Entrega: Segmentado entre entregas atrasadas, antecipadas e no dia — sendo mais da metade das entregas classificadas como atrasadas.

    Status do Pedido: Mostra o fluxo dos pedidos desde o status “created” até “delivered”, revelando que a grande maioria chegou ao destino final.


