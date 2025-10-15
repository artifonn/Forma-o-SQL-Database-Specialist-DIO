🧩 Desafio de Projeto — Esquema Conceitual de Banco de Dados

Este repositório contém o esquema conceitual desenvolvido como parte do desafio de projeto proposto no bootcamp Formação SQL Database Specialist da DIO.
O objetivo é refinar o modelo de banco de dados apresentado, implementando entidades e relacionamentos para representar um cenário mais completo e realista de uma aplicação comercial.

🎯 Objetivo do Projeto

Refinar o modelo de dados, incorporando os seguintes pontos adicionais:

Cliente PJ e PF

Uma conta pode ser Pessoa Jurídica (PJ) ou Pessoa Física (PF), mas não ambas.

Isso garante consistência nos dados e clareza na identificação do tipo de cliente.

Pagamento

Uma conta pode ter múltiplas formas de pagamento cadastradas (ex: cartão, boleto, pix).

O modelo reflete essa multiplicidade através de um relacionamento 1:N.

Entrega

Cada pedido possui informações de status (ex: pendente, em transporte, entregue) e um código de rastreio.

Essa estrutura permite o acompanhamento detalhado das entregas.

🏗️ Descrição do Projeto Conceitual

O esquema conceitual foi elaborado para representar o funcionamento básico de um sistema de e-commerce (ou plataforma de vendas), contemplando:

Clientes (PF ou PJ)

Contas associadas aos clientes

Pedidos realizados

Pagamentos com múltiplas opções

Entregas com controle de status e rastreio

Produtos e suas categorias

O modelo busca demonstrar boas práticas de modelagem, com ênfase em normalização, integridade referencial e clareza nas relações.