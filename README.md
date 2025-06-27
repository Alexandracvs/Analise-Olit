## 🔹 Projetos em Destaque:

Este projeto foi desenvolvido como conclusão da UFCD 10804 – Projeto de Business Intelligence, com o objetivo de aplicar práticas avançadas de modelagem de dados, análise exploratória e visualização estratégica de informações em ambiente Power BI. O estudo de caso foi baseado na base de dados da Olist, uma plataforma brasileira que conecta pequenos lojistas a grandes marketplaces, cujos dados estão disponíveis publicamente no Kaggle.


🎯 Objetivo

Construir um painel de Business Intelligence interativo que permitisse aos gestores da Olist acompanhar o desempenho de vendas, identificar gargalos logísticos e compreender o comportamento dos clientes ao longo da jornada de compra.

🧩 Estruturação do Projeto

📁 Importação e Modelagem de Dados

    Foram carregados e tratados arquivos CSV correspondentes a pedidos, itens, pagamentos, clientes, vendedores, produtos, avaliações e dados geográficos.

    A modelagem foi feita com base no modelo estrela, criando uma tabela fato de pedidos e diversas tabelas dimensão (cliente, produto, tempo, vendedor, etc.).

    Relacionamentos adequados foram definidos entre as tabelas para garantir integridade e consistência nas análises.

🧮 Medidas Criadas (DAX)

Para dar suporte às análises estratégicas, foram criadas diversas medidas no Power BI usando linguagem DAX:

    Receita Total: Soma dos valores pagos por pedidos.

    Número de Pedidos: Contagem de pedidos únicos.

    Ticket Médio por Pedido: Receita Total / Número de Pedidos.

    Tempo Médio de Entrega: Diferença média entre data de entrega estimada e real.

    Avaliação Média dos Clientes: Média das notas dadas nas avaliações.

    Quantidade Total de Produtos Vendidos: Soma das quantidades de itens nos pedidos.

    Receita por Categoria: Receita segmentada por categorias de produto.

    Receita por Região: Receita agregada por estados ou cidades.

Essas métricas permitiram visualizar desempenhos comparativos, identificar áreas de maior faturamento, bem como possíveis gargalos logísticos em entregas.
📈 Análises Realizadas

Através do dashboard interativo, foi possível obter insights como:

    Quais estados e cidades concentram o maior volume de vendas.

    Categorias com maior retorno financeiro.

    Correlação entre tempo de entrega e avaliações dos clientes.

    Impacto de diferentes formas de pagamento na receita total.

    Desempenho de vendedores por região e categoria.

    Evolução mensal de vendas e sazonalidade.

Essas análises contribuem para uma tomada de decisão mais informada, orientando estratégias de marketing, logística e relacionamento com o cliente.
🎨 Design e Experiência do Usuário

Para garantir uma visualização limpa, moderna e eficaz, foi utilizado o Figma na criação de um fundo de tela personalizado, integrando o branding da Olist ao layout do Power BI. O objetivo foi proporcionar uma experiência visual coesa e alinhada aos padrões de apresentação profissional, facilitando a leitura dos dados e melhorando o impacto visual do dashboard final.
🛠️ Tecnologias Utilizadas

    Power BI Desktop

    DAX

    Excel (para pré-tratamento)

    Figma (design visual)

    Kaggle (fonte de dados)

📌 Base de dados – Kaggle: Olist Brazilian E-commerce
