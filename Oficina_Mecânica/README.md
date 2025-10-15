:

🛠️ Esquema Conceitual - Sistema de Gerenciamento de Ordens de Serviço de Oficina Mecânica
📌 Descrição do Projeto

Este repositório contém a modelagem conceitual de um sistema de controle e gerenciamento de ordens de serviço (OS) em uma oficina mecânica. O projeto faz parte de um desafio proposto no bootcamp Formação SQL Database Specialist da DIO, com o objetivo de desenvolver um esquema conceitual a partir de uma narrativa textual, utilizando boas práticas de modelagem de dados.

O modelo conceitual foi construído com base nas necessidades descritas, representando entidades, relacionamentos e atributos essenciais para o funcionamento do sistema.

🎯 Objetivo

Desenvolver um modelo conceitual (DER) para um sistema de gerenciamento de ordens de serviço em uma oficina mecânica, considerando os processos de:

Cadastro de clientes e veículos;

Atribuição de veículos a equipes de mecânicos;

Emissão, execução e controle de ordens de serviço (OS);

Cálculo de valores com base em mão-de-obra e peças;

Acompanhamento de status e datas de conclusão.

📖 Narrativa Base

Clientes levam veículos à oficina mecânica para conserto ou revisões periódicas.
Cada veículo é designado a uma equipe de mecânicos, que identifica os serviços a serem executados e preenche uma Ordem de Serviço (OS) com data de entrega.
A partir da OS, calcula-se o valor de cada serviço, consultando uma tabela de referência de mão-de-obra.
O valor de cada peça também é adicionado à OS.
O cliente autoriza a execução dos serviços.
A mesma equipe avalia e executa os serviços.

Cada mecânico possui: código, nome, endereço e especialidade.
Cada OS possui: número, data de emissão, valor total, status, e data de conclusão.

🧩 Entidades Identificadas

Com base na narrativa, foram identificadas as seguintes entidades principais:

Cliente

Veículo

Mecânico

Equipe

Ordem de Serviço (OS)

Serviço

Peça

Tabela de Mão-de-Obra

🔄 Relacionamentos

Um cliente possui um ou mais veículos.
Um veículo é atendido por uma equipe de mecânicos.
Uma equipe é composta por um ou mais mecânicos.
Uma OS está associada a um veículo e a uma equipe.
Cada OS contém um ou mais serviços.
Cada serviço pode utilizar uma ou mais peças.
Os valores dos serviços são baseados na tabela de mão-de-obra.
