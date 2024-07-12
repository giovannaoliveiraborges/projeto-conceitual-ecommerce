# **Projeto Conceitual de Banco de Dados para E-Commerce**
Bem-vindo ao Projeto Conceitual de Banco de Dados para E-Commerce! Este repositório contém o design conceitual de um banco de dados para uma plataforma de comércio eletrônico. O banco de dados é estruturado para gerenciar produtos, clientes, pedidos, fornecedores e inventário de forma eficiente. Abaixo estão as especificações detalhadas para cada componente do banco de dados.

## **Visão Geral do Projeto**
Este projeto visa criar um banco de dados robusto e escalável para suportar um marketplace online onde múltiplos vendedores podem oferecer seus produtos. O design do banco de dados abrange vários aspectos, incluindo gerenciamento de produtos, informações de clientes, processamento de pedidos e relacionamento com fornecedores.

### **Especificações do Banco de Dados**

#### **Produto**
+ Plataforma: Todos os produtos são vendidos através de uma única plataforma online.
+ Vendedores: Produtos podem ter diferentes vendedores (terceiros).
+ Fornecedor: Cada produto tem um fornecedor.
+ Composição do Pedido: Um ou mais produtos podem compor um pedido.

#### **Cliente**
+ Cadastro: Clientes podem se cadastrar no site usando seu CPF (para pessoas físicas) ou CNPJ (para empresas).
+ Endereço: O endereço do cliente determina o valor do frete.
+ Múltiplos Pedidos: Um cliente pode fazer vários pedidos. Há um período de carência para devolução de produtos.

#### **Pedido**
+ Criação: Pedidos são criados por clientes e contêm informações de compra, endereço de entrega e status da entrega.
+ Composição: Um pedido pode ser composto por um ou mais produtos.
+ Cancelamento: Pedidos podem ser cancelados.

#### **Fornecedor & Estoque**
+ Fornecedores: Cada produto está vinculado a um fornecedor.
+ Gestão de Estoque: O sistema de inventário acompanha o estoque dos produtos.

#### **Refinamentos**

  + **Tipos de Clientes** 
    + PJ (Pessoa Jurídica) e PF (Pessoa Física): Uma conta pode ser PJ ou PF, mas não pode ter ambas as informações.

  + **Pagamento**
    + Múltiplos Métodos de Pagamento: Clientes podem cadastrar mais de um método de pagamento.

  + **Entrega**
    + Status e Rastreamento: Entregas possuem status e códigos de rastreamento.



_**Nota:** Este projeto é um design conceitual e pode exigir ajustes com base em requisitos de negócios específicos e casos de uso._

@digitalinnovationone
